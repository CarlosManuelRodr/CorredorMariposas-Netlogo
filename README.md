# CorredorMariposas-Netlogo
Simulación de corredor de mariposas en NetLogo basado en el modelo descrito en el libro Railsback, Steven F., and Volker Grimm. *Agent-based and individual-based modeling : a practical introduction*. Princeton Oxford: Princeton University Press, 2019. Print.

El modelo fue creado basado en artículo: Guy Pe'er, et al. “Virtual Corridors for Conservation Management.” *Conservation Biology*, vol. 19, no. 6, 2005, pp. 1997–2003. *JSTOR*, www.jstor.org/stable/3591221.

Este modelo muestra la aparición emergente de corredores de mariposas a partir de la interacción de las mariposas con el medio ambiente. En cada paso, las mariposas o bien se mueven hacia una posición más alta con una probabilidad *q*, o bien se mueven aleatoriamente con una probabilidad *1-q*.

Este modelo cuenta con dos tipos de ambiente, un ambiente sencillo:

![modelo simple](https://raw.githubusercontent.com/CarlosManuelRodr/CorredorMariposas-Netlogo/master/img/simple.gif)

Y un ambiente realista:

![realista](https://raw.githubusercontent.com/CarlosManuelRodr/CorredorMariposas-Netlogo/master/img/realistic.gif)

A partir del modelo se puede obtener la anchura de corredor promedio para cada valor de *q*.

![anchuras](https://raw.githubusercontent.com/CarlosManuelRodr/CorredorMariposas-Netlogo/master/img/corridor_width.png)