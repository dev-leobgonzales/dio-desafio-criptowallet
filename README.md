# Desafio da DIO - Especialista em Blockchain

<li>
Construir um gerador de carteiras de Bitcoin (Faucet - sem valor) - par pvt-pub keys;
Importar para um software gerenciador de carteiras;
Realizar transações de envio e recebimento de bitcoin.
</li>

## Tecnologia utilizadas

<li>
JavaScript / NodeJS (Gerador);
Electrum bitcoin wallet;
Bitcoin faucet generator.
</li>

## Links úteis

Download do [Electrum bitcoin wallet](https://electrum.org/#download)
Link para pegar ["faucet"](https://bitcoinfaucet.uo1.net)

## Passos
<li>
Verificar se o NodeJS está instalado, usando o comando no Git Bash "node -v" e após instalar o gerenciados "npm -v";
No terminal, digitar - "npm init -y" (-y para pular a parte de informar nomes e etc...);
No terminal, digitar - "npm install bip39 bip32@2.0.6 bitcoinjs-lib --save" (instalar essas dependências);
Após isso, criar o gerador de HD - o mesmo esta no arquivo "creatWallet.js"
</li>
