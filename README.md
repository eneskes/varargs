# varargs
public static void main(String[] args) {
        
        int sayi=5;
        String str1="Zulal";
        String str2="Zeynep";
        String str3="Ali";
        carpim(sayi, str1,str2,str3);
       
    }
    private static void carpim( int sayi, String... str ) {
        String enUzunStr="";
        for (String each: str
        ) {
            if (each.length()>enUzunStr.length()){
                enUzunStr=each;
            }
        }
        System.out.println("Istenen deger : " + sayi * enUzunStr.length());
            }
        }
