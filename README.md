<p align="center">
  <img src="image/logo-bbx.png" alt="Logo BBX" width="120">
</p>

<h1 align="center">BBX</h1>

Interface web estatica da plataforma BBX, criada a partir de um wireframe com
navegacao lateral, layout escuro, cards de planos e paginas internas para uma
experiencia institucional e de gerenciamento.

## Visao Geral

O projeto apresenta uma area inicial de planos e quatro paginas secundarias:
gerenciamento, sobre nos, perfil e contato. A proposta visual segue uma
identidade escura com destaque em roxo, cards com imagens e uma tabela
comparativa de servicos.

## Paginas

- **Planos**: pagina inicial com cards dos pacotes e tabela comparativa.
- **Gerenciamento**: painel com metricas e atividades recentes.
- **Sobre Nos**: apresentacao da empresa, proposito e atuacao.
- **Perfil**: dados do usuario e informacoes do plano atual.
- **Contato**: canais de atendimento e formulario de mensagem.

## Estrutura

```text
BBX/
  index.html
  css/
    styles.css
  js/
    app.js
  image/
    logo-bbx.png
    plano-essencial.png
    plano-intermediario.png
    plano-avancado.png
  templates/
    gerenciamento.html
    sobre.html
    perfil.html
    contato.html
```

## Como Abrir

Abra o arquivo `index.html` diretamente no navegador.

As demais paginas estao conectadas pela barra de navegacao lateral.

## Tecnologias

- HTML5
- CSS3
- JavaScript

## Observacoes

- O projeto nao depende de build ou instalacao de pacotes.
- O logo tambem esta configurado como fav icon.
- As imagens dos cards de planos estao salvas localmente na pasta `image/`.
