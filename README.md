# Talller-Cliente-Servidor-UDP


## Descripción
En este taller se simulará el envío y recepción de notificaciones en C# usando el protocolo UDP. Incluye un cliente que envia mensajes y un servidor que los recibe.

## Componentes
- ServidorUDP.cs: Recibe los mensajes de clientes y los imprime con hora y dirección.
- ClienteUDP.cs: Se encargará de enviar 5 mensajes al servidor con 2 segundos de espera entre cada uno. Uno de los clientes puede finalizar el servidor con "FIN".

## Clases
- Protocolo UDP 
- `UdpClient` para envío/recepción de los mensajes

## Ejecución
1. Compilar ambos archivos por separado.
2. Ejecutar el servidor (`Taller 5 Servidor.`).
3. Ejecutar múltiples clientes (`ClienteUDP.exe`) desde distintas consolas.
4. Uno de los clientes puede enviar el mensaje "FIN" para cerrar el servidor.

Capturas del funcionamiento:


<img width="978" height="504" alt="image" src="https://github.com/user-attachments/assets/b06ba077-d4f0-47e8-b18f-3773e57850a0" />


<img width="978" height="504" alt="Captura de pantalla 2025-07-15 172119" src="https://github.com/user-attachments/assets/1a8b0ff6-f2b1-488c-975d-aa92dd2ee5b6" />
