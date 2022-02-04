# caculadora-raiz-quadrada-
Calculadora com resultados de raiz quadrada, ao cubo entre outras.
Em
# Calculadora na linguagem Java, reprodução do exercício pratica do curso em vídeo.

A calculadora tera o codigo específico, para gerar soluções predeterminadas.
# Resto da divisão por 2
# Elevado ao cubo
# Raiz quadrada
# Raiz cúbica 
# Valores absoluto

# Organização do projeto

O projeto foi desenvolvido na linguagem Java e utilizado o NetBeans IDE.
As pastas "classes/pacotes" seram abertas separadamente: classes, imagens e Jframe.

# Criando o ambiente Front do projeto

Sera utilizado 2 labeis principais uma para a imagem da calculadora e outro para o botão de soma, e 10 labeis sendo cinco ao lado esquerdo que representarar as "perguntas ou regras" e cinco a direita representando os resultados.

# Pastas e nomes

Nomear os labeis com os mesmos nomes que sera lansado no código, importe as pastas com as imagens e faça as substituição com os nomes devidos 1 botão calculo, 1 imagens calculadora, 5 soluções especificas e 5 resultados sendo pares de soluções.

# ou visível
Em
Para as soluções Pan visiveis se utiliza (true).setVisible(true); 
Para as soluções ficarem invisíveis se utiliza (panCalc.setVisible(falsfalse);)
PanCalc é o nome dado para as "classes" que determinam as especificações/soluções.

# metodos 

para criar um metodo para o clic do botão calcular, clica no label que esta a imagem inportada do botão calc, clica em (eventos, action,actionPerformed) 

# Código

int num = Integer.parseInt(TxtNum.getValue().toString());

//resto da divisão por 2
int r = num %2;
lblRest.settext(integer.toString(r));

//Elevado oao cubo
double c = Math.pow(num,3);
lblcubo.setText(Double.toString(rq));

//Raiz quadrada
double rg = Math.sqrt(num);
lblRaizQ.setText(String.format("%.2f",rq))
 //"%.2f" representa 2 casas decimais 
 
 //Raiz cibuca
 double rc = Math.cbrt(num);
 lblRaizC.setText(String.format("%.2f", rc));
 
 //Valor absoluto
 int abs = Math.abs(num);
 lblabs.setTextInteger.rtoString(abs));
 
 Obs: resultado/teste/conclusão 


