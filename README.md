Asignatura Cloud Computing del Máster en Ingeniería Informática. 

Departamento de Ciencias de la Computación e Inteligencia Artificial.

Universidad de Granada.

<HR>

Profesor: **Francisco Javier Baldán Lozano**

Email: **fjbaldan@decsai.ugr.es**

Tutorías: **Lunes, de 11:00 a 12:00, despacho D31 (4ª planta) Escuela Técnica Superior de Ingenierías Informática y de Telecomunicación (ETSIIT). Se recomienda concretar las citas por correo.**

Material de prácticas de la asignatura: **https://github.com/fjbaldan/PracticasCC**

Francisco Javier Baldán Lozano (fjbaldan@decsai.ugr.es), Febrero 2019

![DICITSlogo](http://sci2s.ugr.es/dicits/images/dicits.png)

Material realizado a partir del trabajo de años anteriores de Manuel Parra & José Manuel Benitez: https://github.com/DiCITS/MasterCienciaDatos2019 & https://github.com/manuparra/PracticasCC

<HR>

# Sesión 1: Microsoft AZURE

Tabla de contenido:

  * [Requisitos iniciales](./sesion1/README.md#requisitos-iniciales)
  * [Registro de alumnos](./sesion1/README.md#registro-de-alumnos)
  * [Comenzando con máquinas virtuales (MV o VM)](./sesion1/README.md#comenzando-con-máquinas-virtuales-MV-o-VM)
  * [Creación del agrupamiento de recursos](./sesion1/README.md#creación-del-agrupamiento-de-recursos)
  * [Creación de una máquina virtual](./sesion1/README.md#creación-de-una-máquina-virtual)
  * [Conéctese a la VM](./sesion1/README.md#conéctese-a-la-vm)
  * [Mercado de imágenes VM](./sesion1/README.md#mercado-de-imágenes-VM)
  * [Máquinas virtuales funcionando](./sesion1/README.md#máquinas-viruales-funcionando)
  * [Características de una máquina virtual](./sesion1/README.md#características-de-una-máquina-virtual)
  * [Parar una máquina virtual](./sesion1/README.md#parar-una-máquina-virtual)
  * [Iniciar una máquina virtual](./sesion1/README.md#iniciar-una-máquina-virtual)
  * [Reiniciar una máquina virtual](./sesion1/README.md#reiniciar-una-máquina-virtual)
  * [Eliminar una máquina virtual](./sesion1/README.md#eliminar-una-máquina-virtual)
  * [Abrir puertos de una máquina virtual](./sesion1/README.md#abrir-puertos-de-una-máquina-virtual)
  * [Ejercicio práctico A (instalación de servicios de forma manual)](./sesion1/README.md#ejercicio-práctico-a-instalación-de-servicios-de-forma-manual)
  
# Sesión 2: Despliegue automatizado de software y servicios 

Tabla de contenido:

  * [Requisitos iniciales](./sesion2/README.md#requisitos-iniciales)
  * [Acceso vía SSH](./sesion2/README.md#acceso-vía-ssh)
  * [Despliegue automático de servicios y software](./sesion2/README.md#despliegue-automático-de-servicios-y-software)
  * [Breve introducción a ANSIBLE](./sesion2/README.md#breve-introducción-a-ansible)
    + [Elementos en ANSIBLE](./sesion2/README.md#elementos-en-ansible)
    + [Instalación de ANSIBLE](./sesion2/README.md#instalación-de-ansible)
    + [Definición del fichero de inventario](./sesion2/README.md#definición-del-fichero-de-inventario)
    + [PlayBooks básicos](./sesion2/README.md#playbooks-básicos)
  * [Despliegue de software y servicios sobre MV](./sesion2/README.md#despliegue-de-software-y-servicios-sobre-mv)
    + [Creamos el fichero de inventario](./sesion2/README.md#creamos-el-fichero-de-inventario)
    + [Instalamos un servicio web](./sesion2/README.md#instalamos-un-servicio-web)
  * [Despliegue de servicios relacionados con la práctica del curso](./sesion2/README.md#despliegue-de-servicios-relacionados-con-la-práctica-del-curso)

# Sesión 3: Despliegue de servicios en contenedores

Tabla de contenido:

  * [Acceso vía SSH](./sesion3/README.md#acceso-vía-ssh)
  * [Despliegue automático de servicios y software](./sesion3/README.md#despliegue-automático-de-servicios-y-software)
    + [Creación de script de inicio/parada y orquestación de MVs](./sesion3/README.md#creación-de-script-de-inicioparada-y-orquestación-de-mvs)
  * [Contenedores con DOCKER](./sesion3/README.md#contenedores-con-docker)
    + [VIRTUAL MACHINES](./sesion3/README.md#virtual-machines)
    + [CONTAINERS](./sesion3/README.md#containers)
    + [KATAContainers](./sesion3/README.md#katacontainers)
  * [Ventajas de DOCKER](./sesion3/README.md#ventajas-de-docker)
  * [Despliegue de Contenedores](./sesion3/README.md#despliegue-de-contenedores)
    + [Instalación de DOCKER en tiempo de instanciación](./sesion3/README.md#instalación-de-docker-en-tiempo-de-instanciación)
    + [Trabajo con DOCKER: Gestión de contenedores](./sesion3/README.md#trabajo-con-docker-gestión-de-contenedores)
      - [Parametrización de contenedores con DOCKER](./sesion3/README.md#parametrización-de-contenedores-con-docker)
    + [Creación de contenedores enlazados](./sesion3/README.md#creación-de-contenedores-enlazados)
      - [Maquina Virtual 1](./sesion3/README.md#maquina-virtual-1)
      - [Maquina Virtual 2](./sesion3/README.md#maquina-virtual-2)
    + [Instalación del servicio completo OWNCLOUD + MYSQL](./sesion3/README.md#instalación-del-servicio-completo-owncloud--mysql)


# Sesión 4: Despliegue de servicios en contenedores

Tabla de contenido:

  * [Requisitos iniciales](./sesion4/README.md#requisitos-iniciales)
  * [Acceso vía SSH](./sesion4/README.md#acceso-vía-ssh)
  * [Despliegue y gestión de servicios de autenticación de usuarios](./sesion4/README.md#despliegue-y-gestión-de-servicios-de-autenticación-de-usuarios)
    + [Entrenando con LDAP](./sesion4/README.md#entrenando-con-ldap)
    + [LDAP Basics](./sesion4/README.md#ldap-basics)
    + [Objetos y clases](./sesion4/README.md#objetos-y-clases)
    + [Atributos](./sesion4/README.md#atributos)
    + [Entradas](./sesion4/README.md#entradas)
    + [DIT](./sesion4/README.md#dit)
    + [Distinguished name (dn). Nombre distinguido.](./sesion4/README.md#distinguished-name-dn-nombre-distinguido)
  * [Verificando el estado del directorio LDAP](./sesion4/README.md#verificando-el-estado-del-directorio-ldap)
    + [Añadir un nuevo usuario](./sesion4/README.md#a-adir-un-nuevo-usuario)
  * [Cambiar el Password de un usuario en LDAP](./sesion4/README.md#cambiar-el-password-de-un-usuario-en-ldap)
    + [Modificando cuentas de usuario con LDAP: DELETE, MODIFY.](./sesion4/README.md#modificando-cuentas-de-usuario-con-ldap-delete-modify)
  * [Añadir una UO a LDAP](./sesion4/README.md#añadir-una-uo-a-ldap)
  * [Buscando y encontrado dentro del DIT](./sesion4/README.md#buscando-y-encontrado-dentro-del-dit)
  * [Ejercicio: Crear un servicio de directorio LDAP en contenedor dentro de una MV](./sesion4/README.md#ejercicio-crear-un-servicio-de-directorio-ldap-en-contendor-dentro-de-una-mv)




