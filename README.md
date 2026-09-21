# Jesse Orçamentos — PWA

PWA estático, preparado para publicação no GitHub Pages.

## Publicar

1. Crie um repositório no GitHub.
2. Recomenda-se deixar o repositório **Private** se o código for interno.
3. Envie **o conteúdo desta pasta para a raiz do repositório** (o `index.html` deve ficar na raiz).
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
6. Salve e aguarde o GitHub publicar o site.

O PWA usa caminhos relativos, então funciona também quando publicado como
`https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`.

## Observação importante

Os dados dos orçamentos são armazenados no `localStorage` do navegador/aparelho.
Isso significa que os dados **não são sincronizados entre computadores/celulares**.

Não coloque senhas, chaves de API ou informações que precisem ficar realmente protegidas dentro do frontend.
