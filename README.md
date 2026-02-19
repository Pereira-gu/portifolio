# Portfólio de Gustavo Pereira

Este repositório contém o código-fonte do meu portfólio pessoal, um site estático desenvolvido em HTML, CSS e JavaScript. Ele apresenta informações sobre mim, meus projetos, habilidades, interesses e formas de contato.

## Visão Geral

- **Tecnologias usadas:** HTML5, CSS3 e um pouco de JavaScript para interatividade mínima.
- **Estrutura:** O `index.html` é a página principal; o arquivo `style.css` controla a aparência; existe uma pasta `img/` com imagens e `cv/` com o currículo em PDF.

## Adicionar ou atualizar projetos

Os cards de projetos ficam dentro da seção `<section id="projects">` no `index.html`. Cada projeto utiliza a classe `.card-projeto`. Para inserir um novo projeto basta copiar um dos blocos existentes e ajustar:

1. **Título** (`<h3>`).
2. **Descrição e objetivos** dentro de `<p>`.
3. **Tecnologias** usadas.
4. **Links** (site, repositório GitHub, etc.) dentro de `<div class="projeto-link-wrapper">`.

Exemplo de um card com links adicionados:

```html
<div class="card-projeto">
  <h3>E-Commerce Optimization</h3>
  <p><strong>Otimização de Operações E-commerce com Análise RFM e Curva ABC</strong></p>
  <p><strong>Objetivo:</strong> Transformar dados brutos de vendas em inteligência logística e estratégica para redução de custos de estoque e aumento de retenção de clientes.</p>
  <p><strong>Tecnologias:</strong> Python, SQL (pandas/scipy), Power BI.</p>
  <div class="projeto-link-wrapper">
      <a href="https://github.com/Pereira-gu/E-Commerce-Optimization" target="_blank" class="projeto-link projeto-link-github" aria-label="Ver projeto no GitHub">
          <span class="link-icon">🔗</span>
          GitHub
      </a>
  </div>
</div>
```

## Como usar este repositório

1. Clone o repositório para sua máquina:
   ```bash
   git clone https://github.com/Pereira-gu/portifolio.git
   ```
2. Abra o `index.html` no navegador para ver seu portfólio em funcionamento.
3. Edite o conteúdo conforme desejar (habilidades, projetos, etc.).

## Licença

Este portfólio está disponível sob a licença MIT. Sinta-se livre para forkar e adaptar.

---

*Aproveite e me avise se quiser ajuda para atualizar algo mais!*