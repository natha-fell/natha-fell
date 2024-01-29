
 <h1 align="center">Olá, meu nome é Nathã Fellipe 👋😀</h1>
 <h1 align="center">Seja muito bem vindo ao meu perfil!</h1> 

[🇺🇸 Translate to English](#translate-to-english)
<a name="translate-to-english"></a>
<script>
function translateToEnglish() {
  // Obtém o conteúdo atual do README
  var currentContent = document.body.innerHTML;

  // Adiciona um aviso indicando que a tradução está em andamento
  document.body.innerHTML = "<p>Translating to English...</p>";

  // Obtém o conteúdo do README via API de tradução do Google
  fetch("https://translate.googleapis.com/translate_a/single?client=gtx&sl=auto&tl=en&dt=t&q=" + encodeURIComponent(currentContent))
    .then(response => response.json())
    .then(data => {
      // Extrai o texto traduzido da resposta
      var translatedText = data[0].map(item => item[0]).join('');

      // Atualiza o corpo do README com o texto traduzido
      document.body.innerHTML = translatedText;
    })
    .catch(error => {
      // Em caso de erro, exibe uma mensagem
      document.body.innerHTML = "<p>Translation failed. Please try again later.</p>";
    });
}
</script>

[Translate to English](javascript:translateToEnglish())

### Sobre mim

💻 Eu sou um desenvolvedor *Front-End* 

**Tecnologias e Ferramentas**

<!-- (Aqui você pode adicionar tecnologias que aprendeu no curso, já listamos algumas delas, e outras que já domina)) -->

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)


### Cursos realizados 🤓

<!-- (Aqui você pode adicionar cursos que você já fez) -->

https://devemdobro.com/matriculas-abertas/

<!--
Substitua o usuário lbguilherme pelo seu usuário no GitHub.
-->

### GitHub Stats ⚡
<div>
<a href="https://github.com/natha-fell">
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=natha-fell&layout=compact&langs_count=7&theme=dracula"/>

### Entre em contato comigo! 📭
<div>
<a href="www.linkedin.com/in/nathã-fellipe-a428b2277" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
<a href = "mailto:nathafguartieri70@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>
