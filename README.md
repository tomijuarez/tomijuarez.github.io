# NaiveBayes
El presente es un proyecto final de la cátedra 'Investigación Operativa' realizado por los alumnos  Tomás Juárez, Mariano Fernández Cocirio, y los progesores Mg. Daniel Xodo y Mg. Moisés Bueno.

Con el desarrollo tecnológico de los últimos años, muchas empresas han optado por introducir sus sistemas de comercio electrónico. Éstas realizan esfuerzos muy grandes por mantener los sitemas de e-commerce lo más intuitivos posibles y fáciles de navegar, de forma tal que los usuarios se sientan cómodos puesto que son potenciales compradores. Sin embargo, muchas personas aún desconfían de estos sistemas dado que no se realiza una compra directa y personal -como en los últimos cientos de años-. Grandes empresas como e-bay y MercadoLibre han utilizado muchas técnicas para solucionar este inconveniente, como la reintegración del dinero si ocurren problemas en la transacción en algunos productos seleccionados. Aún así, es menester otorgar una visión más amplia al cliente haciendo que la compra sea lo más transparente posible. Una forma de avanzar con esta política de claridad consiste en etiquetar a todos los usuarios en una escala de clasificación, partiendo de "pésimo" a "excelente", para que el usuario sepa a priori a qué clase de usuario está solicitando la compra de un producto. Nótese que con la implementación de un clasificador ya no importa quién es el usuario sino cómo es, implicando que el usuario ya no se preocupe por la identidad de los vendedores en este tipo de sistemas.

Un usuario podría ver el historial de un vendedor y realizar una estimación de la calidad de ventas e inferir (o suponer) cómo saldrá su compra. Esto es trivial si el usuario tuvo 100 ventas y 99 votos negativos (ya sea por incumplimiento de los términos acordados con el comprador, por no entregar el producto, por entregarlo roto, por malos tratos, etcétera). Ahora bien, si el usuario tiene muchos votos positivos, pero no todos, sería razonable pensar que faltan más parámetros para determinar si es un buen vendedor o no. Otros parámetros serán la cantidad de tiempo que el usuario vende productos en la plataforma electrónica y el tiempo medio que se toma en responder mensajes a los vendedores. Al introducir estas variables vemos que los lapsos de tiempo se pueden partir en rangos (responde entre 4 y 7 días, hace más de 28 meses que es vendedor), con lo cual el cálculo de la calidad del vendedor ya no resulta sencillo (al menos no mentalmente), con lo cual se debe introducir un clasificador. Cabe destacar que en este tipo de plataformas, es necesario dar facilidades al usuario, con lo cual no es una buena opción darle la responsabilidad de calcular estos parámetros en cada compra. Ese es el objetivo de un clasificador de usuarios en sistemas de e-commerce; ayudar a un comprador a mejorar su calidad y a las empresas y vendedores a obtener una mayor ganancia, al mismo tiempo que se mantiene libre de fraudes su sistema.

El resultado puede probarse en: https://guarded-fortress-67067.herokuapp.com/
