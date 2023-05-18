# Taller de XauenDevs

----

## Tailwinds CSS

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

app.css
@tailwind base;
@tailwind components;
@tailwind utilities;


## API endpoints
```javascript
- Obtener todos los empleados
    - GET
        - https://tallerxauendevs.up.railway.app/api/v1/employeds
- Registrar empleado
    - POST
        - https://tallerxauendevs.up.railway.app/api/v1/employeds
- Actualizar empleado
    - PATCH
        - https://tallerxauendevs.up.railway.app/api/v1/employeds/id
- Eliminar empleado
    - DELETE
        - https://tallerxauendevs.up.railway.app/api/v1/employeds/id
        
- Registrarse e inicar sesión 
    - POST
        - https://tallerxauendevs.up.railway.app/api/v1/users/register
        - https://tallerxauendevs.up.railway.app/api/v1/users/login

- Obtener usuario por id
    - GET
        - https://tallerxauendevs.up.railway.app/api/v1/users/id
```