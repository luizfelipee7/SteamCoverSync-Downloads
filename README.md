<p align="center">
  <img src="assets/logo.png" alt="Logo Steam Cover Sync" width="160">
</p>

<h1 align="center">Steam Cover Sync</h1>
<p align="center">Sua biblioteca. Seu estilo.</p>
<p align="center"><strong>Windows 64 bits · Português e inglês · Sem instalar Python</strong></p>

<h3 align="center"><a href="https://github.com/luizfelipee7/SteamCoverSync-Downloads/releases/latest">⬇ Baixar o aplicativo</a></h3>
<p align="center">Página oficial de downloads, novidades e suporte.</p>

---

| 🖼️ Organize | 🎮 Personalize | 🛡️ Revise |
| :--- | :--- | :--- |
| Veja suas capas em uma galeria. | Troque uma capa ou várias de uma vez. | Confira o destino antes de aplicar. |
| Importe imagens, pastas e packs. | Corrija AppIDs dentro do app. | Guarde backups e restaure as originais. |

## 🚀 Comece em 3 passos

1. **Baixe e abra.** Na [release mais recente](https://github.com/luizfelipee7/SteamCoverSync-Downloads/releases/latest), escolha o arquivo `.exe` e abra com dois cliques.
2. **Prepare sua coleção.** Selecione a instalação da Steam e sua conta local. Na aba **Capas**, clique em **Importar capas**.
3. **Aplique seu estilo.** Feche a Steam, clique em **Revisar e aplicar capas**, confira as mudanças e confirme. Reabra a Steam para ver o resultado.

<p align="center">
  <a href="https://www.steamgriddb.com/">🖼️ Encontrar capas</a> ·
  <a href="https://steamdb.info/">🔎 Consultar AppID</a> ·
  <a href="https://github.com/luizfelipee7/SteamCoverSync-Downloads/issues">💬 Relatar problema ou sugerir melhoria</a>
</p>

## ✨ O que você pode fazer

- **Importar** capas avulsas, pastas ou packs `.zip`, `.rar` e `.7z`.
- **Corrigir ou pular** capas durante a importação, com prévia e progresso.
- **Buscar pelo nome do jogo** no modal da capa e selecionar o resultado para preencher o AppID. A busca funciona offline com o catálogo incluído no app.
- **Clicar em uma capa** para alterar a imagem, trocar seu AppID, aplicar só aquele jogo, restaurar a original na Steam ou apagar da coleção.
- **Baixar sua coleção** em ZIP para guardar ou importar depois.
- **Aprender pelo Tutorial** dentro do aplicativo, com exemplo visual do AppID.

## 💡 Dúvidas rápidas

<details>
<summary><strong>Preciso instalar alguma coisa?</strong></summary>

Para abrir o executável, não é necessário instalar Python. Use Windows de 64 bits.

ZIP funciona diretamente. Para RAR e 7Z, instale o [7-Zip](https://www.7-zip.org/) se o aplicativo solicitar um extrator compatível.

</details>

<details>
<summary><strong>Quais imagens posso usar? O que é AppID?</strong></summary>

Use imagens verticais em PNG, JPG ou JPEG. O AppID é o número que identifica um jogo na Steam; consulte-o no [SteamDB](https://steamdb.info/).

Você também pode digitar o nome do jogo no próprio modal, selecionar o resultado e confirmar o AppID preenchido. Cada resultado tem um link para conferir o jogo na Steam. O botão **Atualizar** busca uma lista mais recente; o campo manual continua disponível.

Nomes como `10.png` ou `10p.jpg` fornecem o ID automaticamente. Nomes com letras, como `5a1d36.jpg`, também são aceitos: informe o número dentro do app. O programa não reconhece o jogo pela imagem; confira se o número corresponde à capa.

Se precisar corrigir depois, clique na capa e escolha **Alterar AppID**. Se o ID já estiver em uso, você pode confirmar a substituição ou digitar outro número.

</details>

<details>
<summary><strong>Posso ignorar uma capa com problema?</strong></summary>

Sim. Na correção de uma pasta ou pack, use **Pular esta capa** para seguir adiante. Mesmo pulando todas as problemáticas, as corretas são importadas. **Cancelar** encerra toda a importação daquela seleção.

</details>

<details>
<summary><strong>Onde ficam minhas capas? Como atualizar o app?</strong></summary>

A coleção fica em `%APPDATA%\SteamCoverSync\covers`. As configurações e os backups ficam em `%APPDATA%\SteamCoverSync`.

Essa pasta não é a pasta temporária do Windows. Para atualizar, feche o app, baixe o novo executável e use-o no lugar do anterior; sua coleção permanece salva. Para guardar uma cópia das imagens, use **Baixar capas** no aplicativo.

</details>

<details>
<summary><strong>Apagar uma capa é o mesmo que restaurar a original?</strong></summary>

**Apagar capa** remove a imagem da coleção do aplicativo. **Restaurar original na Steam** remove a personalização daquele jogo da conta selecionada, com backup, permitindo que a Steam use sua arte padrão disponível. A imagem da coleção permanece disponível.

Feche a Steam antes de aplicar ou restaurar e abra novamente depois.

</details>

---

Este repositório contém a apresentação do app, a logo, o catálogo de nomes e AppIDs e os downloads. O código-fonte é mantido em um repositório privado de desenvolvimento. Para baixar o aplicativo, escolha o `.exe` nos assets da release; os arquivos automáticos **Source code** contêm somente os arquivos públicos deste repositório, sem o código do programa.
