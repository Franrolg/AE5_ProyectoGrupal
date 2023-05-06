# Módulo 6 - Django Grupal 5

## Instalar el aplicativo

1. git clone https://github.com/Franrolg/AE5_ProyectoGrupal.git
2. python -m venv .env
3. source .env/Scripts/activate
4. pip install -r requirements.txt
5. python manage.py runserver

## Usuario sin registrar

- Solo podrá ver la página de login y al registro de usuarios.
- Las secciones de usuarios (listado) y proveedores, no podrán ser accesibles mientrar no esté logueado.


## Usuario registrado

- Podrá iniciar sesión y así consultar el listado de usuarios, como también registrar proveedores en la BD.


- Cuando se inicia sesión, solo los usuarios que son administradores podrán registrar usuarios, estos usuarios registrados podrán ser usuarios normale, staff o superusuario.
- Los usuarios normales solo podrán ver las tablas de usuarios y proveedores registrados.
- Los usuarios staff podrán ver las tablas de usuarios y proveedores, también podrán registrar estos últimos.
- Los usuarios staff tendrán acesso a admin, pero solo podrá editar datos, no podrán ingresar, ni eliminar
- Los usuarios normales solo tendrán acceso a la web y vista de las tablas
- Los superusuarios podrán ver todo.