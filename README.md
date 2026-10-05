# Portal de Autogestión de RRHH

Portal interno de autogestión de Recursos Humanos de Blue Open Data. Es el punto de acceso para que cada colaborador gestione sus ausencias y vacaciones y consulte las novedades de la empresa.

## Objetivo del MVP

El MVP centraliza dos circuitos:

- **Solicitudes de ausencias y vacaciones:** el colaborador solicita, su jefe aprueba o rechaza y RRHH toma conocimiento y gestiona la solicitud.
- **Comunicación de RRHH:** RRHH publica novedades y eventos para que todos los colaboradores puedan consultarlos.

## Tecnologías previstas

- **Frontend:** Angular.
- **Backend:** Java con Spring Boot.
- **Base de datos:** MySQL.

## Alcance del MVP

El MVP incluye:

1. Inicio de sesión y gestión de usuarios, áreas y jefes.
2. Pantalla de inicio con tarjetas de resumen, próximo feriado, cumpleaños del mes y calendario de eventos.
3. Solicitud de ausencias y vacaciones por parte de los colaboradores.
4. Aprobación o rechazo de solicitudes por parte del jefe.
5. Toma de conocimiento y gestión de solicitudes por parte de RRHH.
6. Carga manual del saldo de vacaciones por colaborador.
7. Consulta del historial de solicitudes propias.
8. Visualización de las ausencias del equipo por parte de cada jefe.
9. Publicación de novedades por RRHH, como anuncios, convocatorias y fechas de pago.
10. Publicación de eventos generales o dirigidos a un área.
11. Avisos dentro del portal y por correo electrónico.
12. Panel de configuración de RRHH para administrar tipos de ausencia, feriados, eventos, novedades, saldos, usuarios, áreas y jefes.

## Fuera de alcance

El MVP no incluye:

- Integración con Tango ni con otros sistemas externos.
- Consulta de recibos de sueldo.
- Firma de documentos.
- Aplicación móvil nativa.
- Notificaciones push.
- Reacciones o comentarios en las novedades.
- Liquidación de haberes o cálculo de descuentos. RRHH gestiona los descuentos fuera del sistema.

## Perfiles del sistema

- **Colaborador:** solicita ausencias y vacaciones, consulta sus solicitudes y visualiza novedades y eventos.
- **Jefe:** además de las funciones de colaborador, aprueba o rechaza solicitudes de las personas a su cargo y consulta sus ausencias.
- **RRHH:** administra usuarios y la configuración del portal, publica novedades y eventos y gestiona las solicitudes.

## Documentación y referencias

- [Documento Funcional del MVP](docs/documento-funcional-mvp.docx)
- [Mock navegable del portal](docs/mock-mvp.html)

## Estructura del repositorio

```text
/
├── docs/
│   ├── documento-funcional-mvp.docx
│   └── mock-mvp.html
├── .gitignore
└── README.md

