# Az-104 - Administrador Azure
----
## Pre requisitos para administradores de azure

### Configuración de recursos de azure con herramientas

Los administradores de azure utilizan herramientas para interactuar con los ambientes de nube y completar tareas como:

1. Desplegar cientos o miles de recursos al mismo tiempo
2. Configurar servicios individualmente usando scripts
3. Visualizar reportes de uso, salud, costos etc etc

Azure nos provee las siguientes herramientas para poder realizar la administración de manera adecuado y de acuerdo al problema que se está resolviendo.

1. Azure portal [https://portal.azure.com]( https://portal.azure.com)

    El portal de azure nos permite construir, administrar y monitorear todo!, desde una simple aplicación web hasta una aplicación de nube compleja.

2. Azure Cloud Shell

    Es una shell que se abre desde el portal de azure, te permite seleccionar entre Bash para usuarios de linux o Powershell para usuario windows.

    Esta herramienta nos permite administrar nuestros recursos de azure, además contiene algunas características específicas como las podemos visualiza en la siguiente lista:


    * Para poder ser utilizado necesita de "Azure File" para poder ser montado sobre este recurso.

    * Ofrece un editor gráfico basado en Monaco Editor proyecto open source

    * Al ingresar desde el portal de azure, este se auntentica de manera automática

    * Si después de 20 minutos no detecta actividad genera un time out y cierra la sesión.

    * Requiere de un grupo de recursos, una cuenta de almacenamiento o como se le dice comunmente "storage account" y un un Azure File share

    * Tanto para Powershell como para Bash utiliza el mismo Azure File Share

    * Persite información en $HOME hasta 5GB


3. Azure Powershell

    Es un módulo(Az module) que puede ser cargado en el Powershell de Windows que conocemos y que contiene comandos propios, como por ejemplo: "New-AzVm"

    Cabe mencionar que se puede instalar en los sistemas operativos: Linux, macOS y Windows.

    Esta herramienta nos permite trabajar con los siguientes recursos:

        1. Resource groups
        2. Storage
        3. VMs
        4. Azure AD
        5. Containers
        6. Machine learning


4. Azure CLI

    Azure CLI es una herramienta de línea de comandos que permite conectarse a Azure y ejecutar comandos de administración sobre los recursos de azure.
    Se puede ejecutar en los sistemas operativos principales como Linux, macOS y Windows

    Al ser una herramienta multiplataforma contiene sus propios comandos, por ejemplo, para reiniciar una máquina virtual podemos utilizar el comando:

        az vm restart -g MyResourceGroup -n M




