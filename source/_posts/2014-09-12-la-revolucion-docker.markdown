---
layout: post
title: "La Revolución Docker"
date: 2014-9-12 09:46:12 +0100
comments: true
categories: [docker]
---

Si eres desarrollador o responsable de desarrollo, ya lo conoces. El boca a boca ha sido imparable para **este proyecto de software libre que está transformado como se despliegan las aplicaciones**. Docker te permite ejecutar tus aplicaciones en cualquier lugar, desde tu portátil hasta la instancia EC2 de Amazon más potente y cualquier cosa entre medio, sin atarte a un lenguaje de programación, a un "framework" o sistema de instalación que utilice un S.O. Los contenedores Docker son agnósticos respecto al hardware y la plataforma.

![dockerlogo](/images/blog/docker-transparent-400x310.png)
<!-- MORE -->

Si eres el responsable de sistemas o administrador de sistemas y piensas que resolvías el problema con máquinas virtuales te has perdido la mitad de la película. Las máquinas virtuales son una poderosísima herramienta que ha permitido exprimir al máximo un hardware que era costoso y que estaba siendo infrautilizado. Sí, las VMs han cambiado considerablemente los CPDs y las operaciones... pero no han conseguido -en un mundo dónde el cambio constante y ya no se habla de integración continua sino de despliegue continuo- simplificar y acelerar el despliegue de aplicaciones. Por muchos motivos:

* 	Tamaño: Las VMs son demasiado grandes.
* 	Portabilidad: es una ironía que la virtualización haya permitido independizarte de los fabricantes de servidores para atarte a tecnologías que no interoperan fácilmente.
* 	Foco: las máquinas virtuales están pensadas con las operaciones de TI en mente... no los desarrolladores o en la aplicaciones. No hay versionado de aplicaciones, monitorización específica, configuración, gestión de logs o descubrimiento de servicios.
* 	Rendimiento: Las VMs no facilitan el escalado horizontal o el desarrollo de aplicaciones multicapa.

![DockerandVMs](/images/blog/VMs-Docker-trans-1000x611.png)

Por todo esto Docker está aquí. **Los contenedores de Docker son pequeños, apenas tienen un impacto en el rendimiento, son completamente portables y están pensados con la aplicación en mente** (y se pueden ejecutar dentro de máquinas virtuales). Permiten desplegar las aplicaciones en cualquier lugar, rápida y cómodamente. Por eso está aquí para quedarse. Docker es sólo el resultado de desarrolladores frustrados con operaciones, buscando una mejor manera de hacer las cosas, una herramienta más que ha nacido del movimiento DevOps y que, en último término, pretende volver a hacer hablar operaciones y desarrolladores el mismo idioma, centrarse en lo importante: las aplicaciones.

