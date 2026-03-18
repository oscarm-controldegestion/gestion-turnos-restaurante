# Gestion de Turnos - Restaurante

Aplicacion web para gestion de turnos del personal de restaurante.

## Acceso al Sistema

| Usuario   | Contrasena    | Rol              | Seccion       |
|-----------|---------------|------------------|---------------|
| admin     | admin123      | Administrador    | Administracion|
| cocina    | cocina123     | Encargado        | Cocina        |
| servicio  | servicio123   | Encargado        | Servicio      |
| sushi     | sushi123      | Encargado        | Sushi         |
| barra     | barra123      | Encargado        | Barra         |

## Funcionalidades

- Carga de turnos semana siguiente y mes siguiente
- Tipos de turno: M=Manana, T=Tarde, N=Noche, MT=Partido, L=Libre, F=Franco, V=Vacaciones
- Exportacion PDF para todos los usuarios
- Exportacion Excel solo para usuario admin
- Historial de turnos guardados

## Uso

1. Abrir index.html en el navegador
2. Iniciar sesion con usuario y contrasena
3. Completar los turnos y guardar
4. Exportar a PDF o Excel

## Tecnologias

- HTML5 + CSS3 + JavaScript
- jsPDF para generacion de PDFs
- SheetJS para exportacion a Excel
- localStorage para persistencia local
