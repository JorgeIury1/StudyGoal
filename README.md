# StudyGoal

Site de estudos gamificado. Você registra o que estudou no dia (matérias, tempo, questões e redações), ganha XP, desbloqueia conquistas e sobe de grau de estudante. Uso pessoal, sem ranking.

Os dados ficam salvos no navegador de quem usa (localStorage). Não há servidor nem login. Na página de perfil dá para baixar e restaurar um backup.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo `studygoal`), público.
2. Envie `index.html` e `README.md` para a raiz do repositório (botão "Add file" > "Upload files").
3. Vá em **Settings > Pages**. Em "Build and deployment", escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em 1 a 2 minutos o site abre em `https://SEU-USUARIO.github.io/studygoal/`.

## Aparecer no Google

1. Abra o Google Search Console e adicione o endereço do site (propriedade "Prefixo do URL").
2. Verifique a propriedade (o método por tag HTML cabe no `<head>` do `index.html`).
3. Use "Inspeção de URL" e peça a indexação da página inicial.

## Observações

- A resposta do bot é automática (texto simples). Resposta com IA exigiria um servidor à parte.
- Os níveis de grau e o XP das conquistas podem ser ajustados no começo do script do `index.html` (`GRAUS` e a função `achievements`).
