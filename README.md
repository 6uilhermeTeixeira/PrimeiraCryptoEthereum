# ETHTestToken
Criação de Rede de Testes com Ganache para realizar com a IDE Remix o Deploy do Contrato Inteligente programado em Solidity 

## Tecnologias Utilizadas

- Ganache: Ambiente de Desenvolvimento Ethereum
- MetaMask: Carteira Crypto para navegadores Web
- Remix: Ethereum IDE

## Como Usar

1. Instalar e configurar Ganache:
- Link para download: https://archive.trufflesuite.com/ganache/
- Após Download, dentro do Ganache Criar um novo "Workspace"

2. Instalar e criar carteira Meta Mask e guardar chaves de acesso:

Link para a criação da carteira: https://metamask.io/

3. Configurar Meta Mask para acessar a Test Net criada pelo Ganache:
-   Nome: DIONet
-   Token: DIO
-   Chain ID: 1337 (Igual Chain ID no Ganache)
-   RPC URL: HTTP://127.0.0.1:7545 (Igual RPC URL no Ganache)


4. Clone este repositório dentro da IDE Remix:
Acessar online a IDE Remix e caminhar até a sessão "Git", aonde encontrara a aba "Clone"

```bash
git clone https://github.com/6uilhermeTeixeira/RequisitandoDadosAPICriptomoedas.git
```

5. Realize a compilação e o Deploy do contrato na IDE Remix
- Após clonar repositório no explorador de arquivos caminhar até o arquivo "DIOToken.sol"
- Após abrir arquivo "DIOToken.sol" caminhar até o "Solidity Compiler" no menu lateral e clicar em "Compile DIOToken.sol"
- Após Compilar caminhar até "Deploy & run transactions" no menu lateral
- No campo "Environment" selecionar "Injected Provider - Metamask" e conectar a sua Carteira MetaMask.
- No campo "Contract" Selecionar "DIOToken - contracts/DIOToken.sol"
- Por fim clicar em "Deploy"

## Resultado

No menu lateral surgiram os campos para interação com a block chain e após o deploy do contrato sera possivel acompanhar cada transação dentro do blockexplorer do Ganache.

