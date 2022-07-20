# tp_java
mport java.math.BigDecimal;

public class Main {
    public static void main(String[] args) {
        System.out.println("Hello world!");

        double valeur =0.15;
        double totaldouble=valeur+valeur+valeur;
        System.out.println("Total = " +totaldouble);
        String valeurTex= Double.toString(valeur);
        System.out.println("valeurText = " +valeurTex);
        BigDecimal valeurBig =new BigDecimal(valeurTex);
        BigDecimal totalBig = valeurBig.add(valeurBig.add(valeurBig));
        System.out.println("total valeurBig =" +totalBig);
    }

}
