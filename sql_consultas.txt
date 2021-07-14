USE twitter; 
SELECT * FROM users ;
/*insertar un valor */
INSERT INTO twitter.users (id,first_name, last_name,handle, birthday, created_at, updated_at) 
VALUES ('9','rene', 'carrera', 'errante1313', '1991-07-16', '2010-02-01 00:00:01', '2010-02-01 00:00:01');
/*actualizar un valor  */
UPDATE users 
set first_name = 'roberto', last_name ='lagos', handle = 'desastre'
where id = 9; 

/*borrar un valor */

delete from users where id = 8; 
select * from users;

/*actualizar id del un valor borrado */
 update users 
 set id = 8
 where id = 9; 
select * from users;