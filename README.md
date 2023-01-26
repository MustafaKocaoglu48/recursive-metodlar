# recursive-metodlar
----
### Kendisine parametre olarak gelen sayının faktöriyelini alan ve ekrana yazan recursive metodu yazınız.
````
 static int carp=1;  
         public static void faktoriyel2(int a){
              
             if(a<=0){
                 System.out.println(carp);
                 System.exit(0);
            
                 } else{
                     carp=a*carp;
                     faktoriyel2(--a);
             }
         }

````
### Kendisin eparametre olarak gelen sayı kadar adımızı yazan recursive metodları yazınız.
````
  public static void yaz(int a){
             if(a<=0)System.exit(1);
             else{
                 System.out.println("Mustafa");
             }yaz(--a);
         }

````
### Kendisine parametre olarak gelen sayıya kadar olan sayıların toplamını geri döndüren recursive metodu yazınız.
````

 static int toplam=0;
         public static void topla10(int d){
             if(d<=0){
                 System.out.println(toplam);
                 System.exit(1);
             }else{
                 toplam+=d;
             topla10(--d);}
         }
````
### Kendisine parametre olarak gelen iki sayı arasındaki sayıları toplayıp geri döndüren recursive metodu yazınız.
````
   public static void ikitopla(int a,int b){
             if(b<=a){System.out.println(toplam);
             System.exit(1);
             }else{
                     toplam+=b;
                     ikitopla(a,--b);
                     }
         }
````
### Kendisine parametre olarak gelen stringin içindeki küçük harfleri bulan ve ekrana yazan recursive metodu yaznınız.
````
   public static void kucukbul(String a,int i){
             if(i>=a.length())System.exit(1);
             else{
                 if(a.charAt(i)>='a' && a.charAt(i)<='z'){
                     System.out.println(a.charAt(i));
                 }kucukbul(a,++i);
             }
         
````
### Kendisine parametre olarak gelen dizi içindeki en büyük sayıyı bulup geri döndüren metodu yazınız.
````
  static int enb=0;
         public static int dizi(int a[],int i){
                 if(i>=a.length){
                     return enb;
               System.exit(1);
                 }
                 else{
                     if(enb<a[i])enb=a[i];
                   dizi(a,++i);
                 } 
         }
````
