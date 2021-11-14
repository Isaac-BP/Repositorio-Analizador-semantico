# Analizador Semantico

El analizador semántico es la fase que sigue al análisis sintáctico. En esta fase se explora el AST (árbol de sintaxis abstracta) con el fin de detectar los errores semánticos.

FUNCIONES DE UN ANALIZADOR SEMANTICO:

•Identificar cada tipo de instrucción y sus componentes

•Completar la Tabla de Símbolos

•Realizar distintas comprobaciones y validaciones:

•Comprobaciones de tipos.

•Comprobaciones del flujo de control.

•Comprobaciones de unicidad.

•Comprobaciones de emparejamiento.

•El  Analizador  Semántico  finaliza  la  fase  de  Análisis  del  compilador  y  comienza  la  fase  de Síntesis, en la cual se comienza a generar el código objeto.

El analizador semántico utiliza el árbol sintáctico y la información en la tabla de símbolos para comprobar la consistencia semántica del programa fuente con la definición del lenguaje. También recopila información sobre el tipo y la guarda, ya sea en el árbol sintáctico o en la tabla de símbolos, para usarla más tarde durante la generación de código intermedio. Una parte importante del análisis semántico es la comprobación (verificación) de tipos, en donde el compilador verifica que cada operador tenga operando que coincidan. Por ejemplo, muchas definiciones de lenguajes de programación requieren que el índice de un arreglo sea entero; el compilador debe reportar un error si se utiliza un número de punto flotante para indexar el arreglo.
