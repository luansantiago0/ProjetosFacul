public class descript {
	 public static String decriptar(int chave, String textoCifrado)  {
	        // Variavel que ira guardar o texto decifrado
	        String texto = "";
	        // Variavel com tamanho do texto a ser decriptado
	        int tamanhoTexto = textoCifrado.length();
	        int letraDecifradaASCII=0;
	        
	        // Descriptografa cada caractere por vez
	        for(int c=0; c < tamanhoTexto; c++){
	            // Transforma o caracter em codigo ASCII e faz a descriptografia
	            int letracifradaASCII = (int) textoCifrado.charAt(c);
	            if (letracifradaASCII != 32)
	                letraDecifradaASCII = ((int) textoCifrado.charAt(c)) - chave;
	            else
	                letraDecifradaASCII = ((int) textoCifrado.charAt(c));
	            
	            // Verifica se o codigo ASCII esta no limite dos caracteres imprimiveis
	            while(letraDecifradaASCII < 32)
	                letraDecifradaASCII += 94;

	 

	            // Transforma codigo ASCII descriptografado em caracter ao novo texto
	            texto = texto + (char)letraDecifradaASCII ;
	        }
	        
	        // Por fim retorna a mensagem descriptografada por completo
	        return texto;
	    }

}
