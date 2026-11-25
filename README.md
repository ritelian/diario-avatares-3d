# Entre o corpo e o digital

Diário de bordo de Rita Martins sobre avatares 3D, autoria, perceção e prática artística.

- **Site:** [ritelian.github.io/diario-avatares-3d](https://ritelian.github.io/diario-avatares-3d/)
- **Repositório:** [ritelian/diario-avatares-3d](https://github.com/ritelian/diario-avatares-3d)

## Atualizar o site publicado

O **`index.html`** reúne o design, os textos, as fontes e o funcionamento do site. A publicação inclui também o modelo do templo em **`assets/models/templo.gltf`**, o vídeo de entrada em **`assets/media/entrada-video.json`** e o retrato luminoso em **`assets/media/avatar-pessoa.json`**. Ao exportares pelo editor, o vídeo, o retrato e o modelo são incorporados no novo `index.html`, para facilitar as atualizações.

1. Abre o site e escolhe **Gerir o arquivo**, no rodapé.
2. Acrescenta ou edita notas, referências e trabalhos. Escolhe **Guardar neste navegador**.
3. Escolhe **Exportar site .zip** e descomprime o ficheiro descarregado.
4. Abre o repositório no GitHub. Na branch **main**, escolhe **Add file → Upload files**.
5. Envia o novo **`index.html`** para a raiz do repositório, substituindo o anterior, e confirma em **Commit changes**. Envia o ficheiro extraído, não o ZIP nem uma pasta exterior.
6. Aguarda a atualização do GitHub Pages e volta a abrir o site.

**Guardar neste navegador não torna as alterações públicas.** Cada navegador mantém a sua própria cópia. O editor não tem contas, palavra-passe ou acesso de administrador: quem visita o site pode experimentar alterações na sua cópia, mas só quem tem acesso ao repositório pode publicar a atualização.

Guarda uma exportação antes de limpares os dados do navegador ou de mudares de computador. **Guardar dados (sem modelos)** conserva os textos e as referências; **Exportar site .zip** guarda a versão completa, incluindo o vídeo de entrada e os modelos acrescentados.

A publicação usa **Settings → Pages → Deploy from a branch**, com a branch **main** e a pasta **/(root)**.

## Abertura do site

A entrada apresenta o vídeo fornecido por Rita Martins, gerado com **Hailuo AI / MiniMax**, em ecrã inteiro. Ao desceres a página, o vídeo fecha-se numa janela preta e dá lugar ao templo. A marca de água Hailuo AI foi preservada. É um exemplo visual animado; o personagem do vídeo não responde ao visitante. O templo apresentado abaixo é o modelo 3D interativo.

## Visualização das técnicas

O retrato luminoso na secção **Anatomia de um avatar** é uma ilustração artística criada com IA e inspirada em Fernando Pessoa, em tons de marfim e sálvia. A partir da mesma imagem, uma profundidade facial aproximada permite movimentos suaves de cabeça e olhar. O olhar acompanha a interação e o movimento pode ser pausado; a apresentação respeita a preferência de redução de movimento do navegador. É uma animação com profundidade estimada, sem reconstrução facial validada ou modelo completo para observar de todos os ângulos. Não é um resultado de CAP4D ou um avatar patrimonial validado.

## Acrescentar trabalhos 3D

Usa **Adicionar trabalho** e seleciona um modelo. O formato recomendado é **GLB**, com geometria, materiais e texturas no mesmo ficheiro, sem compressão Draco ou Meshopt e sem texturas KTX2/Basis.

Também podes usar **OBJ**: o visualizador aplica um material uniforme, sem carregar MTL ou texturas externas. Arrasta para rodar e usa a roda do rato ou um gesto de pinça para aproximar. Podes alternar a malha, parar a rotação e repor a vista.

**O templo** é a composição de Rita Martins para *Do Fragmento à Presença*, feita em Blender a partir da sua coluna original, com 24 instâncias, pavimento e cobertura. Conceção e montagem: Rita Martins; criação e edição com assistência de IA: OpenAI / Codex. O modelo aparece abaixo do vídeo de entrada e pode ser explorado em 3D, com rotação automática, arrasto, aproximação e reposição da vista. A versão web foi simplificada para acelerar o carregamento. **Pingas em diálogo** é um trabalho existente em p5.js.

## As duas pastas entregues

- **`diario-3d-publicar`** contém a versão preparada para publicação, com `index.html` e os recursos do vídeo, do retrato e do templo. As exportações feitas no editor incorporam esses recursos num único `index.html`. Para atualizar, segue os passos acima; não é necessário editar um `content.json` separado.
- **`diario-3d`** contém a versão de desenvolvimento, com os textos em `content.json` e o design e funcionamento em ficheiros separados. Esta pasta é opcional e destina-se a alterações mais profundas. Mudar o seu `content.json` não atualiza o site publicado.

Para experimentar a versão de desenvolvimento, usa uma pré-visualização de sites. Se tiveres Python, podes abrir um terminal nessa pasta, executar `python3 -m http.server 8000` e visitar <http://localhost:8000>. Nessa versão, um duplo clique em `index.html` pode impedir o carregamento dos conteúdos.

## Conteúdo inicial

O arquivo reúne uma síntese retrospetiva preparada em 24 de novembro de 2026 a partir do diário e da biblioteca no Notion, de conversas de investigação e da clarificação dos avatares patrimoniais como objeto de trabalho. As datas indicam os registos de origem; as fontes pessoais mantêm o seu acesso privado.

A presença de uma referência não indica leitura ou teste concluído. As experiências propostas e a exploração de Fernando Pessoa estão identificadas como trabalho por realizar e documentar.
