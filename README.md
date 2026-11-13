# Portfólio Profissional — Jefferson Borges Calaça

## Nome do Aluno
Jefferson Borges Calaça ([@JeffBorgs](https://github.com/JeffBorgs2026))

## Descrição do Portfólio
Projeto de portfólio pessoal responsivo desenvolvido para a disciplina de **Desenvolvimento de Sistemas I (Agenda 15 - ETEC)**. O objetivo do site é apresentar minha trajetória acadêmica multidisciplinar (Desenvolvimento de Sistemas, Gestão de Marketing, Design Gráfico e Segurança do Trabalho), minhas competências técnicas e os projetos desenvolvidos ao longo da formação.

## Tecnologias Utilizadas
* **HTML5:** Estruturação semântica da página e seções.
* **CSS3:** Estilização personalizada, ajustes de proporção do carousel e animações de transição.
* **Bootstrap 5.3.3:** Sistema de grid responsivo, barra de navegação colapsável (`navbar`), painel rotativo (`carousel`), cards e botões.
* **Devicon:** Biblioteca de ícones para representação visual das tecnologias e ferramentas.
* **Git & GitHub Pages:** Controle de versão e hospedagem gratuita do site na web.

## Link do Site Publicado
Acesse o portfólio online pelo GitHub Pages:  
👉 [https://jeffborgs.github.io/portfolio/](https://jeffborgs2026.github.io/Portif-lio_ETEC_DS1_AG15_2026/)

## Explicação do Funcionamento do Projeto
O site funciona como uma página única (*Single Page*) com rolagem suave (`scroll-behavior: smooth`). No topo, uma barra de navegação fixa (`sticky-top`) adapta-se automaticamente a telas de celulares e computadores, permitindo saltar diretamente para qualquer seção por meio de âncoras internas (`#perfil`, `#formacao`, `#projetos` e `#contato`). Logo abaixo do menu, um carousel exibe slides de destaque com controles manuais e automáticos, seguido pelas áreas informativas organizadas em grids responsivos e encerradas por um rodapé institucional.

## Descrição dos Recursos Novos Adicionados
Além da estrutura base construída em aula, foram implementados **dois recursos novos** visíveis e funcionais para evoluir o projeto:
1. **Nova Seção Exclusiva de Formação Acadêmica (`#formacao`):** Criação de uma seção dedicada para apresentar minhas qualificações técnicas e superiores (Desenvolvimento de Sistemas, Gestão de Marketing, Design Gráfico e Segurança do Trabalho), integrada diretamente ao menu de navegação.
2. **Animações e Transições Interativas (`:hover`):** Efeitos visuais dinâmicos aplicados aos cards de projetos, formação e ícones de tecnologias ao passar o cursor ou tocar na tela.

## Explicação de Como os Recursos Foram Implementados
* **Seção de Formação Acadêmica:** Implementada por meio de uma nova tag `<section id="formacao">` estruturada com o sistema de grid do Bootstrap (`container`, `row g-4` e colunas responsivas `col-md-6 col-lg-3`), utilizando componentes `card` com `badge` para diferenciar o curso em andamento das formações concluídas, além de um novo link `<a class="nav-link" href="#formacao">` na `navbar`.
* **Animações e Transições CSS:** Implementadas no bloco `<style>` através das classes personalizadas `.card-hover` e `.tech-badge`, combinando a propriedade `transition` (`transform` e `box-shadow` em `0.3s ease`) com a pseudo-classe `:hover`, aplicando elevação vertical (`transform: translateY(-8px)`), realce de sombra e zoom suave nas imagens dos projetos (`transform: scale(1.06)`).
