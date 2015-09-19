package stringsCaptureUser;
import java.io.BufferedReader;  
import java.io.FileReader;  
import java.util.StringTokenizer; 

public class stringsTeste {
 	  	  
	   public void arquivo() {  
	      String linha = null;  
	  
	      try {  
	         FileReader reader = new FileReader("C:/teste.txt"); //Localização do Arquivo  
	         BufferedReader leitor = new BufferedReader(reader);  
	         StringTokenizer st = null;  
	           
	         String primeiroCampo;         // Armazena dados do primeiro campo  
	         String segundoCampo;      // Armazena dados do segundo campo
	         	  
	         while ((linha = leitor.readLine()) != null) {  
	                                            
	              
	            // UTILIZA DELIMITADOR ; PARA DIVIDIR OS CAMPOS  
	            st = new StringTokenizer(linha, "/");  
	            String dados = null;  
	  
	            while (st.hasMoreTokens()) {  
	  
	               // Primeiro campo
	               dados = st.nextToken();  
	               primeiroCampo = dados;  
	                 
	               // Segundo campo
	               dados = st.nextToken();  
	               segundoCampo = dados;
	                 
	               System.out.println("Primeiro campo " + primeiroCampo);  
	               System.out.println("Segundo campo " + segundoCampo);	               
	            }  
	         }  
	         leitor.close();  
	         reader.close();  
	  
	      } catch (Exception e) {  
	         e.printStackTrace();  
	      }  
	   }  
	  
	   public static void main(String[] args) {  
	      stringsTeste t = new stringsTeste();  
	      t.arquivo();  
	   }
}
