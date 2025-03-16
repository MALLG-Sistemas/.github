## Como Clonar, Codificar e Enviar Alterações no Repositório

Este guia passo a passo ensina como clonar o repositório, criar uma nova branch, começar a codificar e enviar suas alterações usando o Git e o VS Code.

### 1. Clonando o Repositório

1.  **Abra o VS Code:** Inicie o Visual Studio Code.
2.  **Abra o Terminal:** Vá em "Terminal" > "Novo Terminal".
3.  **Navegue até o Diretório Desejado:** Use o comando `cd <diretório>` para navegar até a pasta onde você deseja clonar o repositório.
4.  **Clone o Repositório:** Execute o seguinte comando, substituindo `<URL_DO_REPOSITÓRIO>` pela URL do seu repositório:

    ```bash
    git clone <URL_DO_REPOSITÓRIO>
    ```

5.  **Acesse a Pasta do Repositório:** Use o comando `cd <nome_do_repositório>` para entrar na pasta do repositório clonado.

### 2. Criando uma Nova Branch

1.  **Crie a Branch:** Execute o seguinte comando, substituindo `<nome_da_branch>` por um nome descritivo para sua branch:

    ```bash
    git checkout -b <nome_da_branch>
    ```

    *Exemplo:* `git checkout -b feature/adicionar-formulario-de-contato`

### 3. Codificando

1.  **Faça as Alterações:** Comece a codificar e fazer as alterações necessárias nos arquivos do projeto.
2.  **Salve as Alterações:** Salve os arquivos modificados.

### 4. Adicionando e Commitando Alterações

1.  **Adicione as Alterações:** Use o comando `git add .` para adicionar todas as alterações ao staging area. Se desejar adicionar arquivos específicos, use `git add <nome_do_arquivo>`.
2.  **Commit as Alterações:** Execute o seguinte comando, substituindo `<mensagem_do_commit>` por uma mensagem descritiva do que você alterou:

    ```bash
    git commit -m "<mensagem_do_commit>"
    ```

    *Exemplo:* `git commit -m "Adiciona formulário de contato"`

### 5. Enviando as Alterações (Push)

1.  **Envie a Branch:** Execute o seguinte comando para enviar sua branch para o repositório remoto:

    ```bash
    git push origin <nome_da_branch>
    ```

### 6. Criando um Pull Request

1.  **Acesse o Repositório no GitHub:** Vá para a página do seu repositório no GitHub.
2.  **Compare e Pull Request:** O GitHub deve exibir uma mensagem informando que sua branch foi enviada. Clique em "Compare & pull request".
3.  **Preencha o Pull Request:** Adicione um título e uma descrição para o seu pull request, explicando as alterações que você fez.
4.  **Crie o Pull Request:** Clique em "Create pull request".

### Observações

* Certifique-se de ter o Git instalado e configurado corretamente no seu computador.
* Use nomes de branch descritivos e mensagens de commit claras.
* Mantenha sua branch atualizada com a branch principal (`main` ou `master`) para evitar conflitos.

Este guia cobre o fluxo básico do Git para clonar, codificar e enviar alterações. Se você tiver alguma dúvida, consulte a documentação do Git ou peça ajuda aos seus colegas.
