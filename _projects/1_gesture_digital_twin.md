---
page_id: gesture-digital-twin
layout: page
title: Gesture-Driven Robotic Digital Twin (TFG)
description: Prototipo ligero de gemelo digital basado en gestos para la validación de la interacción humano-robot.
img: assets/img/publication_preview/panda.png # Puedes cambiar la ruta a una captura de tu simulador
importance: 1
category: work
related_publications: false
github: https://github.com/jordialt/gesture-digital-twin
---

Sistema de interacción humano-robot (HRI) en tiempo real sin contacto ni sensores de profundidad, ejecutado íntegramente sobre CPU en hardware de gama baja.

### Aspectos técnicos destacados
* **Percepción en tiempo real:** Reconocimiento de gestos mediante **MediaPipe Tasks** con captura por cámara RGB estándar.
* **Filtrado por debounce:** Capa de estabilización temporal que exige 5 fotogramas consecutivos y confianza $\ge 0{,}6$, suprimiendo disparos erráticos.
* **Control cinemático dual:** Enrutador de modos (`ModeController`) que multiplexa el control hacia 4 dimensiones espaciales (planos X-Z e Y-Yaw).
* **Gemelo Digital 3D:** Brazo **Franka Panda (7-DOF)** en **PyBullet** gobernado por cinemática inversa numérica en un único bucle continuo.
* **Métricas validadas:** 24.300+ fotogramas registrados en CSV multihilo con **23,79 FPS medios** y **17,47 ms de latencia**.
