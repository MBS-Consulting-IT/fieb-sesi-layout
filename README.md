[![](https://cdn.jsdelivr.net/gh/MBS-Consulting-IT/fieb-sesi-layou/badge)](https://www.jsdelivr.com/package/gh/pedbernardo/orquestra-utils)

# FIEB-SESI Layout

Refatoração do CSS base para os projetos da FIEB com utilização do `layout.js`.

<br>

### Utilização
```html
<script src="https://cdn.jsdelivr.net/gh/MBS-Consulting-IT/fieb-sesi-layout@1.0.0/dist/layout-v2.css"></script>

<!-- minificado -->

<script src="https://cdn.jsdelivr.net/gh/MBS-Consulting-IT/fieb-sesi-layout@1.0.0/dist/layout-v2.min.css"></script>
```

<br>

### Melhorias
- aplicação de estilos base e reset
- suporte a checkboxes e radios customizados em webkit browsers (uso de pseudo seletores em inputs é apenas suportado em webkit)
- ajuste no componente de toggle para manter aparência utilizada no Maestro
- ajuste no componente de tabela e tabela multi-valorada para visual minimalista
- remoção de código não utilizado e melhor organização com uso de SASS
- disponibilização via CDN através do JSDelivr

<br>

### Modificações na estrutura da página `orquestra-layout.scss`
- aplicação de aparência minimalista com fundo neutro (branco)
- fixada a barra de botões de finalização na parte inferior da página
- **remoção** da coluna lateral com histórico e solicitações vínculadas

