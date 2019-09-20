# CSS-Mobile-First
Flexibilidade na web com Layouts Fluídos

Medidas flexiveis

As duas flexíveis mais usadas são as porcentagens e o em. As porcentagens são usadas para especificar medidas de tamanho com relação ao tamanho do elemento pai.

Exemplos

body {
/* a página ocupa a largura da tela toda */
  width: 100%;
}
article {
  /* o article ocupa 3/4 da página */
  width: 75%;
  
  /* e tem uma margem interna de 10% do tamanho do pai */
  padding: 10%;
 }
 
 Também podemos usar porcentagens no font-size significando um tamanho de fonte relativo ao tamanho da fonte do elemento pai. O em tem esse mesmo significado para fontes um parágrafo com font-size de 200% ou 2em dá na mesma vai ser o dobro do tamanho de fonte do elemento pai.
 
 html {
    /* tem um font-size implícito que equivale a 16px na maioria dos navegadores */
}

p {
  /* título principal com o dobro da fonte base */
  font-size: 1.125em;
 }
 
 h1 {
  /* título principal com o dobro da fonte base */ 
  font-size: 2em;
 }
 
 h2 {
  /* título secundário é 50% maior que o valor base */ 
    font-size: 150%; /* equivalente a 1.5em */
   }
   
   O em tem a vantagem de poder ser usado em qualquer propriedade, mas sempre significar uma relação com o tamanho da fonte. Isso é bem útil quando a medida de algum elemento tem relação com texto, uma medida tipográfica.
   
   Se quiser fazer um espaçamento entre parágrafos, por exemplo, você, provavelmente, vai querer algo relacionado ao tamanho da fonte. Então, um  p { margin: 0 1em; } faz mais sentido que um p {margin: 0 5%; } --- com em, o espaçamento do texto muda proporcionalmente ao tamanho da fonte.
   
   p {
      font-size: 1.125em;
        /* margin será 18px, já que mudamos o tamanho do em para 1.125em */
        margin: 0 1em;
    }
    
    
 
