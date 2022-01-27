// Sintaxis declarativa: MAS SENCILLA y LA MAS USADA. Menos potente que la de scripting... 
//          pero mucho MAS que los proyectos de estilo libre
// Sintaxis de scripting: MAS COMPLEJA Y MAS POTENTE: Puedo hacer lo que quiera con Jenkins
pipeline {
    
    agent any // Para definir DONDE QUIERO QUE SE EJECUTE ESTA TAREA
    
    stages {
       stage("Etapa 1") {
           steps { // Hacemos las llamadas a los plugins
               sh "echo Soy la etapa 1" // Llamada al plugin que ejecuta una shell
           }
       }
       stage("Etapa 2") {
           steps {
               sh """
               echo Soy la etapa 2
               echo Acabo la etapa 2
               """
           }
       }
    }
}