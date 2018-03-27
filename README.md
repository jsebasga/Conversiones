# MostarConversiones
public class MostrarConversiones {
 public static void main(String[] args) {
        Conversiones con = new Conversiones();
        System.out.println("El resultado es: "+con.megabytesAGigabytes(10)+" Gigabytes");
        System.out.println("El resultado es: "+con.gigabytesATerabytes(10)+" Terabytes");
        System.out.println("El resultado es: "+con.gigabytesAMegabytes(10)+" Megabytes");
        System.out.println("El resultado es: "+con.terabytesAGigabytes(10)+" Gigabytes");
}
