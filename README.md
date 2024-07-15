# F o r o H u b 
 <p align="left">
   <img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green">
   <img src="https://camo.githubusercontent.com/0334988e8d4190c3a5068f84b1c0656313c3739b4e707c098d7c093b3d1dbeb3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4944452d496e74656c6c696a5f494445412d626c7565">
   <img src="https://camo.githubusercontent.com/c1df072de064a136599447b3fdf8fcd9b20e34b68a0eecb81c806f66647eba5f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e675f426f6f742d76332e332e302d626c7565">
   <img src="https://camo.githubusercontent.com/da873c99918ec7317aae354758b05b67148a7806fa448329d12fb658ed169c90/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f506f737467726553514c2d7631342e31322d626c7565">
   </p>
 
Introducción

ForoHub es una plataforma API REST desarrollada con Spring Boot, diseñada para facilitar la gestión de tópicos en una comunidad virtual. Permite a los usuarios autenticarse, crear, listar y eliminar tópicos de discusión de manera eficiente y segura mediante autentificación JWT.

aracterísticas ✨

Registro de Usuarios: Registro seguro de nuevos usuarios mediante endpoint POST /signup.

Autenticación JWT: Generación de tokens JWT para inicio de sesión seguro con POST /login.

Gestión de Tópicos: Creación (POST /topicos), listado (GET /topicos o GET /topicos{id} ), actualización (PUT /topicos/{id}) y eliminación (DELETE /topicos/{id}) de tópicos disponibles.
