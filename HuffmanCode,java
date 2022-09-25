//attempt at huffman coding Albert Ruehlman
import java.util.*;


class Main {

    public static void main(String[] args) {
      
      generate("hello myu naye is albert ");

    }


    public static void generate(String p){
      String[] alphabet = {"a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y","z", " "};//alphabet

    String a = "";
    for (String n:alphabet)
        a+= n;
    char[] alpha = a.toCharArray();//dude remember how this converts string to char  but anyways this converts alphabet into a char array

      
      
      String str = p;
      char[] inputCharacters = str.toCharArray();//turns input into char array
      int[]weight = new int[54];//weight array
      int n = 0;
      for(int i = 0; i<54; i+=2){
        
        weight[i] = n;
        weight[i+1] = 0;
        n = n+1;
        System.out.print(weight[i]);
        System.out.print(weight[i+1]);
        
      }//fills weight array with the values of alphabet
      System.out.println("");


      for(int i = 0; i<p.length(); i++){
        for(int x = 1; x<28; x++){
            if(alpha[x-1] == inputCharacters[i]){
              weight[x*2-1]++;
              }
        }
      }
      

      
      
for(int i = 1; i<28; i++){
  System.out.println(alphabet[i-1] + ": " + weight[i*2-1]);
}




      
        
      
    ArrayList<String> compressed = new ArrayList<String>();//output of binary compression
    

  }//generation of binary form
  
}
