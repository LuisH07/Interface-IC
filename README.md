# Documentação do site Interface-IC

## Índice
1. Introdução
2. Configuração do Ambiente
3. Estrutura do Projeto
4. Tecnologias Utilizadas
5. Guia de Estilo
6. Componentes Principais
7. Responsividade
8. Manutenção e Atualizações

## 1. Introdução
O site **Interface-IC** foi desenvolvido para replicar a tela abaixo. Esta documentação fornece detalhes sobre a estrutura do projeto, as tecnologias utilizadas e orientações para manutenção e atualização. <br>
<br> ![InterfaceOF-IC](https://github.com/user-attachments/assets/fc620a66-f068-4139-9915-d1e98bf40a90)

## 2. Configuração do Ambiente
**Requisitos**
* Editor de Código: Visual Studio Code
* Controle de Versão: Git e Gituhub Desktop

**Passos para Configuração**
Clone o repositório: https://github.com/LuisH07/Interface-IC <br>
Abra os arquivos HTML e CSS no editor de texto para edição ou visualização.

## 3. Estrutura do Projeto
```
Interface-IC/                       #pasta do projeto
├── css/                            #pasta do css do site
│   └── style.css                   #arquivo css do site
│
├── fontawesome/                    #pasta para uso dos icones fontawesome
│   ├── css/                        #pasta do css dos icones
│   │   ├── all.css                 #arquivo css necessário para uso dos icones
│   │   └── ...                     #outros arquivos não utilizados
│   └── ...                         #outros componentes do fontawesome não utilizados
│
├── imagens/                        #pasta das imagens do site
│   ├── InterfaceOF-IC.png          #imagem de referência da tela 
│   ├── computer-icon.ico           #favicon do site
│   └── icon-logo.ico               #ícone da logo
│
├── paginas/                        #pasta das páginas do site
│   ├── ajuda1.html                 #arquivo html da página ajuda1
│   ├── ajuda2.html                 #arquivo html da página ajuda2
│   ├── botaoagenda.html            #arquivo html da página botaoagenda
│   ├── botaocelulas.html           #arquivo html da página botaocelulas
│   ├── botaoconfig.html            #arquivo html da página botaoconfig
│   ├── botaomeusdados.html         #arquivo html da página botaomeusdados
│   ├── botaooracao.html            #arquivo html da página botaooracao
│   ├── botaousuarios.html          #arquivo html da página botaousuarios
│   ├── cadastro1.html              #arquivo html da página cadastro1
│   ├── cadastro2.html              #arquivo html da página cadastro2
│   ├── config.html                 #arquivo html da página config
│   ├── oracao.html                 #arquivo html da página oracao
│   ├── pagamento1.html             #arquivo html da página pagamento1
│   ├── pagamento2.html             #arquivo html da página pagamento2
│   ├── top10.html                  #arquivo html da página top10
│   ├── user1.html                  #arquivo html da página user1
│   └── user2.html                  #arquivo html da página user2
│
├── .gitattributes                  #arquivo do github
│
├── LISENCE                         #licença do projeto
│
├── README.md                       #arquivo da documentação do site
│
└── index.html                      #arquivo html principal
```

## 4. Tecnologias utilizadas
Front-end: HTML e css

## 5. Guia de Estilo
* Tipografia: A fonte principal utilizada é Arial
* Cores: Referências da tela original

## 6. Componentes Principais
**Cabeçalho**  <br>
O cabeçalho contém a barra de navegação principal, o logotipo, nome e botoês principais, projetado com HTML e estilizado com CSS.

**Conteúdo Principal** <br>
Inclui informações importantes de cada página.

## 7. Responsividade
O site "Interface-IC" é compatível com monitores 1920px e menores, também para aparelhos móveis. Mostra uma única versão do site em todos os dispositivos.

## 8. Manutenção e Atualizações
**Correções de Bugs**
Registre os bugs na seção de Issues do GitHub.
