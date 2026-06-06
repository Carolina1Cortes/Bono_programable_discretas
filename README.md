# Bono de Programación — Problemas Generales de Conteo
**Matemáticas Discretas I | Universidad Nacional de Colombia**  
**Estudiante:** Linda Carolina Cortés Bustos  
**Docente:** Jhoan Sebastian Tenjo García  

---

## Descripción
Este repositorio contiene la solución a dos problemas de combinatoria 
como herramientas generales de conteo. Cada programa recibe parámetros 
configurables por el usuario y calcula la respuesta para cualquier 
entrada válida.

## Problemas resueltos
- **Problema 2:** Calculadora general de combinaciones
- **Problema 9:** Coeficientes multinomiales y palabras con letras repetidas

## Cómo ejecutar
1. Abrir el archivo `Bono programable - Linda Cortes.ipynb` en Google Colab.
2. Ejecutar las celdas en orden de arriba hacia abajo.
3. Ingresar los valores solicitados cuando el programa lo pida.

## Ejemplos
```python
combinaciones(20, 4)              # 4845
coeficiente_multinomial("BANANA") # 60
triangulo_de_pascal(5)            # Triángulo hasta la fila 5
listar_palabras("ANA")            # {'ANA', 'NAA', 'AAN'}
```

## Requisitos
No requiere instalación de librerías externas.  
Solo se usa `collections.Counter`, incluida en Python por defecto.
