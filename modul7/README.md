
# Modul 7







## Latihan 771a

public class latihan771 {

public static void main(String[] args){

 String[] hari = {"senin", "selasa", "rabu", "kamis", "jum'at", "sabtu", "minggu"};   
 
 System.out.println("Hari Dalam Seminggu:");
 
    int i = 0;
    
 while(i<hari.length){
 
     System.out.println(hari[i]);
     
     i++;
     
 }
 
}
}

Program ini mencetak hari-hari dalam seminggu menggunakan perulangan while dengan menggunakan array.

## Latihan 771b

public class latihan771b {

public static void main(String[] args){

    String[] hari = {"Senin", "Selasa", "Rabu", "Kamis", "Jum'at", "Sabtu", "Minggu"};
    
    System.out.println("Hari Dalam Seminggu:");
    
    int i = 0;
    
    do{
    
        if(i<=hari.length){
        
            System.out.println(hari[i]);
            
            i++;
            
        }
        
    }while(i<hari.length);
    
}
}

Program ini mencetak hari-hari dalam seminggu menggunakan perulangan do-while dengan menggunakan array.
## Latihan 771c

public class latihan771c {

public static void main(String[] args){

    String[] hari = {"Senin", "selasa", "Rabu", "Kamis", "Jum'at", "Sabtu", "Minggu"};
    
    System.out.println("Hari Dalam Seminggu:");
    
    for(int i=0; i<hari.length; i++){
    
        System.out.println(hari[i]);
        
    }
    
}
}

Program ini mencetak hari-hari dalam seminggu menggunakan perulangan for dengan menggunakan array.





## Latihan 772a

import java.io.BufferedReader;

import java.io.InputStreamReader;

import java.io.IOException;

import java.util.Arrays;

import java.util.logging.Level;

import java.util.logging.Logger;

public class latihan772 {

public static void main(String[] args){

    BufferedReader data = new BufferedReader(new InputStreamReader(System.in));
    
 int[] nilai = new int[10];
 
 int i,max,imax;
 
 max =0;
 
 imax = 0;
 
 System.out.println("== Masukan Nilai ==");
 
        try {
        
             for(i=0;i<10; i++){
             
            System.out.print("masukan nilai ke-"+(i+1)+" =");
            
            nilai[i] = Integer.parseInt(data.readLine());    
            
            }
            
             //for(i=0;i<10;i++){
             
             //System.out.println("array yang diinputkan:"+nilai[i]);
             
             //}
             
          for(i=0;i<10;i++){
          
          
          if(nilai[i]>max){
          
                  max = nilai[i];
                  
                  imax = i;
                  
              }
              
          }   
          
          System.out.println("== Hasil Data Nilai ==");
          
          System.out.println("array yang diinputkan:"+Arrays.toString(nilai));
          
          System.out.println("nilai terbesar adalah: "+max);
          
          System.out.println("nilai terbesar ada pada baris ke: "+(imax+1));
          
     }
     
        catch (IOException ex) {
        
            Logger.getLogger(latihan772.class.getName()).log(Level.SEVERE, null, ex);
            
 }
 
}
}

Program di atas adalah contoh pemrograman Java yang meminta pengguna untuk memasukkan 10 nilai, mencari nilai terbesar di antara nilai-nilai tersebut, dan menampilkan hasilnya.
## Latihan 772b

import java.util.Arrays;

import javax.swing.JOptionPane;

public class latihan772b {

public static void main(String[] args){

   int[] nilai = new int[10];
   
   int i,max,imax;
   
   max = 0;
   
   imax = 0;
   
   for(i=0;i<10;i++){
   
       nilai[i] = Integer.parseInt(JOptionPane.showInputDialog("nilai ke-"+(i+1)));
       
   }
   
   for(i=0;i<10;i++){
   
      if(nilai[i]>max){
     
          max = nilai[i];
          
          imax = i;
          
      }
      
   }
JOptionPane.showMessageDialog(null,"\n nilai yang didapatkan "+Arrays.toString(nilai)+

       "\n nilai terbesar :"+max+"\n nilai terbesar terdapat pada baris ke-"+(i));
}

}

Program di atas adalah contoh pemrograman Java yang meminta pengguna untuk memasukkan 10 nilai menggunakan dialog input JOptionPane, mencari nilai terbesar di antara nilai-nilai tersebut, dan menampilkan hasilnya menggunakan dialog pesan JOptionPane. 
## Latihan 773

public class latihan773 {

public static void main(String[] args){

    String[][] entry =  {{"Florence", "735-1234", "Manila"},         
    
                        {"Joyce", "983-3333", "Quezon City"},
                        
                        {"Becca", "456-3322", "Manila"}}; 
                        
    //int i,j;
    
    //for(i=0;i<entry.length;i++){
    
      //  for(j=0;j<entry.length;j++){
      
        //    System.out.println("Name : "+entry[i][j]);
        
        //}
        
    //}
    
    System.out.println("Name : "+entry[0][0]);
    
    System.out.println("Tel : "+entry[0][1]);
    
    System.out.println("Address : "+entry[0][2]);
    
    System.out.println("\n");
    
    System.out.println("Name : "+entry[1][0]);
    
    System.out.println("Tel : "+entry[1][1]);
    
    System.out.println("Address : "+entry[1][2]);
    
    System.out.println("\n");
    
    System.out.println("Name : "+entry[2][0]);
    
    System.out.println("Tel : "+entry[2][1]);
    
    System.out.println("Address : "+entry[2][2]);
    
}
}

Program di atas menggunakan array 2 dimensi untuk menyimpan informasi tentang beberapa entri:\
Deklarasi dan inisialisasi array: Array 2 dimensi "entry" dideklarasikan dan diinisialisasi dengan beberapa entri yang terdiri dari nama, nomor telepon, dan alamat. Setiap baris dalam array mewakili satu entri. Misalnya, entri pertama memiliki nilai "Florence" untuk nama, "735-1234" untuk nomor telepon, dan "Manila" untuk alamat.

Cetak informasi:\
 Program mencetak informasi entri menggunakan pernyataan "System.out.println()". Setiap baris mencetak informasi nama, nomor telepon, dan alamat dari setiap entri secara terpisah. Misalnya, baris pertama mencetak nama, nomor telepon, dan alamat dari entri pertama, baris kedua mencetak informasi entri kedua, dan seterusnya.
