# Club Deportivo · Sistema de gestión de escritorio

Aplicación de escritorio para administrar un club deportivo: ingreso de usuarios, registro de socios y no socios, cobro de cuotas mensuales y actividades, control de vencimientos y emisión del carnet de socio.

Proyecto integrador de la materia Desarrollo de Sistemas Orientados a Objetos de la Tecnicatura Superior en Desarrollo de Software (IFTS N.º 29), 2024. Lo desarrollamos en equipo de dos; este repositorio es una copia del original con todo su historial de commits.

## Funciones

- Inicio de sesión con usuarios y roles
- Registro de socios y no socios
- Pago de cuota mensual y de actividades, con comprobante
- Listado de vencimientos
- Emisión y vista previa del carnet de socio

## Stack

- **C#** con **Windows Forms** sobre .NET Framework 4.7.2
- **MySQL** con MySql.Data
- Organización en capas: formularios, capa de datos (`Datos/`) y entidades (`Entidades/`)

## Correrlo

1. Crear la base ejecutando `ProyectoIntegrador.sql` en MySQL.
2. Abrir `ClubDeportivo-DSOO-PI.sln` en Visual Studio y ejecutar.
3. Al iniciar, la aplicación pide los datos de conexión (servidor, usuario y contraseña de MySQL).

La documentación del proyecto está en `PIClub -Soria-Vago.pdf`.
