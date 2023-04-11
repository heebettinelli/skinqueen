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

