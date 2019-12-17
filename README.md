# Final_Project_StarTravel

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.18.
## Import Library for Python
<ul>
  <h6>1. Install Python</h6>
 
   <h6>2. Install Pip</h6>
    <p> Step 1: Check if PIP is Already Installed
    Type in the following command in the Command Console: <code>pip help</code>
If PIP responds, then PIP is installed; if there’s an error saying this program could not be found, then it isn’t.</p>

<p> Step 2: Verify Python Installation

To determine whether you have Python installed:

Open the Windows Command window.
When the console window opens, type in:
<code>python</code>
If this command is not unrecognized, Python will need to be installed before you can install PIP.

If the command is recognized, Python will respond with its version and a list of commands.

Step 1: Download PIP <a>get-pip.py</a>
Before installing PIP, you’ll need to download <a href="https://bootstrap.pypa.io/get-pip.py" target="_blank" rel="noopener noreferrer" data-cke-saved-href="https://bootstrap.pypa.io/get-pip.py">get-pip.py on pypa.io</a>

Download the file to a temporary folder in Windows or to the “Downloads” library of your Windows installation. You can download the file to anywhere but remember where it’s been saved.

Step 2: Launch Windows Command Line
Pip is a command line program. When you install PIP, a PIP command is added to your system.

To launch the Windows command line:

Press Windows Key + X.
Click on “Run.”
Type in “cmd.exe” and hit enter.
Alternatively, type “cmd.exe” in the Windows search bar and click on “Command Prompt.”

Both these options should open the Command Console. However, it should be noted that you may need to run the Command Console “As Administrator.” If you get an error at any point stating that you don’t have permissions to perform a task, this is generally the problem.

To run a Command Console “As Administrator,” right click on “Command Prompt” and then select the “Run as…” option.

Step 3: Installing PIP on Windows
Open the Command Console if it isn’t already open. Under the Windows command console, cd is the function to change directories. Use cd followed by a directory to navigate to the get-pip.py file.

To install PIP type in the following:

<code>py get-pip.py</code>
PIP should install itself. If the file isn’t found, you may need to navigate to a different directory.

You can view the contents of your current directory using the following command:

dir
The dir command will return a full listing of the contents of a directory.

Step 4: How to Check PIP Version
To check the current version of PIP type following command:

<code>pip --version</code>
This will report back the current version of the platform.
</ul>

## Import Library for Angular
<ul>
  <h6>1. Angular Material</h6>
  <pre>
    <code>ng add @angular/material</code>
  </pre>
  <p>Choose a prebuilt theme name, or "custom" for a custom theme: (Use arrow keys)</p>
  <p>=>Indigo/Pink        [ Preview: https://material.angular.io?theme=indigo-pink ]</p>
  <p>Set up HammerJS for gesture recognition? (Y/n) Y </p>
  <p>Set up browser animations for Angular Material? (Y/n) Y</p>
  
   <h6>2. Decode jwt</h6>
  <pre>
    <code>npm install jwt-decode</code>
  </pre>
</ul>

## Run Postgres
Open cmd:
<ul>
    <li><code>docker exec -it hoteldb psql -U postgres -d estay</code></li>
    <li><code>select Max(id) from users;</code></li>
    <li><code>select nextval('users_id_seq');</code></li>
    <li><code>select setval('users_id_seq',1785);</code></li>
</ul>

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

