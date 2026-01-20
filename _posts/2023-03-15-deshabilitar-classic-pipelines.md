---
layout: post
title: "Deshabilitar classic pipelines en Azure DevOps"
date: 2023-03-15
featured: false
category: "Azure DevOps"
author: "Elena Guzman"
featured_image: "https://images.unsplash.com/photo-1618401471353-b98afee0b2eb?w=1200"
excerpt: "Las classic pipelines en Azure DevOps están siendo reemplazadas por YAML pipelines. Aprende cómo hacer la transición."
---

Azure DevOps ofrece dos formas de definir pipelines: las classic pipelines con interfaz gráfica y las YAML pipelines como código. La tendencia actual favorece fuertemente las YAML pipelines por sus ventajas en versionado y reutilización.

## ¿Por qué migrar de Classic a YAML?

Las YAML pipelines ofrecen beneficios significativos:
- **Infraestructura como código**: Tu pipeline vive en el repositorio
- **Control de versiones**: Cambios rastreables con Git
- **Reutilización**: Templates y bibliotecas compartibles
- **Revisión**: Pull requests para cambios en pipelines

## Proceso de deshabilitación

Para deshabilitar las classic pipelines en tu organización:
1. Revisa todas las pipelines existentes
2. Planifica la migración a YAML
3. Configura políticas de organización
4. Deshabilita la creación de nuevas classic pipelines

## Estrategia de migración

Un enfoque gradual funciona mejor:
- Comienza con pipelines simples
- Documenta patrones comunes
- Crea templates reutilizables
- Capacita al equipo en YAML
- Migra las pipelines críticas al final

## Beneficios a largo plazo

La adopción de YAML pipelines resulta en:
- Mayor consistencia entre proyectos
- Mejor colaboración del equipo
- Reducción de errores manuales
- Facilita auditorías y compliance

El cambio puede parecer disruptivo inicialmente, pero los beneficios justifican ampliamente la inversión.
