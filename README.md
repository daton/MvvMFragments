# Tutorial MVVM con Fragmentos
Este tutorial usa la plantilla de Navigation Drawer de Android Studio

## Primer paso: Creación del Modelo
Para este ejemplo vamos a usar el siguente  modelo simple basado en la entidad Ejercicio como sse muestra a continuación
![person-writing-on-white-paper-3815585](app/src/main/res/mipmap-hdpi/person-writing-on-white-paper-3815585.png)
````
class Ejercicio {
   var id:String?=null
   var nombre:String?=null 
    var repeticiones:Int?=null
}
````