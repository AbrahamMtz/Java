# Java
public class Funciones {
    public void suma1(int x, int y){
        long suma=x+y;
        System.out.println("La suma es "+suma);
        System.out.println(x+"+"+y+"="+suma);
    }
    
    public long suma2(int x, int y){
        return x+y;
    }
    
    public void resta1(int x, int y){
        long resta=x-y;
        System.out.println("El resultado de la resta es "+resta);
        System.out.println(x+"-"+y+"="+resta);
}
    public void multiplicacion1(double x, double y){
            double multiplicacion=(x*y);
            System.out.println("El resultado de la multiplicacion es "+multiplicacion);
            System.out.println(x+"*"+y+"="+multiplicacion);
    }
    
    public void division1(double x, double y){
        double division=(x/y);
        if(y==0){
            System.out.println("Math Error");
        }else {
            System.out.println("El resultado de la division es "+division);
            System.out.println(x+"/"+y+"="+division);
        }
        
  
    }
    
    public void ecuacionelineal(double x, double y){
    if(x==0 && y!=0){
        System.out.println("Error");
    }else {
        if(x==0 && y==0){
            System.out.println("Error");
        }else{
        System.out.println(x+"x+"+y+"=0");
        System.out.println("Solucion es x = "+y/x);
        }
    }
    
    }
}
