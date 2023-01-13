# CS_CreacionDeAplicaciones

lista detallada de todos los comandos

```bash
dotnet --help
```

****instalar un paquete****

```bash
dotnet add package <dependency name>
```

si quiere ver qué paquetes hay en la carpeta

```bash
dotnet list package
```

La inclusión de los transitivos le permitirá ver las dependencias junto con todos los paquetes que haya instalado.

```bash
dotnet list package --include-transitive
```

****Restauración de dependencias****

```bash
dotnet restore
```

****Limpieza de las dependencias****

```bash
dotnet remove package <name of dependency>
```

CLI de .NETdotnet --list-sdks

```bash
dotnet --list-sdks
```

****Creación de un proyecto de .NET de ejemplo****

1. En Visual Studio Code, seleccione **Archivo**>**Abrir carpeta**.
2. Cree una carpeta denominada **DotNetDependencies** en la ubicación que prefiera y, después, seleccione **Seleccionar carpeta**.
3. Abra el terminal integrado desde Visual Studio Code; para ello, seleccione **Ver**>**Terminal** en el menú principal.
4. En la ventana del terminal, copie y pegue el siguiente comando.

```bash
dotnet new console -f net6.0
```

1. En la ventana del terminal, copie y pegue el siguiente comando para ejecutar el programa "Hola mundo".

```bash
dotnet run
```
