# Tarjeta Interactiva de Jugador de Fútbol

Este proyecto muestra una tarjeta interactiva de un jugador de fútbol que se voltea para mostrar más detalles al hacer clic en los botones. A continuación, encontrarás un video demostrativo y algunos fragmentos de código que explican cómo se implementó la funcionalidad.

## Video Demostrativo

[Inserta aquí el enlace al video]

## Código

### 1. Obteniendo Elementos

En este bloque de código obtenemos las referencias a las caras de la tarjeta para poder manipularlas más tarde.

```javascript
const frontal = document.querySelector('.frontal');
const posterior = document.querySelector('.posterior');
```

### 2. Botón ver detalles

```javascript
verDetallesButton.addEventListener('click', () => {
    frontal.style.transform = 'rotateY(180deg)';
    posterior.style.transform = 'rotateY(0deg)';
});
```

### 3. Botón ver detalles

```javascript
volverButton.addEventListener('click', () => {
    frontal.style.transform = 'rotateY(0deg)';
    posterior.style.transform = 'rotateY(180deg)'; 
});
```
