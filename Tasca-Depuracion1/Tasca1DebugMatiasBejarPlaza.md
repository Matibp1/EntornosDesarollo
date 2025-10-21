# U2: TASCA 1.
**Matias Bejar**

---

## 1. En la función1… Què fan aquestes línies de codi?

String string2 = "string2";

- Creamos una variable string llamada "string2" la cual contiene una cadena de texto con el valor: string2.

string2= string2.substring(0, string2.length()-1);
string2=string2+"1";

- En la primera linea se modifica el valor de la variable string2 con el metodo substring. Aplica el metodo con valor de la propia variable y le quita una letra en este caso el "2"
- En la siguiente linea cambia el valor de la variable que acaba de modicicar añadiendo un 1. Por lo que el valor de la variable string2 es "string1"

---

## 2. Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?s

if(string1 == string2 ) {
System.out.println("SÓN IGUALS " + a );.
}
else {
System.out.println("SÓN DIFERENTS");
}

- Como estamos comparando con un " == " en el if no entrara en el primer bloque del if por que no esta comparandose dos cadenas de texto por lo que es FALSE.
  Nos devolera: SÓN DIFERENTS



---

## 3. Per què no funciona l'operador == ? Quin operador s'ha d'usar en lloc d'aquest?

- No funciona el operador == porque compara si las variables apuntan al mismo objeto en memoria y no el texto que contienen. Para este cadso debemos usar el metodo .equals() para comparar dos strings

---

## 4. La función2() està declarada com segueix:

public void funcion2() {
        System.out.println("--------------------");
        System.out.println("Aquesta és la funció 2");
        System.out.println("Com faig la crida perquè funcione????");
}

**Aquesta funció com l'he de cridar des del mètode MAIN perquè funcione. Existeixen 2possibilitats. Explica-les**

- Una forma seria hacer la funcion estatica **public static void funcion2()** para ponder llamarla directamente desde el main

- Otras manera para dejarla no estatica es crear un objero y llamar la funcion con ese objeto.