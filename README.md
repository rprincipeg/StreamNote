# StreamNote

Plataforma educativa web para gestionar notas y tareas personales, compartirlas con otros usuarios, publicarlas en comunidades de estudio y realizar transmisiones en vivo dentro de ellas.

> Proyecto grupal del curso de **Infraestructura** — Universidad Privada Antenor Orrego (UPAO), Trujillo, Perú.

## Equipo

| Integrante | GitHub |
|---|---|
| [André Castañeda Astudillo] | [@Andrecas] |
| [Renzo Principe Guadiamos] | [@rprincipeg] |
| [Bryan Edwars Rodríguez] | [@EdwBryan] |

## Funcionalidades

- Notas con texto e imágenes.
- Tareas y recordatorios personales.
- Compartir notas con otro usuario.
- Comunidades de estudio públicas y privadas.
- Streaming en vivo dentro de las comunidades (solo administradores), con chat y grabaciones.
- Notificaciones push del navegador.
- Inicio de sesión con cuenta de Google.

> Alcance actual: solo aplicación web, sin aplicaciones móviles.

## Arquitectura

La arquitectura se diseña sobre AWS con un enfoque serverless. El diagrama estará disponible en `docs/arquitectura/`.

# Flujo de trabajo
- Una rama por funcionalidad: feature/nombre-de-la-funcionalidad.
- Cambios a main únicamente mediante pull request revisado por otro integrante.
- No subir credenciales, claves ni identificadores de cuentas de AWS al repositorio.