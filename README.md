# DOMUM Tools 0.77.0 Beta

Canal público oficial de DOMUM Tools para AutoCAD 2020 a 2026.

[Descargar la beta](../../releases/latest) ·
[Solicitar acceso](../../issues/new?template=beta-license.yml) ·
[Reportar un error](../../issues/new?template=bug-report.yml) ·
[Proponer una mejora](../../issues/new?template=feature-request.yml)

## Qué incluye

- Espacios arquitectónicos vinculados con nombre, código, superficie y
  perímetro opcional.
- Preparación topográfica de predios.
- Cuadros de construcción editables.
- Subdivisiones automáticas y manuales.
- Láminas generales e individuales.
- Importación y exportación de coordenadas GNSS.
- Publicación y actualización firmada.
- Centro de errores y sugerencias con vista previa y control de privacidad.
- Recuperación local antes de operaciones críticas, sin sobrescribir el DWG.
- Activación central vinculada al equipo y revocación remota desde un portal
  administrativo independiente de AutoCAD.

## Instalación

1. Descarga `DOMUMTools-Beta-Setup.zip` desde la versión más reciente.
2. Cierra AutoCAD.
3. Descomprime el archivo y ejecuta `INSTALAR-DOMUM.cmd`.
4. Abre AutoCAD y ejecuta `DOMUMLICENCIA`.
5. Solicita una licencia temporal, pega la clave recibida y pulsa
   `Validar ahora`.

El instalador comprueba firma RSA y huella SHA-256, instala únicamente para el
usuario actual y conserva una licencia existente al actualizar.

Un solo paquete selecciona automáticamente la DLL compatible para AutoCAD
2020, 2021-2024 o 2025-2026.

## Requisitos

- Windows de 64 bits.
- AutoCAD 2020, 2021, 2022, 2023, 2024, 2025 o 2026 de 64 bits.
- Conexión a Internet para obtener actualizaciones y validar la licencia beta.

## Seguridad

Las actualizaciones y licencias se firman fuera de este repositorio. DOMUM
rechaza paquetes alterados, licencias vencidas y licencias asignadas a otro
equipo. La clave privada permanece únicamente en el servidor de licencias;
este repositorio no contiene el código fuente ni secretos administrativos.

Software creado por **ARQ. ERICK GARCÉS GRAJALES**.
