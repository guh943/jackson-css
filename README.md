#1 Estrutura HTML:
a pagina possui cabeçalho('header'), um menu de navegação('nav'), um botão para ocultar/mostras o menu lateral,um container principal('container') que usa grid layout, um menu lateral
('aside'), ua area de conteudo principal('main') e um rodapé('footer') 
#2 CSS:
  -'display:flex É usado no menu de navegação ('nav') para distribuir os links horizontalmente.
  -'display:grid É usado no conteiner principal ('container') para criar uma grade com duas colunas.
  -display:blocl É usado nos itens da grade('gride-item') para garantir que ocupem toda a largura disponivel dentro de suas celulas da grade.
  -display:inline-block É usado em elementos 'inline-block' para que sejam exibidos em linhas, mas ainda permitam definir largura e altura.
  -display:none É usado na classe 'hidden' para ocultar o menu lateral quando necessario.
  #3 JAVA SCRPIT:
  A função 'toggleMenu()' é usada para adicionar/remover a classe 'hidden' no menu lateral('aside') ocultando ou mostrando o menu conforme necessario
