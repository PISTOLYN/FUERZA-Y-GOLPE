# TEST YOUR MIGHT — Desafío de Fuerza

Prototipo jugable para dos jugadores. Abrir `index.html` en Chrome o Edge.

## Controles iniciales
- Jugador 1 (azul): A
- Jugador 2 (rojo): L
- También admite controles tipo gamepad mediante Gamepad API (botones 1 y 2).

La mayoría de las botoneras arcade USB con encoder se presentan al sistema como teclado y funcionan asignando sus teclas en Configuración. Los mandos que se presentan como gamepad se pueden utilizar con la opción correspondiente.

## Cómo jugar
1. Pulsa NUEVA PARTIDA.
2. Durante la cuenta regresiva y el tiempo de competencia, pulsa repetidamente tu tecla o botón.
3. Cada pulsación llena el medidor según el incremento configurado.
4. El primero en llegar al 100% rompe la tabla y gana.
5. Si se termina el tiempo antes de alcanzar el 100%, el personaje realiza el golpe fallido con la mano roja y la tabla no se rompe.

## Configuración
El engrane permite cambiar nombres, tiempo, incremento por pulsación, teclas, volumen, modo de entrada y cargar archivos MP3/WAV para música, golpe/tabla, victoria y fallo. Los ajustes principales se guardan en el navegador.

## Importante sobre el instalador
Esta entrega es un prototipo web funcional. Para generar un instalador Windows `.EXE` se debe empaquetar con Electron y compilar en un entorno Windows o CI de GitHub Actions. La comunicación Arduino por puerto COM requiere integrar Web Serial o un módulo serial nativo y definir el protocolo del firmware. No se afirma que el instalador o Arduino ya estén implementados en esta versión.

## Prueba rápida
Abre `index.html`, pulsa `NUEVA PARTIDA`, luego usa A y L. Puedes cambiar los controles y el tiempo desde CONFIGURACIÓN.
