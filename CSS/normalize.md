# Normalize CSS

https://necolas.github.io/normalize.css/


O Normalize.css é um arquivo de CSS (folha de estilos) que ajuda a deixar todos os navegadores “falando a mesma língua” visualmente. Aqui está como funciona e pra que serve:

## ✅ Para que serve

- Cada navegador (Chrome, Firefox, Safari, Edge, etc.) tem padrões diferentes para os elementos HTML (como `<h1>, <p>, <ul>,` etc). Por exemplo: em um navegador o `<h1>` pode ter margem diferente de outro.

- O Normalize.css “normaliza” esses estilos padrão, ou seja: ele define estilos base para muitos elementos para que eles apareçam de forma mais consistente em todos os navegadores. 
necolas.github.io

- Ele é uma alternativa moderna aos “CSS Reset” tradicionais, que zeravam praticamente tudo. O Normalize faz algo mais refinado: “apenas ajuste o que precisa”. 
necolas.github.io

## 🛠 Como e quando usar

- Você coloca o arquivo Normalize.css no início da sua folha de estilos (ou como primeiro CSS carregado), para que as bases fiquem iguais antes dos seus estilos personalizados.

- Depois você aplica seus próprios estilos, sabendo que eles partirão de um nível mais consistente em todos os navegadores.

- É útil em projetos onde a compatibilidade entre navegadores importa (design responsivo, diferentes dispositivos, etc).

## 🎯 Principais benefícios

- Menos “surpresas” visuais ao ver seu site em diferentes navegadores.

- Economia de tempo: você não precisa “corrigir” tanto os estilos básicos para cada navegador.

- Código mais limpo: ao usar Normalize.css, seus estilos personalizados não precisam “sobrepor” tanto estilos padrão confusos ou diferentes.

## ⚠️ Algumas considerações

- Ele não remove todos os estilos padrões (isso seria o “reset” completo). Então você ainda pode ver estilos padrão dependendo do navegador.

- Mesmo com Normalize.css, você ainda vai precisar definir seus próprios estilos (cores, fontes, margens, etc). Ele apenas define uma base consistente.

- Se você estiver usando um framework CSS que já inclui normalização ou reset (ex: Bootstrap), verifique se não está duplicando ou conflitando.
