# Entre o corpo e o digital

Diário de bordo de Rita Martins sobre avatares 3D, autoria, perceção e prática artística.

- **Site:** [ritelian.github.io/diario-avatares-3d](https://ritelian.github.io/diario-avatares-3d/)
- **Repositório:** [ritelian/diario-avatares-3d](https://github.com/ritelian/diario-avatares-3d)

## Atualizar o site publicado

A versão publicada está reunida num único **`index.html`**, que inclui o design, os textos, as fontes e o funcionamento do site.

1. Abre o site e escolhe **Gerir o arquivo**, no rodapé.
2. Acrescenta ou edita notas, referências e trabalhos. Escolhe **Guardar neste navegador**.
3. Escolhe **Exportar site .zip** e descomprime o ficheiro descarregado.
4. Abre o repositório no GitHub. Na branch **main**, escolhe **Add file → Upload files**.
5. Envia o novo **`index.html`** para a raiz do repositório, substituindo o anterior, e confirma em **Commit changes**. Envia o ficheiro extraído, não o ZIP nem uma pasta exterior.
6. Aguarda a atualização do GitHub Pages e volta a abrir o site.

**Guardar neste navegador não torna as alterações públicas.** Cada navegador mantém a sua própria cópia. O editor não tem contas, palavra-passe ou acesso de administrador: quem visita o site pode experimentar alterações na sua cópia, mas só quem tem acesso ao repositório pode publicar a atualização.

Guarda uma exportação antes de limpares os dados do navegador ou de mudares de computador. **Guardar dados (sem modelos)** conserva os textos e as referências; **Exportar site .zip** guarda a versão completa, incluindo os modelos acrescentados.

A publicação usa **Settings → Pages → Deploy from a branch**, com a branch **main** e a pasta **/(root)**.

## Acrescentar trabalhos 3D

Usa **Adicionar trabalho** e seleciona um modelo. O formato recomendado é **GLB**, com geometria, materiais e texturas no mesmo ficheiro, sem compressão Draco ou Meshopt e sem texturas KTX2/Basis.

Também podes usar **OBJ**: o visualizador aplica um material uniforme, sem carregar MTL ou texturas externas. Arrasta para rodar e usa a roda do rato ou um gesto de pinça para aproximar. Podes alternar a malha, parar a rotação e repor a vista.

O **Estudo de superfície** é um objeto de demonstração do visualizador, identificado como tal. **Pingas em diálogo** é um trabalho existente em p5.js. O retrato generativo do site foi criado como ilustração deste arquivo e não é uma execução de CAP4D.

## As duas pastas entregues

- **`diario-3d-publicar`** contém a versão de um só ficheiro usada na publicação. Para atualizar esta versão, segue os passos acima. Não é necessário editar um `content.json` separado.
- **`diario-3d`** contém a versão de desenvolvimento, com os textos em `content.json` e o design e funcionamento em ficheiros separados. Esta pasta é opcional e destina-se a alterações mais profundas. Mudar o seu `content.json` não atualiza o site publicado.

Para experimentar a versão de desenvolvimento, usa uma pré-visualização de sites. Se tiveres Python, podes abrir um terminal nessa pasta, executar `python3 -m http.server 8000` e visitar <http://localhost:8000>. Nessa versão, um duplo clique em `index.html` pode impedir o carregamento dos conteúdos.

## Conteúdo inicial

O arquivo reúne uma síntese retrospetiva preparada em 24 de novembro de 2026 a partir do diário e da biblioteca no Notion, de conversas de investigação e da clarificação dos avatares patrimoniais como objeto de trabalho. As datas indicam os registos de origem; as fontes pessoais mantêm o seu acesso privado.

A presença de uma referência não indica leitura ou teste concluído. As experiências propostas e a exploração de Fernando Pessoa estão identificadas como trabalho por realizar e documentar.

O avatar referido na conversa como exemplo do contexto Timeleap foi criado pela **Broken Eggs**, que está a colaborar com o projeto. A imagem desse avatar não é usada no site.
