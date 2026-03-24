# 🏢 Alto Contacto — Automatizaciones y Herramientas

Repositorio de scripts y herramientas desarrolladas durante mi trabajo como **Analista Programador** en Alto Contacto, empresa de call center con campañas para Scotiabank Perú.

---

## 📂 Proyectos

### 🤖 [auto-feedback-tc](./auto-feedback-tc/)
Automatización del procesamiento diario de feedback para la campaña de **Tarjetas de Crédito**.
Procesa archivos de gestión, aplica filtros de negocio, asigna gestores y sube resultados vía SFTP.

**Stack:** Python · pandas · paramiko · openpyxl

---

### 🤖 [auto-feedback-prestamos](./auto-feedback-prestamos/)
Automatización del procesamiento diario de feedback para la campaña de **Préstamos Personales**.
Incluye corrección de tipificaciones, jerarquía por DNI y subida automática al servidor SFTP.

**Stack:** Python · pandas · paramiko · openpyxl

---

## 🛠️ Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![pandas](https://img.shields.io/badge/pandas-data--processing-lightgrey?logo=pandas)
![SFTP](https://img.shields.io/badge/SFTP-paramiko-green)
![Windows](https://img.shields.io/badge/Windows-Task--Scheduler-blue?logo=windows)

---

## 🔒 Nota de seguridad

Todos los proyectos usan variables de entorno (`.env`) para manejar credenciales.
Los archivos `.env` **nunca se suben al repositorio**. Ver cada proyecto para el `.env.example` correspondiente.

---

## 👤 Autor

**Daniel Medina**  
Analista Programador | Arquitecto de Datos Jr.  
📍 Lima, Perú  
[GitHub](https://github.com/ZoldyckDRem)
