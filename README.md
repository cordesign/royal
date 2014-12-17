# COR(x)DESIGN Proposta de Website Serviço para expor produto  
INTRODUÇÃO Website consistente de um logo fixo no canto superior esquerdo (com um link para o topo da página), uma barra de navegação com três itens (about us, our products, contact us), uma versão ‘enlarged’ do logo com uma hiperligação para a zona about. A seguir, uma imagem de fundo com uma máscara em forma de um ‘X’. Directamente por baixo está a zona About Us com uma imagem representativa da nossa personaliade e um texto. Por fim a zona Contact Us que contêm uma imagem, a nossa localização, uma zona para deixar comentário e os botões das redes sociais. 
O website foi feito com o propósito de ser usado como uma forma de promover o artigo desenvolvido e produzido por mim e por uma colega de Guimarães. O nome provisório do sapato é ‘Shorn’. É dada a possibilidade de acrescentar mais artigos caso seja preciso.

#ADAPTÁVEL 
O website foi criado tendo em mente a possíbilidade de o alterar conforme for preciso. Através da framework SASS foi possível definir variáveis como cor do texto e cor do fundo no css. Com a implentação da framework Liquid foi possível separar o website em partes que podem ser alteradas sem alterar a integridade do website e por fim foram acrescentados comentários entre parte de código, 
Além de adaptável o website também é ‘responsive’ podendo ser visulizado tanto em ecrãs pequenos como grandes. A grelha é alterada quando o ecrã do disposito é maior/menor que 768px de largura.  
LINK - http://cordesign.github.io/royal/ 
REPOSITÓRIO - https://github.com/cordesign/royal        
 
# HTML5 
Através desta linguagem de programação foram implementados aspectos relaccionados com a estética do website tal como animações interactivas e, como já referido, o ‘responsiveness’  
CSS3 Através desta linguagem de programação foram implementados aspectos relaccionados com a estética do website tal como animações interactivas e, como já referido, o ‘responsiveness’. 
Exemplo: 
@media(min-width:768px) { 
    .navbar-fixed-top { 
        padding: 25px 0; 
        -webkit-transition: padding .3s; 
        -moz-transition: padding .3s; 
        transition: padding .3s; 
            color: #3f6056; 
    }.  
# JAVASCRIPT 
Inicialmente tinha usado Javascript para a implementação do Google Maps entretanto decidi contra essa característica removendo completamente os mapas. 
Além do javascipt que é incluído com o framework bootstrap foi usado para o smooth scroll e para o scrollspy, uma função que faz com que o scroll entre links na mesma página seja feito de maneira suáve. 
ELEMENTOS ADICIONAIS  • Os microdados utilizados da semântica do HTML5 foram o <header> e <section> em que a identificação do <section> altera de secção para secção. 
• O HTML5 foi escrito por ordem lógica de forma a habilitar pessoas com ‘visual imparments’ a usarem ferramentas de leitura de website. 
• Plugins HTML5/JavaScript que foram utilizados foram o smooth scroll e o scrollspy 
• Em CSS foram acrescentado Media Querys que detactam se o dispositivo do utilizador é superior ou inferior a 768px, adaptando o conteúdo. 
• Na secção About Us tem uma imagem que ao clicar nos leva a uma base de dados nãorelacional que nos possíbilita acrescentar comentários ao website.   
 
 
#CONCLUSÃO 
Na elaboração deste website aprendi muito acerca de vários assuntos relaccionados com as tecnologias da internet. Em especial a usar a libraria Angular.js, as Media Querys mas mais importante, criei um workflow que faz possível a criação de websites de forma mais eficiente e mais rápida do que alguma vez pensei conseguisse. 
Alimentou a minha curiosidade pela tecnologia e vontade de conhecer novas coisas relacionadas. 