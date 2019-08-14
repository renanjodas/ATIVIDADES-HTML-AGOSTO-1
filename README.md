# ATIVIDADES-HTML-AGOSTO-1
Atividade HTML 

### Descrição da atividade:

- Criar um repositório para todas as atividades criadas com o nome: ATIVIDADES-HTML-AGOSTO-1  
- Entregar o repositório  
- Você deve criar as páginas em html com o visual igual ao apresentado nos arquivos de referência  
- As imagens necessárias estão junto com a atividade. Para imagens de redes sociais você pode utilizar a imagem que quiser  
- Aonde existir link você pode direcionar para qualquer site(são apenas ilustrativos)  


### Comandos Utilizados:  

* \<header>\</header> -  elemento <header> representa um contêiner para conteúdo introdutório ou um conjunto de links de navegação. Geralmente contém:  

   Obs: Uma tag \<header> não pode ser colocada dentro de um \<footer>, \<address> ou outro elemento \<header>.  
Ex. 

 ```html
      <header>
           Usuário logado: Renan
           <a href="index.html">Sair</a>
       </header>

 ```
 ---  
 * \<footer>\</footer> - define um rodapé para um documento ou seção. Um elemento \<footer> deve conter informações sobre seu elemento contido. Geralmente contém:  

. informação de autoria  
. Informações sobre direitos autorais  
. informações de contato  
. sitemap  
. voltar ao topo links  
. documentos relacionados  
Você pode ter vários elementos \<footer> em um documento.  
 Ex.:
 
 ```html
       <footer>
            <p>**Este é apenas um site experimental fake. Todos os projetos apresentados não são reais</p>
            <p>&copy; Criado por <a href="https://www.linkedin.com/in/renanjodas/" target="blank">mim mesmo</a></p>
        </footer>
 ```  
 ---  
 * form - Tag para indicar formulario  
* action - ação do formulário (ação de enviar para banc - tag para inserção de link (externo ou local)  
 Ex.:
 ```html
  <form action="cadastro.php" method="POST">
 ```
 ---  
 * label - indica um rótulo(legenda)  
 * input - insere uma caixa de texto para “entrar/inserir” com algum dado/informação/texto  
   name - como sera chamada esta caixa | id - identificação (tipo variavel - direcionar) | maxlength - limite de caracteres   
 Ex.:
 ```html
  <label for="profissao">Profissão *</label>
            <input type="text" name="profissao" id="profissao" required>

 ```  
 ---  
 * Comando   \‘&copy;’ - insere símbolo copyright 
 
  Ex.:
 ```html
  <p>&copy; Criado por <a href="https://www.linkedin.com/in/renanjodas/" target="blank">mim mesmo</a></p>
 ```  
 ---  
  * placeholder - Define a ajuda para o usuário preencher o campo com os dados corretos  
  Ex.:
 ```html
  <input type="text" name="nome" id="nome" placeholder="Nome" required>
 ```  
 ---  
 * method e \‘value’ POST - para, ao clicar em enviar, na URL não apareça os dados enviados pelo form (como a senha)  
 Ex.:
 ```html
  <form action="cadastro.php" method="POST">
 ```  
 ---   
 * required - no input, torna o campo obrigatório.  
 Ex.:
 ```html
  <label for="nome">Nome: </label> 
                    <input id="nome" name="nome" maxlength="20" placeholder="Nome" required> 
 ```  
 ---   
 * select - cria caixa de seleção  
 * option - define a lista de opções da caixa de seleção  
 Ex.:  
 ```html
    <select name="pretensaoSalarial"> 
         <option>R$ 2000,00 - R$ 3000,00</option>
         <option>R$ 0,00 - R$ 1000,00</option>
         <option>R$ 3000,00 - R$ 4000,00</option>
    </select>
 ```   
 ---   
 * textarea - cria uma área de texto  
 * rows - atributo da text area, para definir quantidade de linhas  
 Ex.:  
 ```html
    <textarea rows="2"> </textarea>
```   
---  
  ### Author
 [Renan Dias Jodas](https://br.linkedin.com/in/renanjodas)

