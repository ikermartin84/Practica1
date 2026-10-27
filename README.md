# Practica1
...
## 1. Fundamentos del sistema
1. El usuario podrá crear una cuenta utilizando un correo electrónico y una
contraseña.
2. El usuario podrá iniciar y cerrar sesión.
3. El usuario podrá crear, modificar y eliminar asignaturas.
4. El usuario podrá crear tareas indicando su nombre, asignatura y fecha
de entrega.
5. El usuario podrá crear eventos para indicar las fechas de los
exámenes.


## 2. Análisis y especificación de requisitiso
1. Usabilidad: la interfaz deberá ser sencilla e intuitiva para que un
estudiante pueda aprender a utilizarla rápidamente.
2. Rendimiento: las páginas principales deberán cargarse en pocos
segundos con una conexión a Internet normal.
3. Seguridad: las contraseñas deberán almacenarse de forma segura y
los datos personales deberán estar protegidos.
4. Disponibilidad: el servicio deberá estar disponible la mayor parte del
tiempo, salvo durante tareas de mantenimiento.
5. Compatibilidad: la aplicación deberá funcionar correctamente en los
principales navegadores actuales, como Chrome, Firefox, Edge y
Safari.
6. Adaptabilidad: la interfaz deberá adaptarse a ordenadores, tablets y
teléfonos móviles.
7. Escalabilidad: el sistema deberá poder soportar un aumento del
número de usuarios sin perder rendimiento de manera significativa.
8. Mantenibilidad: el código deberá estar organizado y documentado
para facilitar futuras modificaciones y correcciones.
9. Privacidad: el sistema deberá tratar los datos personales de los
usuarios de acuerdo con la normativa de protección de datos aplicable

## 3. Diseño
- ¿Cómo organizas actualmente tus tareas y exámenes?
● ¿Utilizas alguna aplicación para organizarte?
Entrevistas
También realizaremos entrevistas con algunos estudiantes y profesores. Las
entrevistas permitirán obtener información más detallada y conocer
problemas que podrían no aparecer en las encuestas

- Elección de la técnica
Hemos elegido principalmente las encuestas porque nuestro software está
dirigido a un grupo amplio de usuarios. Además, las entrevistas nos
permitirán profundizar en las respuestas obtenidas.
## 4. Implementación

public class Area {
public static void main(String[] args) {
    double RADIO = 5.0;
    double PI = 3.14159;
    double area = PI * RADIO * RADIO;
    System.out.println("El área es " + area);
  }
}

public class OperacionesMatematicas {
public static int sumar(int numeroUno, int numeroDos) {
    return numeroUno + numeroDos;
  }
public static int restar(int minuendo, int sustraendo) {
    return minuendo - sustraendo;
  }
public static int multiplicar(int numeroUno, int numeroDos) {
    return numeroUno * numeroDos;
  }
public static int dividir(int dividendo, int divisor) {
    return dividendo / divisor;
  }
public static void main(String[] args) {
    System.out.println(sumar(3, 4));
    System.out.println(restar(5, 2));
    System.out.println(multiplicar(2, 6));
    System.out.println(dividir(8, 2));
  }
  }
public class Calculadora {
public int sumar(int numeroUno, int numeroDos) {
    return numeroUno + numeroDos;
  }
public int restar(int numeroUno, int numeroDos) {
    return numeroUno - numeroDos;
  }
public int multiplicar(int numeroUno, int numeroDos) {
    return numeroUno * numeroDos;
  }
public int dividir(int dividendo, int divisor) {
    return dividendo / divisor;
  }
public static void main(String[] args) {
    Calculadora calculadora = new Calculadora();
    System.out.println(
    "Resultado: " + calculadora.sumar(5, 3);
    }
  }
public class Alumno {
    private String nombre;
    private int edad;
    private double notaFinal;
public Alumno(String nombre, int edad, double notaFinal) {
    if (edad < 0 || notaFinal < 0 || notaFinal > 10) {
    throw new IllegalArgumentException(
    "La edad o la nota no son válidas.");
    }
    this.nombre = nombre;
    this.edad = edad;
    this.notaFinal = notaFinal;
    }
    public void mostrarDatos() {
    System.out.println("Alumno: " + nombre);
    System.out.println("Edad: " + edad);
    System.out.println("Nota final: " + notaFinal);
    }
    public boolean aprobado() {
    return notaFinal >= 5.0;
    }
    public void mensajeFinal() {
    if (aprobado()) {
    System.out.println(
    "¡Felicidades, " + nombre + ", has aprobado!");
    } else {
    System.out.println(
    "Lo siento, " + nombre + ", no has aprobado.");
  }
  }
}
## 5. Plan de pruebas del sistema


### 5.1. Pruebas de aceptación
Nada por aquí 

## 7. Los diccionarios de datos
