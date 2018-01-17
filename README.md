# Netfilter

La realización de la memoria de este trabajo se basa en el proyecto de software libre
Netfilter.

Netfilter es un framework de filtrado, enrutado y registro de paquetes de red además de un traductor de direciones (NAT) del kernel de Linux. Ofrece un conjunto de herramientas en espacio de usuario para trabajar con el seguimiento de paquetes además de componentes para el kernel de Linux.

Netfilter cuenta con un montón de proyectos todos de software libre. Uno de los proyectos más conocidos en Netfilter es iptables que ofrece una herramienta en espacio de usuario de Linux para configurar las reglas del firewall y enrutado de la máquina. Nftables es la herramienta que intenta reemplazar a iptables in la configuración de reglas del firewall y enrutado en linux. También ofrece librerías de desarrollo para el sistema operativo como conntrack o libmnl para facilitar el trabajo a otros desarrolladores.

Una cosa importante a destacar de Netfilter es que es un proyecto de servicios gratuitos y por tanto no tiene un ánimo lucrativo cómo organización. El proyecto existe por el esfuerzo de la comunidad, las contribuciones y el uso de las herramientas.

Isn't it great that you can have a fully-fledged feature-rich packet filter, and all for free?

The netfilter/iptables project is a volunteer-based community effort. We can only exist because of the contributions of our users. If nobody would write any code, answer questions on the mailinglists, write documentation, ... the project wouldn't exist.

So basically, it's your choice where you want to see the project tomorrow. If you are interested in the further progress of this project: Please contribute.

La forma más obvia de ayudar en el proyecto es desarrollando, arreglando bugs o realizando mejoras sobre el software. Otra manera de contribuir puede ser realizando doncaciones escribiendo documentación o traduciéndola. Hay que tener en cuenta que cualquier donación que hagamos será decisión de la comunidad el uso de esa donación y no del que la realizó.

# Infraestructura

## Página web

Netfilter cuenta con una página web oficial donde podemos encontrar toda la documentación e información necesaria para empezar en el proyecto y entenderlo. La página web intenta ser el portal de acceso a nuevos contribuidores ya que los usuarios serán todos los usuarios que utilicen un sistema operativo linux, al tener un conjunto de herramientas y librerías estándar dentro del Kernel.

![alt text](img/net_filter_web.png)

## Control de versiones

El uso de control de versiones del software es a través de git. El proyecto de netfilter tiene su propia plataforma git. El repositorio
git está plataformado sobre un servidor web y podemos acceder al git
del proyecto a través de su [enlace](https://git.netfilter.org/) cuenta también con un control de versiones sobre subversion (svn) pero
el repositorio está obsoleto.

![alt text](img/git_repo_ntfilter.png)

### Issues para contribuciones

Podríamos realizar cualquier contribución dentro de estos proyectos si accedemos por ejemplo al proyecto de iptables podemos ver el resumen total del proyecto y cuales han sido los últimos commit del proyecto.

![alt text](img/iptables_summary.png)
