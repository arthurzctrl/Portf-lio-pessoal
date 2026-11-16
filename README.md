# Portfólio Acadêmico e Profissional - Engenharia de Automação

## Nome do Aluno
Arthur Zana Côrtes (Prontuário: CT3037193)

## Descrição do Portfólio
Este portfólio web foi desenvolvido para apresentar minha trajetória acadêmica e meus principais projetos desenvolvidos no curso de **Engenharia de Controle e Automação**. A página reúne informações sobre meu perfil, competências técnicas e desenvolvimentos práticos em robótica, sistemas embarcados e automação.

## Tecnologias Utilizadas
- **HTML5 e CSS3** (Estruturação e estilização customizada)
- **Bootstrap 5** (Framework CSS para responsividade, grid system e componentes)
- **JavaScript (ES6)** (Manipulação dinâmica de elementos e controle de tema)
- **FontAwesome** (Ícones vetoriais)
- **GitHub Pages** (Hospedagem e publicação do site)

## Link do Site Publicado
[https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/](https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/) *(Substitua pelo seu link real do GitHub Pages)*

## Explicação do Funcionamento do Projeto
O site adota uma estrutura de página única (*Single Page Application*) com rolagem suave (*smooth scroll*). A navegação superior fixa permite ao usuário acessar instantaneamente as seções de **Perfil**, **Habilidades**, **Projetos** e **Contato**. O layout é totalmente responsivo, adaptando-se perfeitamente a dispositivos móveis, tablets e computadores de mesa através do sistema de grades do Bootstrap.

## Descrição do Recurso Novo Adicionado
Como recurso novo e diferencial (além do conteúdo base visto em sala), foi implementado um **Sistema Interativo de Alternância de Tema (Dark/Light Mode com transições suaves)** e efeitos visuais dinâmicos de elevação (*hover effects*) nos cards de projetos e ícones de habilidades.

## Explicação de Como Esse Recurso Foi Implementado
1. **Atributo nativo do Bootstrap 5 (`data-bs-theme`):** A tag `<html>` foi configurada para aceitar dinamicamente o atributo `data-bs-theme="light"` ou `"dark"`.
2. **Função JavaScript (`toggleTheme()`):** Um botão interativo na barra de navegação chama uma função JavaScript que alterna o atributo do documento e troca o ícone do botão (Lua/Sol) em tempo real.
3. **Transição CSS:** Foi adicionada a propriedade `transition: background-color 0.4s ease, color 0.4s ease;` no seletor `body` para garantir que a mudança de cores ocorra de forma fluida, sem cortes bruscos, elevando a experiência visual do usuário.
