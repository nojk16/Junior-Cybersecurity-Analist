# Junior Cybersecurity Analyst Path (CJCA) - HTB Academy

Repositorio de documentacion tecnica, analisis de evidencia, reportes de laboratorio y desarrollo de capacidades practicas correspondientes a la ruta **Junior Cybersecurity Associate (CJCA)** en Hack The Box Academy. Este proyecto documenta la transicion integral entre la evaluacion de vulnerabilidades ofensivas (Red Team) y la respuesta defensiva a incidentes en operaciones de SOC (Blue Team).

---

## Estructura General del Repositorio

### 01-fundamentals/ (Fundamentos Tecnicos y Sistemas)
- **01-introduction-to-information-security**: Triada CIA, modelo AAA, gestion de riesgos y clasificacion de activos en operaciones SOC.
- **02-network-fundamentals**: Protocolos TCP/IP, modelo OSI, direccionamiento IPv4/IPv6 y puertos de red.
- **03-introduction-to-networking**: Enrutamiento, conmutacion, VLANs, inspeccion de paquetes y seguridad perimetral.
- **04-linux-fundamentals**: Arquitectura del kernel Linux, permisos POSIX, gestion de procesos y administracion del sistema.
- **05-introduction-to-bash-scripting**: Automatizacion de tareas en Linux, entrada/salida de datos y parsing de logs mediante Bash.
- **06-windows-fundamentals**: Arquitectura de Windows OS, Registro del Sistema, servicios y permisos en Active Directory.
- **07-introduction-to-windows-command-line**: Gestion de comandos mediante CMD y automatizacion de consultas administrativas en PowerShell.

### 02-web-fundamentals/ (Fundamentos Web y Protocolos)
- **01-web-requests**: Analisis del protocolo HTTP/HTTPS, metodos (GET/POST), cabeceras de peticion/respuesta y gestion de cookies.
- **02-introduction-to-web-applications**: Estructura de aplicaciones web, frontend vs backend y vectores de ataque iniciales.

### 03-red-team-offensive/ (Operaciones Ofensivas y Evaluacion de Amenazas)
- **01-introduction-to-penetration-testing**: Metodologias de auditoria, fases de un Pentest y alcance legal de pruebas.
- **02-pentesting-in-a-nutshell**: Ejecucion de pruebas de concepto (PoC), analisis de vectores de entrada y mitigacion de hallazgos.
- **03-network-enumeration-with-nmap**: Descubrimiento de hosts, escaneo de puertos, deteccion de servicios/OS y scripting mediante NSE.
- **04-footprinting**: Reconocimiento pasivo/activo, OSINT y recoleccion de informacion en infraestructura objetivo.
- **05-hacking-wordpress**: Identificacion de vulnerabilidades en CMS, auditoria de plugins/temas y fuerza bruta.
- **06-using-the-metasploit-framework**: Gestion de exploits, payloads, stagers, post-explotacion y sesion Meterpreter.

### 04-blue-team-defensive/ (Operaciones Defensivas, Triaje y SOC)
- **01-introduction-to-network-traffic-analysis**: Analisis profundo de capturas de red (PCAP) utilizando Wireshark y trazado de trafico malicioso.
- **02-incident-handling-process**: Fases del manejo de incidentes (NIST SP 800-61), contencion, host isolation y reporte de casos.
- **03-windows-event-logs-finding-evil**: Analisis de logs de eventos de Windows (Sysmon, Event Viewer, IDs 4624, 4104, 1) y deteccion de anomalías.
- **04-security-monitoring-and-siem-fundamentals**: Ingesta de logs, creacion de reglas de deteccion y triaje de alertas en Wazuh / SIEM.
- **05-introduction-to-threat-hunting-and-hunting-with-elastic**: Caza de amenazas en la red mediante queries KQL y analisis de telemetria en Elastic Stack.

