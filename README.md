# Tripleten web_project_homeland

## Nome do Projeto:

De Pátria para Pátria

## Descrição do Projeto:

O website "De Pátria para Pátria" é uma plataforma que apresenta histórias de pessoas de diferentes partes do mundo, dedicando-se a criar uma comunidade acolhedora para futuros profissionais de tecnologia. O projeto destaca a diversidade cultural e a jornada épica de cada indivíduo, desde lugares como Kentucky, Burundi, País de Gales e Ucrânia. Ele encoraja os visitantes a compartilhar suas próprias histórias e criar obras visuais que representem suas cidades natais, tornando-se uma galeria colaborativa de arte e cultura global. A página central inclui um texto inspirador e uma imagem de um vilarejo representando a conexão com o local de origem.

## Tecnologias e Técnicas utilizadas:

1. HTML5
   O documento é escrito em HTML5, que é a versão mais recente da linguagem de marcação utilizada para estruturar o conteúdo da web. O uso do <!DOCTYPE html> declara que o documento segue o padrão HTML5, proporcionando compatibilidade com navegadores modernos.

2. Metadados
<meta charset="UTF-8">: Define a codificação de caracteres para UTF-8, garantindo suporte a caracteres especiais, como acentos e símbolos.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Responsável por garantir que o site seja responsivo, ajustando-se automaticamente para diferentes tamanhos de tela, como celulares e tablets.
<meta name="description"> e <meta name="keywords">: Essas tags ajudam na otimização para motores de busca (SEO), descrevendo o conteúdo da página e as palavras-chave associadas.
<meta name="author">: Informa o nome do autor da página, no caso, João Luiz Cambraia.

3. CSS Externo
<link rel="stylesheet" href="./pages/index.css">: Conecta o documento HTML a uma folha de estilo CSS externa, que define a aparência e o layout da página. Essa abordagem modulariza o código, separando o conteúdo (HTML) da apresentação (CSS).

4. Imagens e Favicon
   Imagens: O código utiliza duas imagens (logo_tripleten-art-galery.svg e header_image.jpg) para fornecer um logotipo e uma imagem de cabeçalho. As tags <img> incluem atributos alt para acessibilidade e SEO, descrevendo o conteúdo das imagens para leitores de tela e mecanismos de busca.
   Favicon: O favicon é configurado através de <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">, que adiciona um pequeno ícone à aba do navegador.

5. Estrutura Semântica
<header>, <main>, <section>, <footer>: O código usa tags semânticas do HTML5 para estruturar o conteúdo de forma lógica e acessível. Por exemplo:
<header>: Contém o logotipo, título, subtítulo e imagem de cabeçalho.
<main>: Abriga o conteúdo principal da página.
<section>: Agrupa o conteúdo da introdução.
<footer>: Exibe as informações de rodapé, incluindo o copyright.

6. Responsividade
   A inclusão da tag viewport no <meta> é crucial para tornar a página responsiva, ou seja, capaz de ajustar o layout dependendo do tamanho da tela do usuário. Isso é uma boa prática em design moderno, onde muitos acessam a web de dispositivos móveis.

7. Acessibilidade
   O uso de alt nas imagens garante que as descrições alternativas sejam fornecidas para usuários de leitores de tela, melhorando a acessibilidade da página.
   A estrutura semântica também contribui para uma navegação mais fácil para pessoas com deficiências visuais que utilizam tecnologias assistivas.

8. Boas Práticas de SEO
   As metatags como description e keywords, além das tags de cabeçalho como <h1>, <h2>, ajudam na otimização da página para motores de busca, melhorando a relevância e a classificação da página nos resultados de pesquisa.
   O título da página, <title> De Pátria para Pátria, é outro fator importante para SEO, informando o tema principal do site.

9. Uso de Citações
   O trecho com a frase de Joseph Beuys utiliza tags <span> para estilizar a citação e destacar o nome do autor. Embora seja uma técnica simples, é útil para controle de estilo ao aplicar CSS.

10. Organização Modular
    A organização modular do código, separando o CSS externo do HTML, segue o princípio de separação de preocupações, uma boa prática em desenvolvimento web que facilita a manutenção e reutilização do código.

## Link para o GitHub Pages:

O site está disponível no GitHub Pages: [Clique aqui para acessar](https://jlcambraia.github.io/web_project_homeland/)

## Planos de Melhoria:

1. Melhoria na identidade visual: Incorporar elementos gráficos mais ricos e atraentes que representem os diferentes países e culturas, como mapas, bandeiras ou símbolos característicos.

2. Aprimorar a navegação: Implementar uma barra de navegação simplificada com ícones e categorias claras (ex.: "Histórias", "Galeria de Arte", "Participe").

3. Formulário de contribuição de histórias: Adicionar uma área onde os visitantes possam facilmente compartilhar suas próprias histórias de forma mais estruturada, com opções para anexar imagens, vídeos ou áudios.

4. Galeria expandida: Incluir a possibilidade de explorar as histórias por meio de uma galeria visual, onde cada contribuição pode ser exibida com uma imagem, história breve e localização no mapa.

5. Facilitar o compartilhamento das histórias nas redes sociais diretamente do site, utilizando botões visíveis e links integrados.
