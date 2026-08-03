## Questão 1 – Conceito (Fácil - Resolução)

<p>O WAI-ARIA(Web Accessibility Initiative – Accessible Rich Internet Applications) é uma modelo de web criado especialmente para melhorar acessibilidade de pessoas com certas dificuldades, podem ser física, auditiva, visual, e mental gerando uma página acessível, sua existência surgiu pela dificuldade que o Html em seu modelo comum era dividido em <strong>div</strong> fazendo que a ferramenta seja ineficaz, pois não tem como identificar o item.</p>

## Questão 2 – Interpretação (Médio - Resolução)

```<button
    class="navbar-toggler"
    type="button" 
    aria-controls="menuPrincipal"
    aria-expanded="false"
    aria-label="Abrir menu">
    Menu
</button>
```
(A - Resolução)

<p>O <strong>aria-control</strong> serve para identificar e vincular o botão para controlar dentro da página em uma Menu suspenso.</p>

(B - Resolução)

<p>O comando<strong>aria-expanded="false"</strong> é feito para vincular a um item expansivo e <stong>false</stong> é uma varíavel booleana e realiza uma acão que é a de desativado o item em expansão, caso esteja <strong>true</strong> o item estar expandido.  </p>

(C - Resolucão)

<p>O atributo <strong>aria-label</strong> fornece um texto descritivo personalizado para leitores de tela, substituindo o conteúdo visível do botão quando este não é suficientemente claro, garantindo que usuários cegos ou com baixa visão entendam a função do elemento mesmo sem contexto visual</p>

## Questão 3 – Reflexão (Difícil - Resolução)

<p>O WAI-ARIA não substitui o HTML semântico porque os elementos nativos já trazem comportamentos, estados e funções embutidos para acessibilidade, enquanto o ARIA apenas adiciona informações extras; usá-lo em vez de HTML semântico pode gerar inconsistências e falhas em leitores de tela.
Uma situação necessária é quando se cria um componente personalizado, como um <strong>slider</strong> ou menu suspenso feito com <strong>div</strong> e JavaScript, que não possui equivalentes semânticos nativos; nesse caso, usamos <strong>role="slider"</strong>, <strong>aria-valuenow</strong> e aria-expanded<strong>aria-expanded</strong> para transmitir função, estado e interatividade que o HTML puro não oferece.</p>
