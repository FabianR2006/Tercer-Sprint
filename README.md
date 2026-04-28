
#  Estado Actual del Proyecto

Actualmente, el sistema **no cuenta con una base de datos implementada**, por lo que:

* Se incluyen **productos precargados** dentro del sistema para demostrar su funcionamiento.
* Estos productos permiten visualizar correctamente todas las funcionalidades principales.

---

#  Funcionalidades Disponibles

* Visualización de productos precargados.
* Análisis automático de precios comparando:

  * Precio del usuario
  * Precio del mercado
* Indicadores visuales:

  * Precio alto
  * Precio óptimo
  * Oportunidad de mejora
* Vista de detalle por producto:

  * Información completa
  * Diferencia porcentual
  * Recomendaciones

---

## 📂 Carga de Inventario (CSV)

El sistema permite subir un archivo **.csv** con productos para demostrar la lógica principal del sistema.

### ✔ Instrucciones:

1. Hacer clic en **"Sube tu inventario"**
2. Seleccionar el archivo CSV proporcionado
3. El sistema:

   * Carga los productos
   * Genera precios de mercado simulados
   * Aplica automáticamente el análisis de precios

---

# 📄 Estructura del CSV

El archivo debe tener el siguiente formato:

```
name,cat,myPrice
Producto 1,Categoria,10000
Producto 2,Categoria,20000
```

---

## Lógica Implementada

El sistema ya cuenta con la lógica principal:

* Cálculo de diferencia porcentual
* Clasificación del estado del producto
* Generación de recomendaciones
* Actualización dinámica de precios

---

## Trabajo Futuro

* Integración con base de datos
* Conexión con APIs de mercado en tiempo real
* Persistencia de inventarios por usuario
* Mejora en recomendaciones inteligentes

---

##  Conclusión

Aunque el sistema actualmente funciona con datos simulados, **la lógica principal del análisis de precios ya está completamente implementada y funcional**, permitiendo validar el comportamiento esperado de la aplicación.
