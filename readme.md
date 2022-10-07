# Explicación

- Algo en negrita
- Enlace a la wikipedia
- Foto de un gato
- Una mención a Kant003
- Un titulo principal y dos secundarios
- Un cheklist con tareas marcadas y desmarcadas
- Un trozo de codigo fuente en otro lenguaje
- Una tabla comparativa de diferentes tipos de razas
- Algun emoji 
- Sube los cambios a tu repositorio

# Web de Gatos

Esta se trata de una web con iformación que puede resultar interesante a ciertas personas.

## ¿Qué es un gato?
------------------

**Gato**: procedente del vocablo latino *cattus*, es un término que alude a un animal mamífero que forma parte del conjunto de los félidos: 

![Imagen de un gato para compelementar la definición](https://enciclopedia.net/imgs/Gato.jpg)
##### *Imagen de un gato*

Cabe mencionar que existen gran variedad de especies felinas catalogadas en razas.

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
Finalizada la etapa de decisión t