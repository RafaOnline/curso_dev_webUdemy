
# HTML5 Shiv

**Repositório:** `aFarkas/html5shiv`
**Descrição curta:** Script criado para permitir o uso de elementos HTML5 em versões antigas do Internet Explorer.

---

## 🧩 Funcionalidade

O **HTML5 Shiv** serve para:

* Permitir que elementos semânticos do HTML5 — como `<section>`, `<article>`, `<nav>`, `<header>` — funcionem no Internet Explorer 6 a 8.
* Fazer com que esses elementos sejam reconhecidos como blocos (ex.: `display: block`) por navegadores antigos.
* Incluir uma versão especial para impressão (`html5shiv-printshiv.js`) que melhora o suporte de impressão no IE6–8.

---

## 🔧 Como utilizar

### Instalação

**Via Bower:**

```bash
bower install html5shiv --save
```

**Ou manualmente:**
Baixe o ZIP do repositório, extraia e copie os arquivos da pasta `dist/` para seu projeto.

### Inclusão no HTML

Inclua no `<head>` usando comentários condicionais para IE < 9:

```html
<!--[if lt IE 9]>
  <script src="path/to/html5shiv.js"></script>
<![endif]-->
```

### Opções de configuração

Você pode configurar antes ou depois de carregar o script:

* `window.html5 = { elements: 'mark section customelement' }` — define quais elementos o shiv deve suportar.
* `window.html5.shivCSS = false` — desativa a aplicação automática de estilos.
* `window.html5.shivMethods = false` — desativa alterações em `document.createElement`, útil caso bibliotecas como jQuery já façam isso.

**Métodos úteis:**

* `html5.addElements(newElements)`
* `html5.createElement(nodeName)`
* `html5.createDocumentFragment()`

---

## ⚠️ Limitações

* Alguns elementos criados dinamicamente podem não funcionar exatamente igual nos browsers antigos.
* A versão de impressão pode ter problemas de desempenho em páginas muito grandes.
* Em projetos modernos, o suporte ao IE6–8 geralmente não é necessário.

---

## ✅ Quando usar

* Quando é necessário suportar IE6–8.
* Em projetos corporativos antigos ou aplicações legadas.

## ❌ Quando não usar

* Em projetos modernos que não precisam suportar versões antigas do Internet Explorer.
* Quando ferramentas mais completas de compatibilidade já estão em uso.

---

## 📝 Resumo

O HTML5 Shiv foi criado para permitir que navegadores antigos, especialmente o Internet Explorer 6–8, reconheçam e renderizem corretamente os novos elementos semânticos do HTML5. Ele foi essencial durante a transição para o HTML5 e ainda é útil em projetos legados.

