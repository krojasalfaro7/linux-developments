# Utilidades y comandos utiles para MYSQL

## Cambiar clave de un usuario [DOCKER]

	docker exec -it db_mysql mysql -u root -p [Ingresar clave root del usuario del SO]
	ALTER USER 'user'@'%' IDENTIFIED BY 'newpass';

## Crear usuario
	
	CREATE USER 'user'@'%' IDENTIFIED BY 'userpass';
