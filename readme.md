
# Web de Gatos

Esta se trata de una web con iformación que puede resultar interesante a ciertas personas.

## ¿Qué es un gato?
------------------

![Imagen de un gato para compelementar la definición](https://enciclopedia.net/imgs/Gato.jpg)
##### *Imagen de un gato*



## Comparativa de razas
-----------------------

#### Este es el top 5 de razas más populares del momento con datos que puedan resultar de interes para futuros dueños. 

|Puesto| Raza      |   Tamaño  | Comportamiento|
|:-----| :---------: | :--------:| :-------------:|
|**1**         | **Siames**    | Pequeño   | Agresivo      |
|**2**         | **Persa**| Medio| Dócil|
|**3**        | **Sphynx**| Grande| Nervioso|
|**4**        | **Siberiano**| Medio| Asustadizo|
|**5**        | **Charteux**| Grande| Dócil|

En caso de que el lector esté interesado en adquirir un gato  pero no se lo pueda permitir, adjutamos un *"objeto gato"* en **Java** ~~el cual no hace un carajo si no creas otra clase testeandolo~~.

```Java
public class Gato {
	
	public void setEdad(int e){edad = e;}
	public void setcolor(char c){color=c;}
	public void Maullar() {
		System.out.println("Miau Miau");
	}
	public void IrALaCajaDeArena() {
		System.out.println("¿Y tu que miras?");
	}
	
	@Override
	public String toString() {
		return "Gato [color=" + color + ", edad=" + edad + "]";
	}

	private char color;
	private int edad;

}

```

## Lista de tareas
------------------

* [x] Alimetarlos con pienso ultima
* [ ] Bañarlos
* [x] Comprarles un rascador
* [ ] Cortales las uñas
* [x] Enseñarle trucos
  * [x] Enseñarle a hacer la declaración de la renta
  * [ ] Enseñarle a conducir

## Bibliografía
------------------

Toda la información ha sido Obtenida a través de este artículo de [Wikipedia](https://es.wikipedia.org/wiki/Felis_silvestris_catus).

### Agradecimientos
-----
Esta web ha sido en parte creada a la aportación de @Kant003 :smiling_imp::thumbsup: