# Aplicación de Números Primos con Flutter

## Descripción

Esta aplicación fue desarrollada utilizando Flutter y permite mostrar números primos de forma secuencial mediante un contador interactivo.

Cada vez que el usuario presiona el botón de incremento, la aplicación calcula y muestra el siguiente número primo.

## Características

* Interfaz desarrollada con Flutter.
* Generación de números primos.
* Actualización dinámica de la interfaz mediante `setState()`.
* Compatible con Flutter Web.

## Captura de Pantalla



![Captura de la aplicación](images/captura-app.png)

##Captura del código implementado

![Captura de la aplicación](images/captura-app.png)

## Tecnologías Utilizadas

* Flutter
* Dart
* Material Design

## Estructura del Proyecto

```text
lib/
 └── main.dart

web/
 ├── index.html
 └── manifest.json
```

## Ejecución del Proyecto

1. Clonar el repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

2. Acceder al directorio:

```bash
cd nombre-del-proyecto
```

3. Instalar dependencias:

```bash
flutter pub get
```

4. Ejecutar en navegador:

```bash
flutter run -d chrome
```

## Funcionamiento

La aplicación utiliza una función que determina si un número es primo verificando que no tenga divisores distintos de 1 y de sí mismo.

Cuando el usuario presiona el botón:

1. Se incrementa el contador.
2. Se verifica si el número es primo.
3. Si no es primo, se continúa incrementando.
4. Se muestra el siguiente número primo encontrado.

## Autor

**Gabriel**

Proyecto desarrollado como práctica de Flutter y Dart.
