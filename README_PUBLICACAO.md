# ECOAA — Site estático com painel de conteúdo

## Publicação no GitHub Pages
1. Crie um repositório GitHub, preferencialmente `ecoaa-site` (público se usar GitHub Pages gratuito).
2. Envie **o conteúdo desta pasta** para a raiz do repositório (index.html, editor.html, conteudo.js, assets/, .nojekyll).
3. Em Settings > Pages, escolha Deploy from a branch; branch `main`, pasta `/ (root)`; salve.
4. Aguarde a publicação e teste todos os links e imagens no endereço mostrado pelo GitHub.
5. Para domínio próprio, configure o domínio em Settings > Pages e os registros DNS conforme as instruções atuais do GitHub.

## Atualização
1. Abra `editor.html` no computador, ou no site publicado (ele funciona inteiramente no navegador).
2. Edite as fichas e clique em **Baixar conteudo.js atualizado**.
3. No repositório GitHub, substitua o arquivo `conteudo.js` pelo baixado e confirme (commit).
4. Para imagens, envie também os arquivos à pasta `assets/` e use caminhos como `assets/foto-pessoa.jpg` no editor.
5. Após publicação, recarregue a página; a atualização pode levar alguns minutos.
6. Guarde backups JSON antes de grandes mudanças. Não compartilhe o link do editor como se fosse um painel com autenticação: ele é uma ferramenta pública de edição local, sem senha e sem capacidade de publicar sozinho.

## Limites e verificações
- **Não há autenticação ou publicação direta pelo painel.** Qualquer visitante pode abrir o editor, mas só alguém com permissão de escrita no repositório poderá publicar alterações.
- Fotografias e capas exigem direitos de uso/autorização. Imagens geradas por IA são ilustrativas, não registros reais.
- Revisar nomes, vínculos, dados bibliográficos, textos e contatos antes de tornar o site público.
- Atualizações de conteúdo por arquivo `conteudo.js` abrangem pesquisadores, projetos, artigos, livros, capítulos e extensão. Outros textos institucionais permanecem em `index.html`.
- Para pré-visualização, execute `python3 -m http.server 8000` nesta pasta e abra `http://localhost:8000` (opcional).
