# Secret_Number_Game
# Juego del Número Secreto

Este proyecto es una implementación del "Juego del Número Secreto", un juego interactivo desarrollado en JavaScript y HTML donde los jugadores deben adivinar un número secreto generado aleatoriamente por el sistema.

## Descripción

El objetivo del juego es que el usuario adivine el número secreto que el sistema ha generado aleatoriamente entre 1 y 10. El jugador ingresa su suposición y el sistema proporciona pistas sobre si el número secreto es mayor o menor que el intento del jugador. El juego sigue hasta que el jugador adivina el número correcto, momento en el cual se muestra el número de intentos realizados. Luego, el jugador puede optar por iniciar un nuevo juego.

## Funcionalidades

- **Generación aleatoria del número secreto**.
- **Interfaz de usuario**: Una página web interactiva que permite a los usuarios ingresar sus intentos.
- **Validación y retroalimentación**: El sistema valida el número ingresado y proporciona retroalimentación indicando si el número secreto es mayor o menor.
- **Contador de intentos**: Cuenta y muestra el número de intentos realizados por el jugador.
- **Reinicio del juego**: Permite reiniciar el juego después de adivinar el número secreto.

## Tecnologías Utilizadas

- **HTML**: Para la estructura de la página.
- **CSS**: Para el diseño y estilo de la página (no incluido en los archivos proporcionados).
- **JavaScript**: Para la lógica del juego.

## Requisitos Previos

- Navegador web moderno.

## Instalación y Ejecución

1. Clona el repositorio:
    ```sh
    git clone https://github.com/tu-usuario/juego-numero-secreto.git
    cd juego-numero-secreto
    ```

2. Abre el archivo `index.html` en tu navegador web preferido.

## Uso

1. Al abrir la página, el juego se inicializará automáticamente y generará un número secreto entre 1 y 10.
2. Ingresa tu intento en el campo de texto y haz clic en el botón "Intentar".
3. El sistema te dirá si el número secreto es mayor o menor que tu intento.
4. Continúa intentando hasta que adivines el número secreto.
5. Una vez que adivines el número, se mostrará un mensaje con el número de intentos y el botón "Nuevo juego" se habilitará para reiniciar el juego.

## Estructura del Proyecto

- **index.html**: Contiene la estructura HTML del juego.
- **app.js**: Contiene la lógica del juego en JavaScript.

## Ejemplo de Uso

```plaintext
¡Bienvenido al Juego del Número Secreto!
Indica un número del 1 al 10.
Ingresa tu intento: 5
El número secreto es mayor.
Ingresa tu intento: 8
El número secreto es menor.
Ingresa tu intento: 7
¡Felicidades! ¡Has adivinado el número secreto en 3 intentos!
```

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios (`git commit -m 'Añadir nueva característica'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-caracteristica`).
5. Abre un pull request.

