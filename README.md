# Medidor de Core Web Vitals y Rendimiento Web

[![Medidor Core Web Vitals](https://img.shields.io/badge/TAVARDT-Core%20Web%20Vitals-5b3cf5.svg)](https://tools.tavardt.com/es/medidor-core-web-vitals/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Analisis de TTFB, compresion de recursos, scripts bloqueantes y optimizacion de estabilidad visual (CLS).

Desarrollado y mantenido por la division de rendimiento e ingenieria web de **TAVARDT**.

***

## Capacidades de Auditoria de Core Web Vitals

* **Medicion de Latencia y TTFB**: Evaluacion de tiempo de respuesta de servidor (Time to First Byte) y eficiencia de CDN.
* **Deteccion de Recursos Bloqueantes**: Localizacion de hojas de estilo y scripts sincronos en cabecera que retrasan el renderizado.
* **Control de Desplazamiento de Diseno (CLS)**: Revision de dimensiones fijas y carga diferida en imagenes.
* **Auditoria de Compresion**: Verificacion de codificacion Brotli o Gzip en transferencias HTTP.
* **Puntuacion de Rendimiento W3C**: Calificacion de 0 a 100 con pasos de optimizacion priorizados.

***

## Instalacion y Ejecucion

Requiere Python 3.8 o superior sin dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/core-web-vitals-tester-es.git
cd core-web-vitals-tester-es
python cwv_tester.py https://empresa.es
```

Para salida en formato JSON:

```bash
python cwv_tester.py https://empresa.es -json
```

***

## Diagnostico Completo en la Web

Para auditorias avanzadas de velocidad y respuesta:

* **Medidor de Core Web Vitals Oficial**
* **[Portal Corporativo TAVARDT](https://ag.tavardt.com/es/)**

***

## Consultoria en Optimizacion y Rendimiento Web

Para arquitectura de carga ultrarrapida bajo directrices de Estandares W3C y Directrices de Experiencia Web UE, contacte a **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/es/
* **Suite de Diagnósticos:** https://tools.tavardt.com/es/
* **Contacto Técnico:** https://ag.tavardt.com/es/contacto/

***

© 2026 TAVARDT. Todos los derechos reservados.
