# Conceptos de Redes

## NIC (Tarjeta de Interfaz de Red)
Las NIC permiten la conexión de una computadora a una red y gestionan la transmisión y recepción de datos.

## PDU (Unidad de Datos de Protocolo)
Es una unidad de datos utilizada para transmitir información en un nivel específico del modelo OSI.

## Medios de Transmisión
- Cable Trenzado No Blindado (UTP)
- Cable Trenzado Blindado (STP)
- Cable Coaxial

## Tipos de Fibra Óptica
1. Fibra Óptica Monomodo
2. Fibra Óptica Multimodo

## Protocolo OSI
1. Capa Física: Transmite bits.
2. Capa de Enlace de Datos: Utiliza direcciones MAC (dirección física).
3. Capa de red: IP (Internet Protocol), ICMP (Internet Control Message Protocol).
4. Capa de transporte: TCP (Transmission Control Protocol), UDP (User Datagram Protocol).
5. Capa de sesión: NFS (Network File System), SMB (Server Messaging Block).
6. Capa de presentación: SNMP (Simple Network Management Protocol).
7. Capa de aplicación: FTP, HTTP, SMTP, Telnet.

## Capa de Red
- Dirección IP
- Puerto TCP/UDP
- Controlador de Flujo
- Agregación de Paquetes
- Encapsulación y Desencapsulación

## Agregación de Paquetes
Permite enviar múltiples paquetes a través de una sola conexión física, reduciendo el número de conexiones necesarias.
- Ventajas: Reduce costos y mejora rendimiento.
- Desventajas: Incrementa latencia y requiere hardware adicional.

## Controlador de Flujo
Dispositivo o software que controla cómo viajan los paquetes en una red, permitiendo definir prioridades y limitar la velocidad de transmisión.

## DHCP (Protocolo de Configuración Dinámica de Host)
Asigna direcciones IP automáticamente a los hosts que se conectan a una red, utilizando mensajes broadcast.

## NAT (Traducción de Direcciones de Red)
Convierte una dirección IP pública en varias direcciones IP privadas, permitiendo el acceso a Internet sin asignar direcciones IP públicas.

## Firewall
Sistema o dispositivo de protección de red que filtra el tráfico entrante y saliente para proteger una red o dispositivo.

## VLAN (Red de Área Local Virtual)
Separa la red en subredes virtuales para mayor flexibilidad en la comunicación entre dispositivos.

## Subred
Sección de una red separada de otras por un dispositivo de acceso, definida utilizando una máscara de bits.

## Máscara de Bits
Valor numérico que indica qué parte de la dirección IP identifica la red y cuál identifica al host.

## EEEI (Interfuncionamiento Mejorado de Eficiencia Energética)
Capa de protocolo de red que proporciona energía eléctrica para ciertas funciones de red, como el apagado de dispositivos inactivos.

## Medios Inalámbricos
- WLAN (Red de Área Local Inalámbrica): WiFi, Bluetooth.
- Identificación por Radiofrecuencia (RFID): Utiliza ondas de radio para transmitir información.
- Bluetooth Mesh: Red de área personal basada en tecnología Bluetooth.
