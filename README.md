Alterações html skinqueen:
- Adicionei a tag -a href- para linkar o menu de todas as abas do site.

alterei a lista li para dt, para tirar numeraçao do menu

antes: 

      </li>
        <ul>
          <li id="homepage"><a href="homepage.html">Página inicial</a></li>
          <li id="equipe"><a href="equipe.html">Equipe</a></li>
          <li id="corporais"><a href="tratamentoscorporais.html">Tratamentos Corporais</a></li>
          <li id="faciais"><a href="tratamentosfaciais.html">Tratamentos Faciais</a></li>
          <li id="contatos"><a href="contatos.html">Contatos</a>
      </li>

      depois:

      <dl>
        <dd id="homepage"><a href="homepage.html">Página inicial</dd>
        <dd id="equipe"><a href="equipe.html">Equipe</dd>
        <dd id="corporais"><a href="tratamentoscorporais.html">Tratamentos corporais</dd>
        <dd id="faciais"><a href="tratamentosfaciais.html">Tratamentos faciais</dd>
        <dd id="contatos"><a href="contatos.html">Contatos</dd>
      </dl>


      Substitui a div menu por uma tag nav:

      antes: 
      <dl>
        <dt id="homepage"><a href="homepage.html">Página inicial</a></dt>
        <dt id="equipe"><a href="equipe.html">Equipe</a></dt>
        <dt id="corporais">
          <a href="tratamentoscorporais.html">Tratamentos corporais</a>
        </dt>
        <dt id="faciais">
          <a href="tratamentosfaciais.html">Tratamentos faciais</a>
        </dt>
        <dt id="contatos"><a href="contatos.html">Contatos</a></dt>
      </dl>


      depois:
      <nav>
        <a href="homepage.html">Página Inicial</a>
        <a href="equipe.html">Equipe</a>
        <a href="tratamentoscorporais.html">Tratamentos Corporais</a>
        <a href="tratamentosfaciais.html">Tratamentos Faciais</a>
        <a href="contatos.html">Contatos</a>
      </nav>

      com isso mudei o css de: 

      #homepage {
    text-align: left;

    

}

#equipe {
    text-align:left;
    

}

#corporais {
    text-align: center ;

}

#faciais {
    text-align: right ;

}

#contatos{ 
    text-align: right ;

}

para: 

nav > a {
    margin: 0px 40px 0px 40px;
    position: relative;
}


tirei: 

article > h3 {
    text-align: center;
    padding: 50px 100px 10px 100px;
}

e agrupei:

 article > h1, h3 {
    text-align: center;
    padding: 50px 100px;
}

tirei: 
article > p {
    text-align: justify;
}

