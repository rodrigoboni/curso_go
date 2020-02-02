# curso_go
Códigos e exemplos do curso Go Lang Udemy

# Instalação Go
* baixar versão + recente - https://golang.org/
* sudo tar -C /usr/local -xzf go<versao>
* add go no path
    * editar arquivo ~/.profile
    * add "export PATH=$PATH:/usr/local/go/bin"
    * exec "source .profile" ou fechar terminal
    * testar com cmd "go version"

# Config vscode
* criar arquivo e salvar com extensão .go
* deve exibir msg recomendando extensao "go" - permitir instalar
* permitir instalar extensões recomendadas também
* extensões adicionais:
    * code runner
* ctrl+alt+n para executar código
* ctrl+alt+m para interromper exec   

# variáveis de ambiente
* GOROOT - instalação go
* GOPATH - workspace

# pasta /go
* bin - binários gerados para os programas e binários do go
* pkg - pacotes / compilados por plataforma (x64 etc)
* src - código fonte dos projetos
