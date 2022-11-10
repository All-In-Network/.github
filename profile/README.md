
# All In Network

## El Defi Prop-Trader Hub de Dotsama

All In Network no es un exchange (_orderbook_), somos una parachain que provee toda la infraestructura y herramientas necesarias para conectar nuevos traders con traders expertos de forma transparente y descentralizada.

Cuando hablamos de herramientas, nos referimos a que proveemos conexión a mentores con experiencia en los mercados crypto, un simulador de trading para evaluar a traders, y el tesoro de la parachain provee la financiación, luego de que cada trader apruebe la evaluación del simulador.

# Categorías a participar

- DeFi
- NFT

# Descripción del problema

- Una problemática que existe actualmente, es que cuando un nuevo usuario quiere ingresar al mundo del trading con criptomonedas, la primer plataforma de búsqueda de información es YouTube, y muchos de los canales que se encuentran, proveen información errada, educación de mala calidad y con poca transparencia.
- Otro problema es que el deseo de muchas personas, es generar buenos ingresos en el trading con criptomonedas, pero la mayoría no tiene el capital adecuado para obtener ganancias suficientemente rentables.

# Solución al problema

All In Network quiere facilitar el camino al trading profesional en tres pasos: **Mentoría**, **Financiamiento** y **Ganancias**.

## Mentoría

- Conéctate con un trader experto y recibe su enseñanza.
- Todos los mentores operan cuentas financiadas por el tesoro de All In Network, y las métricas de sus cuentas se guardan en la cadena de bloques.

## Financiamiento

Como trader necesitas capital adecuado para ganar como profesional, el tesoro de All In Network, te provee capital luego de haber completado una evaluación simulada con capital ficticio.

## Ganancias

- Llévate el 80% de todas tus ganancias como trader financiado.
- Como mentor te llevas 80% de las ganancias, y además puedes monetizar enseñando a cada trader que se suscriba a tu perfil.

# ¿Cómo utilizamos Substrate?

Somos una parachain que:

- Crea y registra en la blockchain, un perfil a través de un nickname y la compra de un NFT Soulbound para los nuevos traders.
- Para acceder a las características de All In Network, cada trader debe haber adquirido el NFT Soulbound del Marketplace.
- Una vez el trader apruebe la evaluación simulada, recibirá la financiación del tesoro de All In Network a través de _proxy accounts_.
- Las _proxy accounts_ son para que el usuario administre el capital operando futuros en los Exchanges (_orderbooks_) asociados del ecosistema Dotsama.

Te invitamos a revisar nuestra la versión reducida de nuestra arquitectura y la manera en la que usamos los pallets de Substrate en nuestra [documentación de Gitbook](https://docs.all-in.app/arquitectura).

# Video de presentación

- Para ver el pitch y la demostración del proyecto, te invitamos a visualizar el vídeo en [YouTube](https://youtu.be/4IOAsqRioRI).

# Repositorios de código vinculados al proyecto

### All In Network Parachain

Este repositorio almacena el código para compilar y ejecutar el nodo de la parachain que se utiliza para interactuar entre la interfaz de usuario de la plataforma con la blockchain de _All In Network_.

**Enlace:** [https://github.com/All-In-Network/all-in-parachain](https://github.com/All-In-Network/all-in-parachain)

### All In Network Websocket

Este repositorio almacena el código para recibir en tiempo real los datos del **BTC/USD** pair, a través del websocket de [Alpaca](https://alpaca.markets/), y transferir estos datos a la interfaz de usuario de All In Network para que se puedan utilizar en el _[Simulador](https://docs.all-in.app/empezar/simulador)_ y en el _[Mercado real](https://docs.all-in.app/empezar/mercado)_.

**Enlace:** [https://github.com/All-In-Network/all-in-api](https://github.com/All-In-Network/all-in-api)

### All In Network Frontend

Este repositorio almacena el código de la interfaz de usuario de la plataforma de _All In Network_.

**Enlace:** [https://github.com/All-In-Network/all-in-frontend](https://github.com/All-In-Network/all-in-frontend)

### All In Network Reverse Proxy

Este repositorio almacena el código que permite utilizar múltiples subdominios para desplegar muchas aplicaciones en una sola instancia Linux.

Créditos a [Evert Ramos](https://github.com/evertramos), por proveer un [repositorio de código](https://github.com/evertramos/nginx-proxy-automation) público, que facilita la configuración de Reverse Proxy con Nginx, Docker y Let's Encrypt para múltiples sitios.

**Enlace:** [https://github.com/All-In-Network/all-in-app](https://github.com/All-In-Network/all-in-app)

# Enlace de la aplicación del proyecto

- Te invitamos a visitar la aplicación de All In Network, en entorno productivo: [https://all-in.app](https://all-in.app)
- También puedes explorar el RPC de nuestra blockchain a través de **Polkadot.js**: [wss://rpc.all-in.app](https://polkadot.js.org/apps/?rpc=wss://rpc.all-in.app/explorer#/explorer)

# Documentación

- Para ver la documentación completa del proyecto, te invitamos a visitar nuestro [Gitbook](https://docs.all-in.app), donde te explicamos todos los detalles del MVP de All In Network.

# Tecnologías
- Para ver la documentación de las tecnologías que utiliza el proyecto, te invitamos a visitar nuestra [documentación en Gitbook](https://docs.all-in.app/stack).

# Equipo

- Cristian Gómez <[felipeg1702@hotmail.com](mailto:felipeg1702@hotmail.com)> / Rust/Substrate Developer ([GitHub](https://github.com/0xti4n)) ([Twitter](https://twitter.com/xt1a_n))
- Evert Escalante <[evertescalante@gmail.com](mailto:evertescalante@gmail.com)> / Full-Stack Software Engineer ([GitHub](https://github.com/Evertcolombia)) ([Twitter](https://twitter.com/evert_escalante))
- Santiago Londoño <[monoprosito@gmail.com](mailto:monoprosito@gmail.com)> / Full-Stack Software Engineer ([GitHub](https://github.com/monoprosito)) ([Twitter](https://twitter.com/msarboledal))
- Oscar Riaño <[oscarnetworkingpro@gmail.com](mailto:oscarnetworkingpro@gmail.com)> / Full-Stack Software Engineer ([GitHub](https://github.com/OscarDRT)) ([Twitter](https://twitter.com/Oscar__RT))
