# Polimorfismo
package tienda_level.sshop;

public class Tienda_LevelSShop {
  
    public static void main(String[] args){
        Ropa Rop[] = new Ropa[2];
                
        Rop[0] = new Ropa(2547, 0.00);
        Rop[1] = new Camisas("Nike","Balnco con negro", 14, 2451, 25.00);
        Rop[2] = new Pantalones("Cat","Azul negro", 32, 5784, 30.00);  
        
        for(Ropa ropa: Rop){
            System.out.println(ropa.verDatos());
            System.out.println("");
        }
    } 
}
