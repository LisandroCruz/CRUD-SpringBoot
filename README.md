
# Manual de Usuario - Sistema de Gestión de Estudiantes // Español

Este manual proporciona una guía detallada sobre cómo utilizar el Sistema de Gestión de Estudiantes. El sistema está diseñado para realizar operaciones básicas de un CRUD (Crear, Leer, Actualizar, Eliminar) en estudiantes almacenados en una base de datos en Mysql Workbench. A continuación, se describen las funciones principales y cómo utilizarlas.


# 0. Login:
   Para poder hacer uso del programa debes de iniciar sesión con un usuario y una contraseña previamaente creados

# 1. Lista de Estudiantes:
Al abrir la aplicación, se mostrará una lista de estudiantes actualmente almacenados en la base de datos. La lista incluirá información como el nombre, apellido y correo electrónico


# 2. Agregar un PRODUCTO:
Para agregar un nuevo estudiante, sigue estos pasos:

Haz clic en el enlace "Agregar" 
Se abrirá un formulario con campos para el nombre, descripción, unidad y precio
Ingresa la información del nuevo producto
Haz clic en el botón "Agregar" para guardar el nuevo estudiante.

 # 3. Modificar un producto:
Para modificar un estudiante existente, sigue estos pasos:

Busca el estudiante que deseas modificar en la lista de estudiantes.
Haz clic en el enlace "actualizar" junto al estudiante deseado.
Se abrirá un formulario prellenado con la información actual del estudiante.
Modifica los campos que desees actualizar.
Haz clic en el botón "Guardar" para aplicar los cambios.

# 4. Eliminar un producto:
Para eliminar un producto existente, sigue estos pasos:

Busca el producto que deseas eliminar en la lista de productos.
Haz clic en el enlace "Eliminar" junto al estudiante deseado.
Confirma la eliminación cuando se te solicite.

# 5. Empleados:
En la página se mostra un apartado el cual se llama empleados en el cual se podra agregar un empleado, con los campos a llenar de: Nombre, Correo y Contraseña.

# 6. Actualizar información de empleados.
La persona utilizando el programa puede modificar la información de los usuarios de ser necesario y también puede borrar usuarios

# User Manual - Student Management System // English

This manual provides a detailed guide on how to use the Student Management System. The system is designed to perform basic CRUD (Create, Read, Update, Delete) operations on students stored in a MySQL Workbench database. Below are the main functions and how to use them.

# 0. Login:
To use the program, you must log in with a previously created username and password.

# 1. product List:
Upon opening the application, a list of product currently stored in the database will be displayed. The list will include information such as name, last name, and email.

# 2. Add a product:
To add a new student, follow these steps:

1. Click on the "Add" link.
2. A form with fields for name, description, unit, and price will open.
3. Enter the information for the new student.
4. Click the "Add" button to save the new student.

# 3. Modify a product:
To modify an existing student, follow these steps:

1. Find the student you want to modify in the list of students.
2. Click on the "Update" link next to the desired student.
3. A form pre-filled with the current student information will open.
4. Modify the fields you want to update.
5. Click the "Save" button to apply the changes.

# 4. Delete a Student:
To delete an existing product, follow these steps:

1. Find the student you want to delete in the list of students.
2. Click on the "Delete" link next to the desired student.
3. Confirm the deletion when prompted.

# 5. Employees:
On the page, there is a section called "Employees" where you can add an employee with fields to fill in: Name, Email, and Password.

# 6. Update Employee Information:
The person using the program can modify user information if necessary and also delete users.

# Imagénes ilustrativas
![image](https://github.com/LisandroCruz/CRUD-SpringBoot/assets/145726150/d0165850-41ce-410a-905f-4130d732a050)

![image](https://github.com/LisandroCruz/CRUD-SpringBoot/assets/145726150/50f11133-bd9c-456d-ace3-198952e3d6bf)

![image](https://github.com/LisandroCruz/CRUD-SpringBoot/assets/145726150/47253531-8271-4556-bb59-60cf51d3ec13)

# Manual técnico // español

1. Introducción
El Sistema de Gestión de Estudiantes es una aplicación de software diseñada para realizar operaciones CRUD en datos de estudiantes almacenados en una base de datos de MySQL Workbench. Este manual técnico proporciona información detallada sobre la arquitectura, componentes y funcionalidad del sistema.

2. Arquitectura del Sistema
2.1 Frontend
El frontend de la aplicación se construye utilizando tecnologías web, que incluyen HTML, CSS y JavaScript para crear una interfaz fácil de usar. El usuario interactúa con el sistema a través de páginas web que facilitan la navegación sin problemas.

2.2 Backend
El backend se implementa utilizando un lenguaje del lado del servidor, como Python o Node.js. Maneja las solicitudes de los usuarios, procesa datos e interactúa con la base de datos. La comunicación entre el frontend y el backend se facilita mediante solicitudes HTTP.

2.3 Base de Datos
La base de datos de MySQL Workbench almacena información de estudiantes y empleados. Está estructurada para admitir operaciones CRUD de manera eficiente. El esquema de la base de datos incluye tablas para estudiantes y empleados, capturando información relevante como nombres, direcciones de correo electrónico y contraseñas.

3. Funcionalidad del Sistema
3.1 Autenticación de Usuarios (Login)
Los usuarios deben iniciar sesión con un nombre de usuario y contraseña preexistentes para acceder al sistema. La autenticación se maneja de manera segura para proteger la información del usuario.

3.2 Lista de productos
Al iniciar sesión, el sistema muestra una lista de estudiantes recuperada de la base de datos. La lista incluye detalles como nombres, apellidos y direcciones de correo electrónico.

3.3 Agregar un producto
Para agregar un nuevo producto, el usuario hace clic en el enlace "Agregar", lo que abre un formulario con campos para nombre, descripción, unidad y precio. Al ingresar la información, hacer clic en el botón "Agregar" guarda al nuevo estudiante en la base de datos.

3.4 Modificar un producto
Los usuarios pueden modificar la información de los productos existentes seleccionando el enlace "Actualizar" junto al estudiante deseado. Esto abre un formulario prellenado con la información actual, permitiendo a los usuarios realizar cambios. Hacer clic en el botón "Guardar" aplica las actualizaciones a la base de datos.

3.5 Eliminar un producto
Para eliminar un producto, los usuarios hacen clic en el enlace "Eliminar" junto al estudiante deseado, confirmando la eliminación cuando se les solicita. El sistema garantiza la integridad de los datos durante este proceso.

3.6 Gestión de Empleados
El sistema incluye una sección de empleados donde los usuarios pueden agregar empleados con campos para nombre, correo electrónico y contraseña. Además, los usuarios pueden actualizar y eliminar información de empleados según sea necesario.

4. Consideraciones de Seguridad
El sistema incorpora medidas de autenticación seguras para proteger las cuentas de usuario y la información sensible. Además, se implementa validación y saneamiento de datos para prevenir vulnerabilidades de seguridad comunes como la inyección de SQL.

5. Mejoras Futuras
Posibles mejoras futuras pueden incluir la implementación de características adicionales, una interfaz de usuario mejorada e integración con otros sistemas para una funcionalidad mejorada.

6. Conclusión
Este manual técnico proporciona una visión general de la arquitectura, funcionalidad y consideraciones de seguridad del Sistema de Gestión de Estudiantes. Tanto usuarios como desarrolladores pueden utilizar este documento como referencia para comprender y mantener el sistema.

# Technical Manual // English

## 1. Introduction
The Student Management System is a software application designed to perform CRUD operations on student data stored in a MySQL Workbench database. This technical manual provides detailed information about the architecture, components, and functionality of the system.

## 2. System Architecture
### 2.1 Frontend
The application's frontend is built using web technologies, including HTML, CSS, and JavaScript, to create a user-friendly interface. Users interact with the system through web pages that facilitate seamless navigation.

### 2.2 Backend
The backend is implemented using a server-side language such as Python or Node.js. It handles user requests, processes data, and interacts with the database. Communication between the frontend and backend is facilitated through HTTP requests.

### 2.3 Database
The MySQL Workbench database stores information about students and employees. It is structured to efficiently support CRUD operations. The database schema includes tables for students and employees, capturing relevant information such as names, email addresses, and passwords.

## 3. System Functionality
### 3.1 User Authentication (Login)
Users must log in with pre-existing usernames and passwords to access the system. Authentication is handled securely to protect user information.

### 3.2 Product List
Upon logging in, the system displays a list of students retrieved from the database. The list includes details such as names, last names, and email addresses.

### 3.3 Add a Product
To add a new product, the user clicks the "Add" link, opening a form with fields for name, description, unit, and price. After entering the information, clicking the "Add" button saves the new student to the database.

### 3.4 Modify a Product
Users can modify information about existing products by selecting the "Update" link next to the desired student. This opens a pre-filled form with current information, allowing users to make changes. Clicking the "Save" button applies updates to the database.

### 3.5 Delete a Product
To remove a product, users click the "Delete" link next to the desired student, confirming deletion when prompted. The system ensures data integrity throughout this process.

### 3.6 Employee Management
The system includes an employee section where users can add employees with fields for name, email, and password. Additionally, users can update and delete employee information as needed.

## 4. Security Considerations
The system incorporates secure authentication measures to protect user accounts and sensitive information. Additionally, data validation and sanitation are implemented to prevent common security vulnerabilities such as SQL injection.

## 5. Future Enhancements
Possible future enhancements may include implementing additional features, improving the user interface, and integrating with other systems for enhanced functionality.

## 6. Conclusion
This technical manual provides an overview of the architecture, functionality, and security considerations of the Student Management System. Users and developers alike can use this document as a reference for understanding and maintaining the system.


