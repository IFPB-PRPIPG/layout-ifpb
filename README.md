#Grid (12 colunas)
- xs-1 
- mid-1 
- large-1 

#Caixas

###Caixa de texto
.text-box (usar se não houver background)
  .header-title (.default for blue color)
    .mid-size
    .large-size
  .header-subtitle

###Caixa de conteúdo (news, articles)
.content-box
  .header-box
    h3 [title]
  .footer-box

#Bordas
.boder-box [Fim da caixa]
.border-title-light [A baixo do titulo, light]


#Listas
- text-list
  --.text-list-item [-header || -indent]
  --.text-list-item-header
  --..text-list-item-simple-header [no-boder-no-spaces]
  --.text-list-item-indent

- .date-list
  - .date-list-item
    - .date [.year .hour]
    - .image
    - .text
