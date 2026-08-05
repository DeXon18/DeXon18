<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DeXon18/DeXon18/output/galaga-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DeXon18/DeXon18/output/galaga-contribution-graph.svg">
  <img alt="Gráfico de contribuciones de GitHub con estilo Galaga" src="https://raw.githubusercontent.com/DeXon18/DeXon18/output/galaga-contribution-graph.svg">
</picture>

---

<div align="center">

# 👋 ¡Hola! Soy DeXon

### Software industrial, automatización e infraestructura self-hosted
</div>

---

## 💻 Código que nace de problemas reales

Me apasionan la tecnología, los servidores, Proxmox VE, la domótica y automatizar todo lo que se deje automatizar.

Y, claro, el desarrollo de software. Al final, el código es lo que conecta todo lo demás.

Es donde más disfruto: cuando una idea deja de ser una idea y se convierte en una herramienta que alguien utiliza de verdad. La mayoría de mis proyectos nacen de una necesidad propia o de una tarea real que se estaba haciendo a mano.

Si algo me resulta útil a mí o a mi equipo, probablemente también pueda ayudar a alguien más.

---

## 🧭 A qué me dedico

Trabajo desarrollando y manteniendo herramientas para entornos de ingeniería y software industrial.

Mi día a día está a medio camino entre el soporte técnico, el desarrollo de software y la automatización:

* 🔑 Gestión y auditoría de licencias industriales.
* 🏭 Herramientas para Siemens Designcenter NX, Simcenter 3D y Moldex3D.
* 🖥️ Automatización de configuraciones y procedimientos de soporte.
* 📊 Portales internos para centralizar clientes, máquinas, productos e historial.
* 🔄 Flujos con n8n para conectar servicios y eliminar tareas repetitivas.
* 🧰 Scripts PowerShell, Bash y Batch para resolver operaciones concretas.

Lo que más me gusta es terminar una herramienta y que alguien pregunte:

> «¿Esto siempre estuvo aquí y no lo sabíamos?»

Eso es exactamente lo que busco.

---

## 🏠 Mi laboratorio en casa

Fuera del trabajo mantengo mi propia infraestructura sobre **Proxmox VE**.

No es un laboratorio de montar algo durante una tarde y apagarlo después. Son servicios reales que utilizo a diario, con almacenamiento, copias de seguridad, monitorización y acceso remoto.

<p align="center">
  🖥️ Proxmox VE &nbsp;·&nbsp;
  📦 LXC y máquinas virtuales &nbsp;·&nbsp;
  💾 ZFS &nbsp;·&nbsp;
  🛡️ Proxmox Backup Server &nbsp;·&nbsp;
  🐳 Docker
</p>

Dentro conviven servicios como:

* 🏠 **Home Assistant**, para persianas, toldos, sensores, iluminación y automatizaciones.
* 🔁 **n8n**, conectando aplicaciones, procesos y notificaciones.
* 📷 **Immich**, para gestionar mi biblioteca personal de fotografías y vídeos.
* 🎬 **Plex**, para contenido multimedia.
* 🛡️ **Pi-hole**, para DNS y filtrado de red.
* 🌐 **Cloudflare Tunnel**, para publicar servicios sin abrirlos directamente a Internet.
* 🔐 **Tailscale**, como vía de acceso remoto y recuperación.
* 📈 Herramientas de monitorización, copias y sincronización.

También me ha tocado hacer la parte menos vistosa: recuperar servicios después de un fallo de almacenamiento, evacuar contenedores, aislar un pool ZFS dañado, validar copias y checksums, reorganizar datasets y devolver la plataforma a producción.

Ahí es donde una infraestructura deja de ser una colección de contenedores y empieza a parecerse a un sistema bien diseñado.

Me gusta que las cosas funcionen sin tener que estar encima. Si necesito intervenir continuamente, algo está mal planteado.

---

## 🌟 Proyectos que me hacen sentir orgulloso

### 🛡️ [DX License Manager](https://github.com/DeXon18/DX-License-Manager)

Portal web para centralizar la gestión técnica, auditoría y control de licencias industriales de Siemens y Moldex3D.

Reúne en un mismo sitio clientes, máquinas, productos, archivos de licencia, historial, renovaciones y herramientas de auditoría. Nació para sustituir información repartida entre hojas de cálculo, correos y comprobaciones manuales.

`Laravel` · `PHP` · `Blade` · `Alpine.js` · `MariaDB` · `Redis` · `n8n`

---

### 🖥️ [Proxmox Tool Suite](https://github.com/DeXon18/Proxmox-Tool-Suite)

Script Bash interactivo para gestionar tareas habituales de Proxmox VE sin tener que recordar cada comando.

Permite trabajar con contenedores LXC, actualizaciones, limpieza, `fstrim`, mantenimiento del sistema y configuración de bind mounts desde un menú sencillo.

Nació porque yo mismo lo necesitaba. Como casi todo lo que construyo.

`Bash` · `Proxmox VE` · `Linux` · `LXC`

---

### 🔐 [DX Composite Manager](https://github.com/DeXon18/DX-Composite-Manager)

Conjunto de herramientas para obtener los identificadores de máquina utilizados en la generación de licencias de Siemens y Dassault Systèmes.

Está pensado tanto para usuarios finales como para personal de soporte, con scripts separados según el fabricante y validaciones para distintos tipos de equipo.

`PowerShell` · `Bash` · `Batch` · `Windows` · `Linux`

---

### 🔄 [Siemens License Manager](https://github.com/DeXon18/Siemens-License-Manager)

Utilidad PowerShell para cambiar la configuración de licencias de Designcenter NX y Simcenter 3D entre servidores locales y cloud.

Detecta las versiones instaladas, actualiza variables de entorno y claves del registro, protege instalaciones antiguas y conserva la configuración del servidor local.

Es pequeño, concreto y hace exactamente lo que promete.

`PowerShell` · `Windows Registry` · `Siemens NX` · `Simcenter 3D`

---

### 📊 [ATS DX License Control](https://github.com/DeXon18/ATS-DX-License-Control-PS)

Herramienta para consultar licencias FlexNet y Siemens mediante `lmutil.exe`, sin tener que ejecutar y recordar los comandos manualmente.

Convierte una operación técnica repetitiva en un procedimiento más claro para soporte y diagnóstico.

`PowerShell` · `FlexNet` · `lmutil` · `Windows`

---

## 🧠 Mi filosofía

> «Si algo es útil para ti, probablemente también lo sea para alguien más.
> Hazlo bien desde el principio, porque siempre fue primero para ti.»

Intento que cada cosa que publico tenga una finalidad clara, esté documentada y pueda utilizarse sin tener que adivinar cómo funciona.

No me gusta dejar proyectos a medias ni código que dé miedo volver a tocar unos meses después.

Aunque, siendo realistas, siempre encuentras algo que mejorar cuando regresas a un proyecto antiguo. Y eso también forma parte del proceso.

---

## 🛠️ Tecnologías y herramientas

### 👨‍💻 Desarrollo y scripting

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square\&logo=powershell\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square\&logo=php\&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square\&logo=laravel\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square\&logo=nodedotjs\&logoColor=white)

### 🖥️ Sistemas e infraestructura

![Proxmox VE](https://img.shields.io/badge/Proxmox%20VE-E57000?style=flat-square\&logo=proxmox\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square\&logo=debian\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![OpenZFS](https://img.shields.io/badge/OpenZFS-2C5BB4?style=flat-square\&logo=openzfs\&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square\&logo=tailscale\&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square\&logo=cloudflare\&logoColor=white)

### ⚙️ Automatización y datos

![Home Assistant](https://img.shields.io/badge/Home%20Assistant-18BCF2?style=flat-square\&logo=homeassistant\&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square\&logo=n8n\&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square\&logo=mariadb\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square\&logo=redis\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)

### 🏭 Software industrial

![Siemens](https://img.shields.io/badge/Siemens-009999?style=flat-square\&logo=siemens\&logoColor=white)
![Designcenter NX](https://img.shields.io/badge/Designcenter%20NX-009999?style=flat-square)
![Simcenter 3D](https://img.shields.io/badge/Simcenter%203D-005F87?style=flat-square)
![Moldex3D](https://img.shields.io/badge/Moldex3D-ED1C24?style=flat-square)
![FlexNet](https://img.shields.io/badge/FlexNet-4B5563?style=flat-square)

---

<p align="center">
  <sub>Construyendo herramientas, automatizando procesos y manteniendo servidores desde España 🇪🇸</sub>
</p>
