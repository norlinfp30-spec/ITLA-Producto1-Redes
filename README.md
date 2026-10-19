# Proyecto de Implementación Empresarial L2/L3

Instituto Tecnológico de las Américas (ITLA)
Asignatura: Conmutación y Enrutamiento (TI-203)
Profesor: Onel Luis Pelegrino

## 👥 Integrantes del Equipo 2
- Lia Shaday Pérez Santana - Matrícula: 2025-2258
- Nolberto Francisco Pérez - Matrícula: 2025-2263
- Sebastian Pujols Fernández - Matrícula: 2025-2713
- Brayner Thomas Martínez Muñoz - Matrícula: 2025-2268

## 📋 Descripción del Proyecto
Este repositorio contiene los scripts de configuración y la topología implementada en PNETLab correspondientes al Equipo 2 (Red IPv4: 172.18.0.0/15 | IPv6: 2001:25:18::/48). El objetivo principal es desplegar una red confiable, segura y escalable para una mediana empresa.

El proyecto cumple con los siguientes criterios técnicos:
- Segmentación: Creación de VLANs por departamentos y propagación mediante VTP.
- Redundancia L2/L3: Implementación de EtherChannel, STP y configuración de alta disponibilidad en el gateway utilizando HSRP.
- Enrutamiento: Implementación de OSPFv2 (soportando crecimiento multiarea) para la conectividad entre sucursales y el backbone.
- Seguridad: Restricción de accesos internos y a Internet mediante políticas de seguridad basadas en listas de control de acceso (ACLs) estándar y extendidas.
- Direccionamiento: Plan de direccionamiento estructurado para IPv4 (VLSM) e IPv6.

## 📁 Archivos Entregables
- Topologia.png: Captura de la topología física en PNETLab.
- SWM1.txt: Comandos de configuración del Switch Multicapa 1 (Gateway Principal).
- SWM2.txt: Comandos de configuración del Switch Multicapa 2 (Gateway Secundario).
- SWAC1.txt: Comandos de configuración del Switch de Acceso 1 (VLAN Docentes).
- SWAC2.txt: Comandos de configuración del Switch de Acceso 2 (VLAN Estudiantes).
- SWAC3.txt: Comandos de configuración del Switch de Acceso 3 (VLAN Gestión).
- SW.txt: Comandos de configuración del Switch del Datacenter.
- SWA13.txt: Comandos de configuración del Switch de Acceso (Académicos/Finanzas).
- R1-Core.txt: Comandos de configuración del router Core/Backbone.
- R2.txt: Comandos de configuración del router de la Sucursal.
- ISP.txt: Comandos de simulación del proveedor de Internet.
