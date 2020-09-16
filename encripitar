

public class cript {
public static String criptar(int chave, String texto){
    // Variavel que ira guardar o texto crifrado
    String textoCifrado = ""
    // Variavel com tamanho do texto a ser encriptado
    int tamanhoTexto = texto.length();
    int letraCifradaASCII;
   
    // Criptografa cada caractere por vez
    for(int c=0; c < tamanhoTexto; c++){
        // Transforma o caracter em codigo ASCII e faz a criptografia
        // não criptografa espaço.
        int letranormal = ((int) texto.charAt(c));
        if (letranormal != 32)
        	
            letraCifradaASCII = ((int) texto.charAt(c)) + chave;
        else
            letraCifradaASCII = ((int) texto.charAt(c));
       
        // Verifica se o codigo ASCII esta no limite dos caracteres imprimiveis
        while(letraCifradaASCII > 126)  {
            letraCifradaASCII = 94;
        }
        // Transforma codigo ASCII criptografado em caracter ao novo texto
        textoCifrado = textoCifrado + (char)letraCifradaASCII;
    }
    
   
   
    // Por fim retorna a mensagem criptografada por completo
    return textoCifrado;
    
    
}
}
