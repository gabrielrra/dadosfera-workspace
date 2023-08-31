# Dadosfera Workspace - Dev Container

Este repositório contém uma configuração pronta para ser usada com a extensão "Dev Containers" no Visual Studio Code.

Com esta configuração, você pode criar um ambiente de desenvolvimento isolado e consistente, garantindo que todos os membros da equipe tenham as mesmas ferramentas e configurações, independentemente de suas máquinas locais.

A imagem utilizada no workspace é a [dadosfera/base-kernel-py](https://hub.docker.com/r/dadosfera/base-kernel-py)

Qualquer instalação adicional necessária na imagem pode ser adicionada no arquivo [setup_script.sh](./.devcontainer/setup_script.sh)

## Como usar

Siga essas etapas simples para configurar e utilizar o ambiente de desenvolvimento:ms-vscode-remote.remote-containers

1. Instale a extensão [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) no VS Code, se ainda não o tiver feito

2. O VS Code detectará automaticamente a configuração do Dev Container e sugerirá abrir o espaço de trabalho dentro do contêiner. Você verá uma notificação na parte inferior direita. Clique em `"Reabrir em container"` (ou algo similar).

   1. Caso não apareça o aviso, pressione `Ctrl` + `shift` + `P` para abrir a paleta de comandos e procure por `"Dev Containers: Open Folder in Container..."` e selecione a raiz deste repositório.

3. Espere o build da imagem (a primeira vez pode demorar um pouco)

4. Pronto! Seu workspace com a imagem da dadosfera está ativo. Copie ou clone os projetos para este diretório para aproveitar todas as bibliotecas e recursos que estão na imagem.
