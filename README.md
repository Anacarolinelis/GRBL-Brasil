# GRBL Brasil - Site Institucional

## Descrição

Este é o site institucional da GRBL Brasil, líder em tecnologias de fabricação digital, especializada em máquinas de corte a laser diodo, CNC Routers e impressoras 3D. O site inclui uma página inicial, uma página de produtos com um carrossel de imagens, uma página de contatos e uma seção "Quem somos".

**Nota:** Este site foi criado como parte de um trabalho acadêmico. Algumas informações sobre a empresa são fictícias e foram utilizadas apenas para fins educacionais.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

.
├── index.html
├── produtos.html
├── contatos.html
├── styles.css
└── README.md

less
Copiar código

### index.html

A página inicial do site, com informações básicas sobre a empresa e links para as outras páginas.

### produtos.html

A página de produtos, que apresenta um carrossel de imagens de produtos e informações detalhadas sobre cada um.

### contatos.html

A página de contato, que fornece informações sobre como entrar em contato com a empresa.

### styles.css

O arquivo de estilos CSS que define a aparência e o layout do site.

## Tecnologias Utilizadas

- HTML5
- CSS3
- Bootstrap 5

## Instruções de Uso

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:
bash
Copiar código
cd nome-do-repositorio
Abra o arquivo index.html em seu navegador para visualizar o site.
Estilização
O arquivo styles.css contém a estilização personalizada do site. Aqui estão algumas das principais customizações:

Barra de Navegação
A barra de navegação inclui links para as páginas "Home", "Produtos" e "Contato".

Carrossel de Imagens
O carrossel de imagens na página de produtos exibe imagens de produtos com indicadores e controles para navegação entre as imagens.

Cartões de Produtos
Os cartões de produtos na página de produtos incluem uma imagem centralizada com borda e informações detalhadas sobre cada produto.

Rodapé
O rodapé inclui informações de copyright da empresa.

Personalizações
Fundo da Página de Produtos
Para alterar a cor de fundo da página de produtos, adicione a seguinte linha ao arquivo styles.css:

css
Copiar código
body.produtos {
    background-color: #sua-cor-desejada;
}
E certifique-se de que o <body> da página produtos.html tenha a classe produtos:

html
Copiar código
<body class="produtos">
Borda das Imagens dos Produtos
Para adicionar uma borda às imagens dos produtos, adicione o seguinte ao arquivo styles.css:

css
Copiar código
.card-img-top {
    border: 2px solid #ffffff; /* Ajuste a cor e a espessura da borda conforme necessário */
    border-radius: 5px; /* Ajuste o raio da borda conforme necessário */
}
Contato
Para mais informações, entre em contato com o autor do projeto.

Licença
Este projeto é licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.

perl
Copiar código

Este `README.md` foi formatado para garantir que você possa copiá-lo e colá-lo diretamente 
