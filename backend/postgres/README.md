python generateDB.py
python migrate.py
python export_schema.py

docker exec -it hoteldb psql -U postgres -d estay

select Max(id) from users;
select setval('users_id_seq',1787);