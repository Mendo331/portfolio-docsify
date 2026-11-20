# Licencias de software

En el ámbito profesional y educativo es esencial conocer los distintos tipos de licencias de software para cumplir la legalidad, planificar costes y garantizar la compatibilidad de formatos.

## Comparativa de tipos de licencia

| Tipo de licencia | Coste habitual | Código fuente | Uso y modificación |
| :--- | :--- | :---: | :--- |
| **Propietaria / Comercial** | De pago (suscripción o licencia única) | Cerrado | Limitado a las condiciones del fabricante |
| **GPL (Copyleft)** | Gratuito | Abierto | Libre uso, estudio, modificación y redistribución bajo la misma licencia |
| **MIT / BSD (Permisiva)** | Gratuito | Abierto | Libre uso incluso en proyectos propietarios manteniendo el aviso de autoría |
| **Freeware / Trial** | Gratuito (o limitado por tiempo) | Cerrado | Permite el uso sin acceso al código ni derecho a modificar |

## Ejemplo de comprobación del sistema en consola

```powershell
# Consultar versión y tipo de sistema operativo en Windows
systeminfo | findstr /B /C:"OS Name" /C:"OS Version" /C:"System Type"