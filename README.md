# PokerArg - Plataforma de Torneos de Póker

## Descripción
PokerArg es un sitio de póker en línea que permite a los usuarios registrarse, iniciar sesión y participar en torneos. 
Los administradores pueden crear torneos configurando:
- Cantidad de fichas iniciales por jugador.
- Tiempo de registro antes del torneo.
- Cambios de color en la interfaz según el estado del torneo:
  - Amarillo: Falta mucho tiempo.
  - Azul: Falta poco tiempo.
  - Rojo: El torneo ha comenzado.

## Instalación

### Requisitos previos:
- Node.js y npm instalados.
- MongoDB (local o en la nube).

### Pasos:
1. Clonar el repositorio:
   ```sh
   git clone https://github.com/TU-USUARIO/pokerarg.git
   cd pokerarg
   ```

2. Instalar dependencias:
   ```sh
   cd backend
   npm install
   ```

3. Configurar variables de entorno (`.env` en backend):
   ```
   MONGODB_URI=mongodb://localhost:27017/pokerarg
   JWT_SECRET=tu_clave_secreta
   ```

4. Iniciar el servidor:
   ```sh
   npm start
   ```

5. Abrir el `index.html` en un navegador.

## Despliegue
Se puede desplegar en plataformas como **Railway**, **Render**, o **Vercel**.

## Autor
PokerArg Development Team
