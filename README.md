# Tarea-5
S.O , QEMU y nmap 
# Investigación sobre Sistemas Operativos Linux

Este proyecto tiene como finalidad explorar en profundidad distintas distribuciones del sistema operativo Linux, analizando su historia, características técnicas, aplicaciones principales y su importancia en distintos contextos (como servidores, escritorio, seguridad informática, etc.). El objetivo es comprender la diversidad y versatilidad del ecosistema Linux en el mundo real.

---

## Distribuciones Linux Investigadas

### 1. Debian
- **Historia**: Lanzado en 1993 por Ian Murdock como una distribución completamente libre y abierta. Fue una de las primeras en organizarse como un proyecto comunitario.
- **¿Qué es?**: Sistema operativo robusto y estable, base para muchas otras distribuciones.
- **Características**: Gran comunidad, estabilidad comprobada, arquitectura modular, más de 59,000 paquetes disponibles.
- **Usos comunes**: Servidores, entornos educativos, infraestructura de TI, base de Ubuntu y otras distribuciones.

### 2. Arch Linux
- **Historia**: Nació en 2002 con un enfoque de “hazlo tú mismo” para usuarios avanzados.
- **¿Qué es?**: Distribución minimalista que permite instalar solo lo necesario.
- **Características**: Rolling release (se actualiza constantemente), altamente personalizable, uso intensivo de línea de comandos.
- **Usos comunes**: Escritorios personalizados, estaciones de trabajo técnicas, entusiastas del software libre.

### 3. Rocky Linux
- **Historia**: Fundado por uno de los creadores originales de CentOS en 2020 tras el cambio de rumbo de Red Hat con CentOS.
- **¿Qué es?**: Clon binario compatible con RHEL (Red Hat Enterprise Linux), destinado al ámbito empresarial.
- **Características**: Estabilidad, actualizaciones de seguridad, ciclos de soporte extendido.
- **Usos comunes**: Centros de datos, servidores web y de aplicaciones, infraestructura empresarial.

### 4. Garuda Linux
- **Historia**: Una de las distribuciones más recientes, basada en Arch.
- **¿Qué es?**: Distro centrada en el rendimiento y el aspecto visual.
- **Características**: Kernel Zen optimizado, herramientas de configuración fáciles de usar, entornos llamativos (KDE Dr460nized).
- **Usos comunes**: Gaming en Linux, estaciones de trabajo de alto rendimiento, usuarios que buscan estética y funcionalidad.

### 5. Fedora
- **Historia**: Lanzado en 2003 por la comunidad con el patrocinio de Red Hat.
- **¿Qué es?**: Plataforma de desarrollo de software que incorpora tecnologías de vanguardia.
- **Características**: Software muy actualizado, versiones regulares cada 6 meses, integración con GNOME.
- **Usos comunes**: Desarrollo de software, pruebas de nuevas tecnologías, estaciones de trabajo.

### 6. Manjaro
- **Historia**: Fundada en 2011 como una versión más amigable de Arch Linux.
- **¿Qué es?**: Distribución fácil de usar basada en Arch pero con instalación y mantenimiento simplificado.
- **Características**: Soporte gráfico, controladores preinstalados, rolling release.
- **Usos comunes**: Escritorios para usuarios intermedios, estaciones de trabajo, educación.

### 7. CentOS (clásico)
- **Historia**: Apareció como una reconstrucción gratuita de RHEL; descontinuado oficialmente en 2021.
- **¿Qué es?**: Sistema operativo empresarial que ofrecía estabilidad y seguridad.
- **Características**: Compatible con RHEL, gratuito, ciclos largos de soporte.
- **Usos comunes**: Infraestructura empresarial, hosting web, servidores internos. Hoy en día reemplazado por Rocky Linux y AlmaLinux.

### 8. Kali Linux
- **Historia**: Sucedió a BackTrack Linux y fue creado por Offensive Security.
- **¿Qué es?**: Distribución especializada en ciberseguridad y pruebas de penetración.
- **Características**: Más de 600 herramientas de seguridad, entorno personalizado para expertos, configuración sigilosa.
- **Usos comunes**: Ethical hacking, forense digital, pruebas de seguridad, análisis de redes.

### 9. Linux Mint
- **Historia**: Fundada en 2006 para ofrecer una experiencia de escritorio más amigable que Ubuntu.
- **¿Qué es?**: Distro enfocada en facilidad de uso y compatibilidad.
- **Características**: Entorno Cinnamon propio, codecs multimedia incluidos, diseño intuitivo.
- **Usos comunes**: Escritorios domésticos, educación, migrantes de Windows.

### 10. Ubuntu
- **Historia**: Lanzada en 2004 por Canonical, basada en Debian.
- **¿Qué es?**: Una de las distribuciones más populares, pensada para usuarios de todos los niveles.
- **Características**: Versiones LTS (soporte por 5 años), centro de software, instalación sencilla.
- **Usos comunes**: Escritorios, servidores, nubes públicas, desarrollo de apps, IoT.

### 11. Alpine Linux
- **Historia**: Diseñada desde el inicio para ser ligera y segura.
- **¿Qué es?**: Distro minimalista ideal para contenedores y sistemas embebidos.
- **Características**: Tamaño reducido (<5 MB), musl libc, OpenRC, enfoque en seguridad.
- **Usos comunes**: Contenedores Docker, microservicios, servidores ligeros.

### 12. AlmaLinux
- **Historia**: Nació en 2021 como respuesta al fin de CentOS clásico.
- **¿Qué es?**: Clon de RHEL con enfoque comunitario.
- **Características**: Binariamente compatible con RHEL, soporte empresarial, actualizaciones seguras.
- **Usos comunes**: Entornos de producción, hosting, servidores corporativos.

## 🖥️ QEMU - Emulador y Virtualizador de Código Abierto

### ¿Qué es QEMU?

**QEMU** (Quick EMUlator) es un **emulador y virtualizador de código abierto**, desarrollado originalmente por Fabrice Bellard en 2003. Permite emular múltiples arquitecturas de hardware, así como virtualizar sistemas operativos completos en diferentes plataformas.

QEMU puede ser utilizado por sí solo o junto con otros gestores de máquinas virtuales como **KVM** (en Linux) para obtener una virtualización acelerada por hardware.

---

## Características Principales

 -**Virtualización completa y emulación** de CPU, dispositivos y periféricos.
 -Soporte para múltiples arquitecturas: x86, ARM, MIPS, PowerPC, SPARC, RISC-V, entre otras.
 -**Integración con KVM** para virtualización acelerada en sistemas Linux.
-  **Snapshots** de discos, clonación y almacenamiento en imágenes (formato `.qcow2`, `.raw`, `.vmdk`, etc.).
-  Virtualización de red, soporte para múltiples interfaces y modos (NAT, bridge, host-only).
-  Herramientas para pruebas de sistemas operativos, compiladores, y entornos de desarrollo cruzado.
-  Portabilidad: funciona en Linux, macOS, Windows y otras plataformas.

---

##  Diferencia entre Emulación y Virtualización

| Concepto       | Emulación                                        | Virtualización                                         |
|----------------|--------------------------------------------------|--------------------------------------------------------|
| Rendimiento    | Más lento (interpreta instrucciones de hardware) | Más rápido (usa hardware real del host)               |
| Compatibilidad | Alta: puede emular otras arquitecturas           | Limitada a la arquitectura del host                   |
| Uso común      | Probar sistemas en arquitecturas distintas       | Ejecutar varios sistemas en la misma arquitectura     |

---

##  Componentes de QEMU

- **qemu-system-ARCH**: Ejecuta una máquina virtual completa de la arquitectura especificada (ej. `qemu-system-x86_64`).
- **qemu-img**: Herramienta para crear, convertir y modificar imágenes de disco.
- **qemu-nbd**: Conecta imágenes de disco como dispositivos de bloque.
- **qemu-user**: Ejecuta binarios de usuario de otra arquitectura sin iniciar un sistema operativo completo.

---

## Ventajas de Usar QEMU
- Totalmente libre y de código abierto.
- Gran versatilidad: desde uso doméstico hasta sistemas avanzados de pruebas y desarrollo.
- Compatible con muchas herramientas y entornos como Libvirt, virt-manager, Proxmox, OpenStack.
- Soporte activo de la comunidad y contribución constante.

<img width="602" height="639" alt="image" src="https://github.com/user-attachments/assets/f1ce6879-9c7d-4fda-915f-430006fad5f9" />

## escaneo con nmap 
<img width="1308" height="138" alt="image" src="https://github.com/user-attachments/assets/45df8c59-5429-4bcb-a957-b66682ff6f99" />

### Interpretación del escaneo Nmap

- **Host is up (0.0000060s latency):**  
  El host `192.168.42.252` está activo y responde a la red. La latencia muy baja indica que la comunicación fue rápida.

- **All 1000 scanned ports are in ignored states:**  
  Se escanearon los 1000 puertos TCP más comunes, pero todos estaban cerrados o filtrados, por lo que Nmap los ignora en el reporte principal.

- **Not shown: 1000 closed tcp ports (reset):**  
  Todos los puertos respondieron con un RST (reset), lo que significa que **no hay servicios TCP escuchando** en esos puertos.

- **Service detection performed:**  
  Nmap intentó identificar servicios y versiones en puertos abiertos, pero al no encontrar ninguno, no se detectó ningún servicio.

### Conclusión

1. El host está **activo** en la red.
2. No se encontraron servicios TCP escuchando en los puertos escaneados.
3. Para buscar servicios adicionales, sería necesario escanear otros puertos o protocolos (por ejemplo UDP o puertos no estándar).




