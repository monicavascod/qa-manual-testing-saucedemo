# 🧪 Proyecto de Pruebas Manuales QA — SauceDemo

![QA Manual](https://img.shields.io/badge/QA-Pruebas%20Manuales-2F75B5)
![Casos de prueba](https://img.shields.io/badge/Casos%20de%20prueba-58-17324D)
![Ejecución](https://img.shields.io/badge/Ejecución-100%25-0F6B78)
![Estado](https://img.shields.io/badge/Estado-Aprobado-2E7D32)
![Bugs encontrados](https://img.shields.io/badge/Bugs%20encontrados-0-6B7280)

## 📌 Descripción del proyecto

Este repositorio contiene un proyecto de pruebas manuales funcionales sobre **SauceDemo**, una aplicación web que simula el flujo de compra de una tienda en línea.

El proyecto incluye el diseño, la documentación y la ejecución de casos de prueba para las principales funcionalidades del sistema, desde el inicio de sesión hasta la finalización de una compra.

El objetivo fue validar el comportamiento visible del sistema mediante pruebas estructuradas, trazables y basadas en riesgos.

---

## 🎯 Objetivos de prueba

* Validar las principales funcionalidades de SauceDemo.
* Verificar escenarios positivos, negativos y de validación.
* Comprobar campos obligatorios y restricciones de autenticación.
* Validar la información de productos y la navegación.
* Verificar el comportamiento del carrito de compras.
* Validar los cálculos de subtotal, impuestos y total.
* Comprobar el cierre de sesión y la protección de rutas.
* Mantener trazabilidad entre riesgos, módulos y casos de prueba.
* Documentar los resultados de ejecución.

---

## 🌐 Sistema bajo prueba

| Campo             | Detalle                      |
| ----------------- | ---------------------------- |
| Aplicación        | SauceDemo                    |
| URL               | https://www.saucedemo.com/   |
| Plataforma        | Web                          |
| Navegador         | Google Chrome                |
| Tipo de pruebas   | Pruebas manuales funcionales |
| Usuario principal | `standard_user`              |
| Entorno           | Entorno web público          |

---

## 🔍 Alcance

Se validaron los siguientes módulos:

| Módulo                 | Casos de prueba |
| ---------------------- | --------------: |
| Login                  |              11 |
| Productos              |              16 |
| Carrito                |               7 |
| Checkout               |               6 |
| Resumen de compra      |               8 |
| Finalización de compra |               3 |
| Menú lateral           |               5 |
| Logout                 |               2 |
| **Total**              |          **58** |

---

## 🧩 Cobertura de pruebas

El proyecto incluye validaciones sobre:

* Inicio de sesión con diferentes usuarios.
* Usuario bloqueado y credenciales inválidas.
* Campos obligatorios en el inicio de sesión.
* Información del catálogo de productos.
* Ordenamiento de productos.
* Navegación al detalle de producto.
* Agregar y retirar productos.
* Contador y persistencia del carrito.
* Checkout con datos válidos e incompletos.
* Resumen de compra.
* Información de pago y envío.
* Cálculos de subtotal, impuestos y total.
* Cancelación de la compra.
* Confirmación de la orden.
* Retorno al catálogo.
* Generación del comprobante PDF.
* Navegación desde el menú lateral.
* Restablecimiento del estado del sistema.
* Cierre de sesión.
* Acceso a rutas protegidas sin sesión activa.

---

## 🧪 Tipos de prueba aplicados

* Pruebas manuales funcionales.
* Pruebas positivas.
* Pruebas negativas.
* Validación de campos obligatorios.
* Pruebas de navegación.
* Pruebas de persistencia del carrito.
* Validación de cálculos.
* Pruebas de control de acceso.
* Pruebas basadas en riesgos.

---

## 📊 Resultados de ejecución

| Métrica                   | Resultado |
| ------------------------- | --------: |
| Casos de prueba diseñados |        58 |
| Casos ejecutados          |        58 |
| Casos Pass                |        58 |
| Casos Fail                |         0 |
| Casos Blocked             |         0 |
| Bugs encontrados          |         0 |
| Porcentaje de ejecución   |     100 % |
| Porcentaje de aprobación  |     100 % |

### Estado final

> ✅ Todos los casos de prueba planificados fueron ejecutados satisfactoriamente.

No se identificaron defectos dentro del alcance probado y bajo las condiciones utilizadas durante esta ejecución.

Este resultado no significa que el sistema esté completamente libre de defectos. Significa que no se reprodujeron errores mediante los 58 escenarios incluidos en el alcance actual.

---

## ⚠️ Estrategia basada en riesgos

La estrategia de pruebas priorizó riesgos relacionados con:

1. Fallos de autenticación para usuarios válidos.
2. Acceso no autorizado a rutas protegidas.
3. Información incorrecta de productos.
4. Pérdida, duplicación o eliminación incorrecta de productos.
5. Continuación del checkout con datos incompletos.
6. Cálculos incorrectos de subtotal, impuestos o total.
7. Finalización de compra sin confirmación.
8. Persistencia de sesión después del cierre de sesión.

Cada riesgo fue relacionado con uno o varios casos de prueba dentro de la matriz de trazabilidad.

---

## 📄 Documentación incluida

El archivo principal del proyecto contiene las siguientes pestañas:

### Casos de prueba

Incluye 58 escenarios documentados con:

* ID del caso.
* Módulo.
* Funcionalidad.
* Nombre del caso.
* Tipo de prueba.
* Precondiciones.
* Datos de prueba.
* Pasos.
* Resultado esperado.
* Prioridad.
* Estado de ejecución.
* Observaciones.

### Datos de prueba

Contiene información reutilizable como:

* Usuarios proporcionados por SauceDemo.
* Credenciales inválidas.
* Productos.
* Precios.
* Descripciones.
* Datos de checkout.
* Rutas principales del sistema.

### Reporte de bugs

Incluye una plantilla profesional para registrar defectos.

No se registraron bugs durante esta ejecución porque todos los casos finalizaron en estado Pass.

### Resumen de ejecución

Incluye:

* Métricas de ejecución.
* Estrategia de pruebas.
* Alcance.
* Criterios de entrada y salida.
* Suposiciones.
* Matriz de riesgos.
* Matriz de cobertura y trazabilidad.

---

## 📝 Consideraciones importantes

* Los casos fueron diseñados con base en el comportamiento visible del sistema.
* No se asumieron reglas de negocio no documentadas.
* El valor de Tax se validó según el valor observado en el sistema.
* El checkout con carrito vacío se documentó según el comportamiento actual.
* La generación del comprobante PDF requirió verificación manual.
* El proyecto se enfocó en pruebas funcionales manuales.

---

## 🛠️ Herramientas utilizadas

* Microsoft Excel.
* Google Chrome.
* GitHub.
* SauceDemo.

---

## 💡 Aprendizajes principales

Este proyecto fortaleció mi capacidad para:

* Diseñar casos de prueba claros y mantenibles.
* Redactar resultados esperados verificables.
* Aplicar escenarios positivos y negativos.
* Priorizar pruebas según el riesgo.
* Organizar datos de prueba reutilizables.
* Mantener trazabilidad entre riesgos y casos.
* Comunicar resultados de ejecución de forma transparente.
* Diferenciar entre comportamiento observado y defecto confirmado.

---

## 🚀 Próximas mejoras

Este proyecto podría ampliarse con:

* Pruebas en otros navegadores.
* Pruebas responsive.
* Validaciones de accesibilidad.
* Pruebas de API.
* Automatización de escenarios críticos.
* Nuevas sesiones de pruebas exploratorias.

---

## 👩‍💻 Autora

**Monica**
QA Manual Junior

Interesada en pruebas funcionales, diseño de casos de prueba, documentación y mejora de la calidad del software.

---

## 📎 Entregable principal

La documentación completa del proyecto se encuentra en el siguiente archivo:

[📥 Ver archivo de casos de prueba y resultados](./QA_Manual_Profesional_SauceDemo.xlsx)
