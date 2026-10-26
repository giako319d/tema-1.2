# Tema 1.2 GIAN ZAPATA: Entorno portable de Dart y Flutter

## Características del Equipo
* **Procesador:** Intel(R) Core(TM) i5-10400 CPU @ 2.90GHz
* **Memoria RAM:** 16,0 GB (2400 MHz)[cite: 10]
* **Tarjeta Gráfica:** NVIDIA GeForce GTX 1650 (4 GB)
* **Almacenamiento:** 559 GB SSD
* **Sistema Operativo:** Windows 10/11 de 64 bits

## Entorno de Desarrollo
* **Versión de Flutter y Dart:** Flutter 3.x / Dart 3.x (obtenidas mediante `flutter --version`)
* **Ruta del Entorno:** `C:\dev\flutter\bin` (configurada en la variable de entorno PATH)
* **Destinos Disponibles:** Windows (desktop), Google Chrome (web) y Microsoft Edge (web)

## Problema Resuelto
Al ejecutar programas interactivos en Dart con `stdin.readLineSync()`, la consola interna de depuración de VS Code (*Debug Console*) no permitía ingresar texto por teclado. Se resolvió creando el archivo `.vscode/launch.json` con la propiedad `"console": "terminal"`, lo que redirige la ejecución a una terminal interactiva real.