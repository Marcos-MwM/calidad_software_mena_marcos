# Calidad de Software

Este repositorio está dedicado a la materia de Calidad de Software. Su objetivo es comprender y aplicar buenas prácticas para garantizar que una aplicación sea confiable, mantenible y fácil de validar.

## Objetivo del proyecto

En esta materia se trabajan conceptos como:

- Calidad del software
- Pruebas de software
- Revisión de código
- Automatización de pruebas
- Métricas y calidad del producto
- Buenas prácticas de desarrollo

## Estructura general

El repositorio puede contener:

- Código fuente de la aplicación
- Pruebas unitarias
- Pruebas de integración
- Pruebas end-to-end (E2E)
- Documentación técnica

## Pruebas unitarias

Las pruebas unitarias validan que cada parte del sistema funcione de forma aislada. Por ejemplo, una función, un servicio o un componente puede probarse individualmente para verificar su comportamiento esperado.

Ejemplo de enfoque:

- Validar entradas y salidas
- Comprobar condiciones lógicas
- Cubrir casos normales y de error
- Verificar que cada módulo funcione de manera independiente

En proyectos con JavaScript o TypeScript, normalmente se usan herramientas como Jest o Vitest para este tipo de pruebas.

## Pruebas E2E

Las pruebas end-to-end (E2E) validan el comportamiento del sistema completo como lo haría un usuario real. Se prueban flujos completos, como:

- Inicio de sesión
- Registro de usuario
- Navegación entre páginas
- Compra o envío de datos
- Validación del flujo completo de una funcionalidad

Estas pruebas ayudan a detectar errores que no aparecen al validar módulos por separado. Herramientas comunes son Playwright, Cypress o Selenium.

## Diferencia entre pruebas unitarias y E2E

- Pruebas unitarias: validan unidades pequeñas y aisladas.
- Pruebas E2E: validan escenarios completos de usuario.
- Ambas son importantes: las unitarias detectan errores rápidos y específicos, mientras que las E2E aseguran la experiencia global del sistema.

## Recomendaciones

- Escribir pruebas antes o junto con la implementación.
- Mantener las pruebas claras y legibles.
- Cubrir casos positivos y negativos.
- Automatizar la ejecución en integración continua.
- Revisar siempre que los resultados de las pruebas sean consistentes.

## Ejemplo de comandos

En un proyecto Node.js con pruebas automatizadas, normalmente se usan comandos similares a estos:

```bash
npm install
npm run test
npm run test:e2e
```

Estos comandos representan, respectivamente:

- instalación de dependencias
- ejecución de pruebas unitarias
- ejecución de pruebas end-to-end

## Conclusión

La calidad de software no depende solo de escribir código funcional, sino también de validarlo de manera continua. Las pruebas unitarias y E2E son herramientas clave para asegurar que el software cumpla con los requisitos y funcione correctamente en la práctica.
