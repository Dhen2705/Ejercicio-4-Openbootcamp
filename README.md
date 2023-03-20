# Ejercicio-4-Openbootcamp


public class Main {
    public static void main(String[] args) {
        // crear una condición que compare si la variable numeroIf es positivo, negativo, o 0.

        int numeroIf = 5;

        if (numeroIf>0){
            System.out.println("La Variable es positivo");
        }
        else if(numeroIf<0){
            System.out.println("La Variable  es negativa");
        } else {
            System.out.println("La variable  es 0");
        }
        //while
        int numeroWhile = 1;

        while(numeroWhile < 3){
            numeroWhile++;
            System.out.println("La variable numeroWhile ahora vale: " + numeroWhile);
        }

        //do while
        //Al no cumplirse la condición, solo entra en el bucle una vez
        int numeroDoWhile = 3;
        do{
            numeroDoWhile++;
            System.out.println("La variable numeroDoWhile ahora vale: " + numeroDoWhile);
        }while(numeroDoWhile < 3);

        //for
        for(int numeroFor = 0; numeroFor <= 5; numeroFor++){
            System.out.println("La variable numeroFor ahora vale: " + numeroFor);
        }

        //switch
        String estacion = "otoño";
        switch(estacion) {
            case "verano":
                System.out.println("Estamos en verano");
                break;
            case "invierno":
                System.out.println("Estamos en invierno");
                break;
            case "primavera":
                System.out.println("Estamos en primavera");
                break;
            case "otoño":
                System.out.println("Estamos en otoño");
                break;
            default:
                System.out.println("No es una estación");
        }
    }

}
