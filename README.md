# Signal Integrity Lab — Beyond the Circuit

Laboratorio didáctico interactivo para visualizar la reflexión de ondas en una línea de transmisión.


## Contenido

- Ajuste de impedancia característica, de carga y de fuente.
- Terminaciones adaptada, abierta y en cortocircuito; fuente adaptada, resistiva o driver ideal.
- Coeficientes de reflexión de tensión en carga (ΓL) y en fuente (ΓS).
- Porcentaje de potencia reflejada para una línea ideal sin pérdidas y carga resistiva.
- Tiempo de propagación de ida estimado a partir de longitud y velocidad relativa.
- Excitación en escalón o pulso con tiempo de subida finito (10–90 %).
- Perfil de tensión V(x, t) a lo largo de la pista, separado en onda incidente, reflejada y total.
- Respuesta temporal en ambos extremos con múltiples rebotes y cursor de tiempo sincronizado.

## Alcance del modelo

Modelo ideal de línea de transmisión sin pérdidas, con carga y fuente resistivas. La tensión se obtiene por superposición de ondas viajeras: cada viaje de ida y vuelta se multiplica por ΓL·ΓS, de modo que se representan rebotes múltiples (escalones o ringing). El flanco de excitación es un coseno alzado con el tiempo de subida 10–90 % configurado. No simula pérdidas dieléctricas/conductoras, dispersión, cargas reactivas, múltiples discontinuidades ni una solución electromagnética 2D/3D. Para análisis de integridad de señal de una PCB real se requieren geometría del stack-up, permitividad, espesor, ancho de pista, planos de referencia, modelo del driver y del receptor.
