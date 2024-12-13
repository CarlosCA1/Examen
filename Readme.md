# Examen 1ª Evaluación

---

* Creamos un tablero y usamos un "for" para recorrerlo.
* Con un "if" verificamos si la casilla está ocupada.
* Con un "for" recorremos el tablero y mediante un contador contamos el número de cada tipo de ficha.
* Con un "if" comprobamos quién gana, dependiendo del número de las mismas.

Imagen:
![imagen](imagen/diagrama.png)
https://drive.google.com/file/d/1jt4Pjo9KrJBeM0Vi77U0fdDLIeTLWLIZ/view?usp=drive_link

Tablero:

```)
int [][] tablero =
{{x b x b x x x n},
{x b x b n x n n},
{b b x b x x x x},
{n x x b b x x x},
{b x x b x x b x},
{x b x x b n b b},
{n b b x x b n x},
{n b x x b n b x},
};
```
Funciones que se podrían emplear y javadoc:
```)
/**
* Recorre el tablero y verifica si la casilla está ocupada.
* @param tablero [][] Recoge el tablero.
**/
public static void recorrerTablero (String tablero [][]) {
}

/**
* Cuenta las fichas de cada jugador.
* @param tablero [][] Recoge el tablero.
**/
public static void contarFichas (String tablero[][]){
}

/**
* Indica quién va ganando
* @param numBlancas
* @param numNegras
**/
public static void mostrarGanador (int numBlancas, int numNegras){
}
