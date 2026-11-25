# Entre o corpo e o digital

Diário de bordo de Rita Martins sobre avatares 3D, autoria, perceção e prática artística.

- **Site:** [ritelian.github.io/diario-avatares-3d](https://ritelian.github.io/diario-avatares-3d/)
- **Repositório:** [ritelian/diario-avatares-3d](https://github.com/ritelian/diario-avatares-3d)

## Atualizar o site publicado

A versão preparada para publicação usa **`index.html`** e **`content.json`** separados. O segundo ficheiro contém as notas, as referências e os trabalhos. Conserva também a pasta `assets`, que inclui o templo, o vídeo de entrada, o retrato luminoso e as imagens e vídeos do portefólio.

A atualização recomendada é feita em **Gerir o arquivo**. A exportação reúne os dados e os recursos num novo `index.html` autónomo. Esse é o ficheiro a substituir no GitHub ao seguir os passos abaixo.

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

**O templo** é a composição de Rita Martins para *Do Fragmento à Presença*, feita em Blender a partir da sua coluna original, com 24 instâncias, pavimento e cobertura. Conceção e montagem: Rita Martins; criação e edição com assistência de IA: OpenAI / Codex. O modelo aparece abaixo do vídeo de entrada e pode ser explorado em 3D, com rotação automática, arrasto, aproximação e reposição da vista. A versão web foi simplificada para acelerar o carregamento. **Pingas em diálogo — Corpo de um encontro** é a obra em p5.js desenvolvida para o Professor Pedro, no contexto de *Imagens que lembram*. A capa mostra o modo de exemplo da própria obra, com dois participantes simulados.

## As duas pastas entregues

- **`diario-3d-publicar`** contém a versão preparada para o GitHub: `index.html`, `content.json` e a pasta `assets`. Ao publicar esta pasta pela primeira vez, mantém estes ficheiros e subpastas juntos. As atualizações exportadas pelo editor passam a reunir tudo num `index.html` autónomo.
- **`diario-3d`** contém a versão de desenvolvimento, com o design e o funcionamento em ficheiros separados. Permite alterações mais profundas; os ficheiros só se tornam públicos depois de serem enviados para o GitHub.

Os recursos incluem `assets/models/templo.gltf`, `assets/media/entrada-video.json`, `assets/media/avatar-pessoa.json` e `assets/media/portfolio-assets.json`. Este último reúne a animação da coluna, a sua capa e a capa de Pingas em diálogo. `assets/data/content-legacy.json` apoia a compatibilidade com notas anteriormente guardadas no navegador.

Para experimentar a versão de desenvolvimento, usa uma pré-visualização de sites. Se tiveres Python, podes abrir um terminal nessa pasta, executar `python3 -m http.server 8000` e visitar <http://localhost:8000>. Nessa versão, um duplo clique em `index.html` pode impedir o carregamento dos conteúdos.

## Conteúdo inicial

O arquivo reúne **14 notas, 16 referências e 6 trabalhos ou propostas**. Integra o diário e a biblioteca de estudo, a prática no DMAD e ideias para o artefacto do retiro doutoral. As datas indicam os registos de origem; quando a data do trabalho não está confirmada, a nota é identificada como registo retrospetivo.

Os trabalhos apresentados são **Pingas em diálogo**, **Coluna em movimento** e **O templo**. As propostas **As Faces de Pessoa**, **Encontros no Renascimento** e **O rosto que fica** continuam em desenvolvimento. Os estados distinguem a obra publicada, o trabalho existente e as ideias por concretizar.

A entrada da **2.ª Atividade Formativa de Estudo de Estado da Arte** conserva o texto de trabalho fornecido pela autora e as suas três referências bibliográficas. Está identificada como **Esboço em revisão**; não indica entrega ou aprovação da atividade.

A proposta de artigo e os documentos da pasta **Paper** ficaram excluídos. Os documentos pessoais integrais não são distribuídos com o site. A presença de uma referência na biblioteca não indica leitura ou teste concluído.


As Faces de Pessoa: o retrato luminoso também aparece animado na galeria e no detalhe da proposta. A animação inclui pestanejos locais, movimento da cabeça e do olhar, controlos de pausa e respeito pela preferência de movimento reduzido. Continua a ser um estudo visual com profundidade aproximada a partir de uma imagem.
