# M09 - UF3: Proyectos de Desarrollo de Aplicaciones con Unity

Este repositorio contiene las actividades prácticas del módulo **M09 - UF3** del curso, enfocadas en el desarrollo de aplicaciones interactivas utilizando Unity y otras tecnologías complementarias. A continuación, se describen los cuatro proyectos realizados: **B01_NodeJs**, **B1_Chat_UDP**, **B2_WebSocket** y **B3_Salas_multimedia**. Cada proyecto aborda diferentes aspectos de la programación de aplicaciones en red y multimedia.

---

## Tabla de Contenidos

- [B01_NodeJs](#b01_nodejs)  
- [B1_Chat_UDP](#b1_chat_udp)  
- [B2_WebSocket](#b2_websocket)  
- [B3_Salas_multimedia](#b3_salas_multimedia)  
- [Requisitos](#requisitos)  
- [Instrucciones de Uso](#instrucciones-de-uso)  
- [Autor](#autor)

---

## B01_NodeJs

### Descripción

Este proyecto implementa un servidor web básico utilizando Node.js, que sirve como backend para una aplicación Unity. El servidor permite gestionar solicitudes HTTP y enviar respuestas a clientes, demostrando la integración entre Unity y un entorno de servidor.

### Funcionamiento

- **Servidor Node.js:** Se configura un servidor HTTP utilizando el módulo `http` de Node.js.  
- **Endpoints:** Proporciona rutas básicas (por ejemplo, `/` para una página de bienvenida o `/data` para enviar datos JSON).  
- **Integración con Unity:** Unity realiza solicitudes HTTP (usando `UnityWebRequest`) para interactuar con el servidor.  
- **Entrega:** Incluye el código fuente del servidor y un PDF con capturas, explicación y enlace al repositorio.

### Tecnologías

- **Node.js:** Backend del servidor.  
- **Unity:** Cliente que consume los servicios del servidor.  
- **JavaScript:** Lógica del servidor.

---

## B1_Chat_UDP

### Descripción

Este proyecto desarrolla un sistema de chat en red utilizando el protocolo UDP para la comunicación en tiempo real entre múltiples clientes, implementado en Unity.

### Funcionamiento

- **Arquitectura cliente-servidor:** Un servidor Unity gestiona los mensajes, mientras que los clientes (instancias de Unity) envían y reciben mensajes.  
- **Protocolo UDP:** Los mensajes se envían como datagramas, permitiendo comunicación rápida pero sin garantía de entrega.  
- **Interfaz:** Una interfaz en Unity permite a los usuarios escribir y ver mensajes en un chat.  
- **Entrega:** Incluye scripts de Unity, un ejecutable (opcional) y un PDF con documentación.

### Tecnologías

- **Unity (C#):** Desarrollo del cliente y servidor.  
- **UDP Sockets:** Comunicación en red mediante `System.Net.Sockets`.  
- **Canvas UI:** Interfaz gráfica del chat.

---

## B2_WebSocket

### Descripción

Este proyecto implementa un sistema de comunicación en tiempo real utilizando WebSockets, permitiendo una interacción bidireccional entre un servidor y clientes Unity.

### Funcionamiento

- **Servidor WebSocket:** Configurado con una biblioteca como `ws` en Node.js o similar, gestiona conexiones persistentes.  
- **Clientes Unity:** Se conectan al servidor mediante una biblioteca WebSocket compatible con Unity (por ejemplo, `NativeWebSocket`).  
- **Funcionalidad:** Permite enviar y recibir mensajes en tiempo real, como un chat o actualizaciones de estado.  
- **Entrega:** Incluye el código del servidor, scripts de Unity y un PDF con capturas y explicación.

### Tecnologías

- **Node.js (opcional):** Servidor WebSocket.  
- **Unity (C#):** Cliente con soporte para WebSockets.  
- **WebSocket Protocol:** Comunicación bidireccional.

---

## B3_Salas_multimedia

### Descripción

Este proyecto crea una aplicación multimedia en Unity que simula la gestión de salas con pantallas virtuales, donde los usuarios pueden reproducir y controlar contenido audiovisual.

### Funcionamiento

- **Escena 3D:** Contiene al menos dos pantallas (objetos 3D como planos) que muestran vídeos o imágenes.  
- **Menú interactivo:** Implementado con Canvas UI, incluye botones para:  
  - Seleccionar la pantalla activa.  
  - Reproducir, pausar o detener contenido (3 vídeos o imágenes).  
  - Cambiar entre pantallas.  
  - Salir de la aplicación.  
- **Reproducción multimedia:** Usa el componente `VideoPlayer` de Unity y `RenderTexture` para mostrar contenido en las pantallas.  
- **Entrega:** Incluye el proyecto Unity, un repositorio GitHub y un PDF con portada, explicación, capturas y enlace.

### Tecnologías

- **Unity (C#):** Desarrollo de la escena y lógica.  
- **VideoPlayer:** Reproducción de vídeos.  
- **Canvas UI:** Interfaz de usuario.  
- **RenderTexture:** Visualización de contenido en objetos 3D.

---

## Requisitos

- **Unity:** Versión 2021.3 LTS o superior (compatible con todos los proyectos).  
- **Node.js:** Requerido para B01_NodeJs y B2_WebSocket (versión 16 o superior recomendada).  
- **Git:** Para clonar y gestionar el repositorio.  
- **Recursos multimedia:** Vídeos (MP4) o imágenes (PNG/JPG) para B3_Salas_multimedia (proporcionados o de uso libre).  
- **Conexión a internet:** Necesaria para pruebas de red en B01, B1 y B2.

---

Nombre: Alessandra Rivasplata
Curso: M09 - UF3
Fecha: Mayo 2025



B1_Chat_UDP
B2_WebSocket
B3_Salas_multimedia

