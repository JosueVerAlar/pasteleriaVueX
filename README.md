# vuex-pasteleria
Este proyecto fue elaborado por Josué Vergara Alarcón, para más información contactar a [Josue Vergara](https://github.com/JosueVerAlar)

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## About this project
Este proyecto se ha realizado con la finalidad de tener un primer acercamiento al uso de Vue y VueX para el desarrollo de aplicaciones web. Por su parte, se trabajó sobre el proyecto de pastelería [Pasteleria Delicia](https://github.com/JosueVerAlar/pasteleriaDelicia) elaborado por Josué Vergara buscando integrar las diferentes funciones del Index.js sobre los formularios, solicitudes y otros elementos.

Con mayor precisión se desarrollaron las siguientes cosas;
+ Página de cliente de pastelería POR COMPONENTES
++ Componente con información de la pastelería Dirección, Teléfono y horarios de atención
++ Componente para ver los diferentes sabores de pasteles, así como los precios de cada uno
++ Componente para ver los diferentes adornos con los que se puede decorar el pastel y los precios de cada uno
++ Componente para combinar sabores dependiendo de sus preferencias
++ Componente para combinar adornos dependiendo de sus preferencias
++ Componente de formulario debe de contener los datos de contacto del cliente que son Nombre, Teléfono, Correo Electrónico, Descripción general del pastel y    la selección de sabores y adornos

+ Página de pastelero POR COMPONENTES
++ Componente de información de la cantidad de sabores que le quedan para hacer los pasteles
++ Componente de información de la cantidad de adornos que le quedan para hacer los pasteles
++ Componente donde aparezcan los pedidos que se han realizado con los datos del formulario

Algunas de las herramientas que no pudieron desarrollarse debido a la falta de tiempo fueron las siguientes;
+ Uso de rutas para poder acceder a la página de cliente y de pastelero (router de Vue)
+ La información de sabores, adornos, cantidades y precio debe de estar en el estado con Vuex o Vite y se debe modificar ahí para mostrarse en los   componentes.

Sin embargo, se planea que próximamente se puedan resolver estos pendientes para completar el funcionamiento de la página.

Sobre la página del pastelero es necesario aclarar que existe un desfase en la serie de datos con respecto a las tablas, esto es debido a un problema con el uso de Display: Flex; que espero pronto poder corregirlo.
