# Ejercicios-tema-8-OpenBootcamp
ejercicio tema 8
public class Persona {
    private int edad;
    private String nombre;
    private String telefono;

    public int getEdad() {
        return edad;
    }

    public void setEdad(int edad) {
        this.edad = edad;
    }

    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

    public String getTelefono() {
        return telefono;
    }

    public void setTelefono(String telefono) {
        this.telefono = telefono;
    }
}

public static void main(String[] args) {
    Persona persona = new Persona();

    persona.setEdad(30);
    persona.setNombre("Juan");
    persona.setTelefono("123456789");

    System.out.println("Nombre: " + persona.getNombre());
    System.out.println("Edad: " + persona.getEdad());
    System.out.println("Teléfono: " + persona.getTelefono());
}
