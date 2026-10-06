>## 1. En la función1… Què fan aquestes línies de codi?
>**String string2 = "string2"; <br>
string2= string2.substring(0, string2.length()-1); <br>
string2=string2+"1";**

Es basicamente un bucle. <br>
Esta función1, estas lineas de codigo lo que hacen es marcar una variable con el nombre de "string2" el cual con la segunda linea de codigo hacemos que el valor de "string2" (que sería 7 ya que tiene 7 caracteres en su nombre) pase a ser 6 eliminando el ultimo caracter con el "-1" convirtiendolo en "string" a secas, lurgo en la ultima linea de codigo se encarga en sumarle un caracter especifico al "string" hacieno que su nombre vuelva a cambiar llamandose "string1" ya que le hemos sumado al final de el titulo de la variable un numero especifico (+"1")

>## 2. Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?
>**if(string1 == string2 ) { <br>
System.out.println("SÓN IGUALS " + a );. <br>
} <br>
else { <br>
System.out.println("SÓN DIFERENTS"); <br>
}**

Las variables "string1" y "string2" valen exactamente de la siguiente forma:
* string1 = string1
* string2 = string2 (aunque el texto se vea como "string1" por el codigo realizado anteriormente)

>## 3. Per què no funciona l'operador == ? Quin operador s'ha d'usar en lloc d'aquest?
Realmente si que funciona el operador "==" ya que no es capaz de leer el texto de las variables, solo el valor de las variables como tal y como el valor de las variables sigue siendo "string1" y "string2" lo detecta como dierentes aunque el texto de los dos trings aparezca igual

>## 4. La función2() està declarada com segueix:
>**public void funcion2() { <br>
System.out.println("--------------------"); <br>
System.out.println("Aquesta és la funció 2"); <br>
System.out.println("Com faig la crida perquè funcione????"); <br>
}**
>
>**Aquesta funció com l'he de cridar des del mètode MAIN perquè funcione. Existeixen 2
>possibilitats. Explica-les.
>Crea un directori de treball anomenat EntornosDesarrollo**
>* **Inicializalo amb GIT**
>* **Sincronitza-ho en el teu GitHub Remot**
>* **Crea un carpeta dins de Entorns de Desenvolupament anomenada “Tasca-Depuracion1”**
>* **Contesta les preguntes en un document MarkDown dins d'aquesta carpeta.**
>* **Actualitza amb GIT el repositori d'Entorns de Desenvolupament local i REMOT**
>* **Envia la URL del repositori**                  

