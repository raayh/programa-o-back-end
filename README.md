# programacao-back-end
Ambientação para o curso de back-end da awari

Use esse arquivo para explicar e descrever o que esse site irá fazer. Como ainda estamso nos familiarizando com a ferramenta, segue os comandos gits que você pode usar:
## Exemplos de comandos para prompt do Windows
- cd - Muda o diretório atual.
- dir - Lista os arquivos e diretórios no diretório atual.
- md - Cria um novo diretório.
- rd - Remove um diretório.
- type - Exibe o conteúdo de um arquivo.
- copy - Copia um arquivo.
- move - Move ou renomeia um arquivo.
- del - Remove um arquivo.
- tree - Exibe a estrutura de diretórios.
- ping - Verifica a conectividade com um host.
- ipconfig - Exibe informações sobre o endereço IP do computador.
- netstat - Exibe as conexões de rede ativas no computador.
- tasklist - Lista os processos em execução.
- taskkill - Finaliza um processo.
- systeminfo - Exibe informações sobre o sistema operacional.

1. Git clone
É um comando para baixar o código fonte existente de um repositório remoto (como o Github). Em outras palavras, ele basicamente faz uma cópia idêntica da versão mais recente de um projeto em um repositório e a salva em seu computador.
Há diferentes maneiras de baixar o código-fonte, mas uma das mais comuns é o clone com https:
git clone <https://name-of-the-repository-link>

2. Git branch
As ramificações são muito importantes no mundo git. Ao utilizá-las, várias "devs" podem trabalhar simultaneamente no mesmo projeto. Podemos usar o comando git branch para criar, listar e deletar branches. Este comando criará uma ramificação localmente:
git branch <branch-name>

3. Git checkout 
O comando git checkout é o mais usado para alternar de um branch para outro, mas é possível usá-lo também para fazer check-out de arquivos e commits.
git checkout <name-of-your-branch>

4. Git Status
Fornece todas as informações necessárias sobre o branch atual.
git status

5. Git add
Quando um arquivo é criado, modificado ou excluído, essas alterações acontecem em um local e não são incluídas no próximo commit (a menos que as configurações sejam alteradas). O comando git add é usado para incluir essas alterações ao próximo commit.
git add <file>

6. Git commit
Este é talvez o comando mais usado do Git. Ao chegar a um certo ponto no desenvolvimento, é preciso salvar as alterações. Nesse caso, o Git commit ajuda a definir um “ponto de verificação” que permite que ele seja retomado depois, caso precise.
Também é necessário escrever uma mensagem curta para explicar o que foi desenvolvido ou alterado no código-fonte — lembrando que esse comando  salva as alterações apenas localmente.
git commit -m "commit message"

7. Git push
Depois de confirmadas, todas as alterações devem ser enviadas para o servidor remoto. Sendo assim, você pode usar o Git push para carregar os commits no repositório remoto.
git push <remote> <branch-name>

8. Git pull
Uma combinação de git fetch e git merge, esse comando é geralmente usado para obter atualizações do repositório remoto. Ele obtém as atualizações do repositório remoto (git fetch) e aplica imediatamente as últimas alterações em seu local (git merge).
git pull <remote>

9. Git reverter
Existem diversas maneiras de desfazer alterações local ou remotamente, mas uma das mais seguras é usar o git revert. A vantagem desse comando é que ele não toca no histórico de commits, o que significa que, mesmo os revertidos, ainda será possível visualizá-los.
git revert 3321844

10. Git merge
O Git merge basicamente integra a ramificação de recursos com todos os os commits de volta para a ramificação dev (ou master).
git merge <branch-name>


