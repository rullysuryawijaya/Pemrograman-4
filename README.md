# Pemrograman-4
/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */
package inherit;

/**
 *
 * @author STUDENT
 */
public class Inherit {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Hewan hewan = new Hewan();
        hewan.tidur();
        hewan.makan();

        Kucing a = new Kucing();
        a.tidur();
        a.makan();
        
        Harimau b = new Harimau();
        b.tidur();
        b.makan();
        
        }
    }

