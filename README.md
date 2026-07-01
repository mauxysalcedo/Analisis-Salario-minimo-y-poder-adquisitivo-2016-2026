## Poder Adquisitivo del Salario Mínimo en Colombia (2016–2025)

## ¿El colombiano promedio vive o sobrevive — y le alcanza para invertir en su futuro?

Elaborado por: Mauxy Salcedo
Año: 2026
Herramientas: Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook
Fuentes de datos: DANE · Banco de la República · Ministerio del Trabajo · SNIES


Cada enero, Colombia recibe la noticia del nuevo salario mínimo con un aumento en papel — pero con dudas reales sobre si ese aumento de verdad alcanza. Este proyecto responde esa pregunta con datos: ¿ha mejorado el poder adquisitivo del salario mínimo entre 2016 y 2025, y le queda margen al colombiano promedio para invertir en su educación superior?

## Metodología


Deflactación del salario: salario nominal ÷ IPC de diciembre de cada año (÷100), serie de empalme del DANE (base dic-2018 = 100)
Excedente: (Salario nominal + Auxilio de transporte) − Línea de pobreza nacional
Comparación con matrícula: excedente mensual × 6 (semestre), comparado contra el costo de matrícula universitaria


Período: 2016–2025 · Población de referencia: trabajador formal que gana exactamente el SMMLV

## Las tres capas del análisis

Capa 1 — Salario real. El salario nominal subió 106%, pero descontando inflación, el salario real solo creció 26%. Respuesta: sí mejoró, pero mucho menos de lo que parece.

<img width="1767" height="716" alt="grafica_capa1_salario_real" src="https://github.com/user-attachments/assets/93b4879d-e38f-44e0-bbb3-964f30f34ac4" />

 Capa 2 — ¿Vivir o sobrevivir? El ingreso se mantuvo sobre la línea de pobreza, pero el excedente es frágil — y se calcula para una sola persona, cuando el hogar promedio colombiano tiene 2,82 integrantes (DANE, 2025). Respuesta: técnicamente por encima de la pobreza; en la práctica familiar, el colchón es demasiado estrecho.

<img width="1617" height="716" alt="grafica_capa2_excedente" src="https://github.com/user-attachments/assets/f9e2b98e-eeef-4ef0-9659-26cb83853ee1" />

Capa 3 — ¿Invertir en el futuro? En ningún año del período el excedente semestral alcanzó para cubrir una matrícula privada (~$8.500.000). Respuesta: no alcanza. La universidad pública gratuita no es una preferencia — es la única puerta abierta.

<img width="1908" height="866" alt="grafica_capa3_matricula" src="https://github.com/user-attachments/assets/aba6ab38-e6bc-4752-a6f1-2e75121dc026" />

# El mejor escenario posible

Este análisis se hizo sobre alguien con empleo formal, ganando exactamente el salario mínimo, sin dependientes. Según el DANE, esa persona es apenas el 10,1% de los trabajadores colombianos. El 48,9% de los ocupados gana menos del salario mínimo, y el desempleo juvenil llega a 16–17%. Es decir: este proyecto midió el mejor escenario posible — y si ahí el margen ya es estrecho, la realidad de casi la mitad del país es aún más difícil.

# Conclusión

El poder adquisitivo del salario mínimo en Colombia mejoró en la última década, pero de forma frágil y muy por debajo de lo que sugiere el titular de cada enero: un aumento nominal de 106% se traduce en apenas 26% de poder de compra real. En este contexto, la educación superior deja de ser una aspiración personal para convertirse en la variable que decide si alguien puede romper el ciclo en el que nació — y fortalecer el acceso a la universidad pública es, para millones de colombianos, la diferencia entre quedarse donde están o construir algo distinto.


Fuentes: DANE (IPC, líneas de pobreza, mercado laboral, informalidad), Banrep / Ministerio del Trabajo (SMMLV y auxilio de transporte), SNIES / Laboratorio de Economía de la Educación – Universidad Javeriana, Ministerio de Educación Nacional.

Elaborado por: Mauxy Salcedo — Proyecto de portafolio, 2026.


Salario real — cuánto vale hoy el salario mínimo después de descontar la inflación, comparado con 2016.
Vivir o sobrevivir — en qué se está gastando ese salario realmente, y cuánto margen queda después de cubrir lo esencial.
Invertir en el futuro — si ese margen alcanza para educación superior, y qué papel juega la educación pública en esa respuesta.
