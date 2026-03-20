# 🚀 Guia de Sobrevivencia: Dominio do terminal

Este guia foi criado para te ajudar com o registros de comandos normalmente usados no ***TERMINAL***, sendo criado por um aluno de **Sistemas Operacionais**, fazendo uso do [TERMINAL MASTER](https://andersonrmgomes.github.io/terminal-master/) para o uso pratico dos codigos em _Linux e Windowns_.

---------

## Introdução
A CLI ou a Interface de Linha de Comando no portugues brasileiro é descrita como uma interface que interage diretamente com o _**SISTEMA OPERACIONAL**_ atraves de comandos escritos em texto para cada sistema, por exemplo a CLI do **🐧Linux**, denomidade de **Bash** ou **Bourne Again Shell** diferente da Windows, que se chama **CMD**. Por isso as CLI's tem influencia direta nos nossos computadores, sendo a base do nossos costumes acessos nos arquivos, sendo a forma bruta de acesso a varias informações alem de arquivos, como a acessibilidade a internet/roteador.
## 💾 COMANDOS
Abaixo estara comandos para serem utilizados na CLI e do Windowns.

| Comandos | Função | Sistema | Exemplo de uso | 
| :--- | :--- | :--- | :----- |
| `cd`| `Altera o diretorio escolhido` | _Ambos_ | cd Documentos -> _Diretorio "Documentos" aberto_ |
| `dir e Is`| `Lista de arquivos e pasta do diretorio aberto` | Windows e Linux (respectivamente)| Documentos -> dir/Is -> abre o conteudo do diretorio |
| `mkdir`| `Criar um diretorio` | _Ambos_ | mkdir Exel -> _diretorio criado_|
| `findstr e find`| `pesquisa/procura arquivos e diretorios` | Windows e Linux (respectivamente) | find ~ -type f; findstr "erro" arquivo.log|
| `del e rm`| `remove diretorio escolhido` |  Windows e Linux (respectivamente) | (arquivo) -> rmdir arquivo ->  arquivo deletado
| `cls e clear` | `"limpar" os textos do terminal` |  Windows e Linux (respectivamente) | (opções do comando dir) cls -> (terminal limpo) |
| `move e mv` | `move arquivos ou diretorios` |  Windows e Linux (respectivamente) | move Arquivo > pasta_copy Arquivo direcionado a pasta_copy |
| `copy e cp` | `copia arquivos e diretorios` |  Windows e Linux (respectivamente) | copy Arquivo > pasta_copy -> Arquivo copiado e direcionado a pasta_copy |
| `echo %cd% e pwd` | `apresenta o caminho utilizado` | Windows e Linux (respectivamente) | echo %cd% -> Saída esperada: C:\Users\Usuario\Documentos\Projetos; pwd -> Saída esperada: /home/usuario/documentos/projetos |
| `icacls e chmod` | `altera permissões` | Windows e Linux (respectivamente) | chmod 777 arquivo.txt: Dá permissão total; icacls pasta /grant Usuario:(OI)(CI)F: Dá controle total |
| `systeminfo e uname -a` | `informações do sitema são apresentada` | Windows e Linux (respectivamente) | systeminfo ou uname -a -> apresenta as informações do sistema/ pc|
| `netsh e ip` | `Apresenta as confgurações da rede` | Windows e Linux (respectivamente)| netsh e ip -> exibi as configurações da rede|
| `tasklist e top` | exibi os processos que ocorrem no gerenciador de tarefas | Windows e Linux (respectivamente) | tasklist e top: Lista tudo o que está rodando |
| `getmac e ip link` | `identificar o endereço físico da sua placa de rede` | getmac /v: Mostra o endereço detalhado; ip link show: Lista todas as interfaces e seus MACs |