# Hazlite

Hazlite es un agente de finanzas personales que corre en Cowork. Toma estados de cuenta bancarios, los normaliza en un único ledger CSV, categoriza el gasto y genera un análisis mensual de salud financiera.

La arquitectura es modular: cada banco tiene su propio parser, implementado como una skill independiente. Agregar soporte para un banco nuevo implica escribir una skill nueva, sin modificar el resto del sistema. El objetivo de la v1.0 es cubrir la mayor cantidad posible de bancos de plaza en Uruguay.

Este repositorio no contiene datos reales. Los estados de cuenta, el ledger, la configuración y los reportes viven en carpetas locales excluidas del control de versiones. Los ejemplos en `examples/` son anonimizados.
