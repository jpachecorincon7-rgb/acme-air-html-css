 # ✈️ ***ACME AIR***

## Descripción del Proyecto:
Este proyecto es una **aplicación web estática** creada para renovar la experiencia digital de la aerolínea **ACME AIR**.  
El objetivo es ofrecer una interfaz **moderna, clara y adaptable** pensada principalmente para dispositivos móviles, pero ajustable para tablets y escritorio.  

La aplicación web está construida únicamente con HTML5 Y CSS3, solo como parte visual, con navegación simulada. Toda la navegación se simula mediante enlaces entre páginas, lo que permite recorrer el flujo completo de usuario: iniciar sesión, registrarse, crear contraseña, buscar vuelos, hacer check-in y consultar reservas.

---

## 📋- Objetivos del Proyecto

El proyecto tiene como objetivo ofrecer a los usuarios de ACME AIR una aplicación web clara y responsiva que les permita:

- Iniciar sesión o crear una cuenta nueva de manera sencilla.  
- Definir y gestionar su contraseña de acceso.  
- Buscar vuelos según origen, destino y fechas, con opción de solo ida.  
- Consultar un listado de vuelos disponibles con información de ruta, horario y precio.  
- Realizar el check-in en línea ingresando su código de reserva y confirmando requisitos de seguridad.  
- Revisar el historial de vuelos y reservas activas.  
- Recuperar su contraseña en caso de olvido para mantener acceso seguro.  

En conjunto, la aplicación busca simular el flujo completo de gestión de viajes en una aerolínea, garantizando una experiencia intuitiva y coherente con la identidad visual de ACME AIR.


---
```
## ⚙️- Estructura del Proyecto
acme-air/
├── index.html                (Login)
├── menu.html                 (Menú principal)
├── registro.html             (Registro)
├── crear-contraseña.html     (Nueva contraseña)
├── buscar-vuelos.html        (Búsqueda de vuelos)
├── vuelos.html               (Vuelos disponibles)
├── checkin.html              (Check-in)
├── mis-vuelos.html           (Mis vuelos)
├── recuperar.html            (Recuperar contraseña)
├── css/
│   ├── style.css             (estilos generales)
│   ├── forms.css             (formularios)
│   ├── layout.css            (estructuras y grids)
│   └── responsive.css        (media queries)
└── img/
├── logo.png
├── icons/
└── backgrounds/
```
---

## ❔- Cómo usar la aplicación 
La aplicación no requiere de ningun tipo de instalación, para probarla ejecutamos (abrimos) los archivos `.html` en cualquier navegador web de preferencia.  

## 🖥️ - Flujo de navegación:
- **Login (index.html)** → acceso al menú principal, crear cuenta o recuperar contraseña.  
- **Registro (registro.html)** → formulario de datos personales, luego creación de contraseña.  
- **Crear contraseña (crear-contraseña.html)** → define la clave y redirige al menú.  
- **Menú principal (menu.html)** → centro de opciones: buscar vuelos, check-in, mis vuelos o cerrar sesión.  
- **Buscar vuelos (buscar-vuelos.html)** → formulario de búsqueda, con opción de solo ida.  
- **Vuelos disponibles (vuelos.html)** → tabla con rutas, fechas, horarios y precios.  
- **Check-In (checkin.html)** → ingreso de código de reserva y confirmación.  
- **Mis vuelos (mis-vuelos.html)** → listado de reservas activas y confirmadas.  
- **Recuperar contraseña (recuperar.html)** → ingreso de correo electrónico y enlace para crear nueva clave.  

---
## 📱- Responsividad
  Aunque la aplicación está pensada inicialmente para dispositivos móviles, también puede ser utilizada en tablets y escritorios ya que tiene una adaptación mediante **media queries**:  
- 320px / 480px → móviles
- 768px → tablets  
- 1024px → escritorio  

De forma que le podamos garantizar una experiencia que sea consistente sin importar el tamaño de pantalla.
---

## 👁️- Vistas

- **Login**

<img width="393" height="853" alt="image" src="https://github.com/user-attachments/assets/d7e0b772-ab5e-41a3-8243-631bbe6496ec" />

- **Menú Principal**

<img width="389" height="854" alt="image" src="https://github.com/user-attachments/assets/5dd99b5a-41a0-4aeb-9b97-e289eea421f2" />

- **Registro**
<img width="391" height="854" alt="image" src="https://github.com/user-attachments/assets/bc509c74-9622-4bc0-8fd4-22d50aa6a55b" />

- **Crear contraseña**
<img width="389" height="855" alt="image" src="https://github.com/user-attachments/assets/db799496-8a03-45b5-a2bf-1ebba7de3bd0" />

- **Buscar Vuelos**
<img width="389" height="828" alt="image" src="https://github.com/user-attachments/assets/2bcc485d-d4ae-4501-9a87-9b56ab1e86dd" />

- **Vuelos Disponibles**
<img width="390" height="857" alt="image" src="https://github.com/user-attachments/assets/a63dcb19-de20-4a1a-a58f-c9212c0c81be" />

- **Check-In**
<img width="391" height="855" alt="image" src="https://github.com/user-attachments/assets/4d076b06-66fb-4e95-869d-62a9a82d0e12" />

- **Mis Vuelos**
<img width="391" height="854" alt="image" src="https://github.com/user-attachments/assets/f8438e93-3509-47e0-b179-2f9eaa5ac859" />

- **Recuperar Contraseña**
 <img width="392" height="854" alt="image" src="https://github.com/user-attachments/assets/c3ff67db-ca99-4872-b8a0-61c2988c31af" />
