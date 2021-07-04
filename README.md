usdc-aum
========

Estima os ativos USDC sob gestão, mostrando a quantidade total de USDC cunhada em cada uma das cadeias ao vivo. Para obter uma contagem precisa, seria necessário subtrair as contas de reserva que mantêm USDC que ainda não são apoiados por AUM.

## Setup
```
git clone https://github.com/isaccanedo/usdc-aum.git
cd usdc-aum/
npm install
```

## Run
```
node app
```

## Exemplo de saída a partir de 04-07-2021
```
Fonte de USDC
-----------------------------------------
      Ethereum USDC:    24,686,528,868.72
      Algorand USDC:       176,081,218.19
       Stellar USDC:        11,249,152.85
        Solana USDC:       785,000,020.00
          Tron USDC:       111,680,870.77
-----------------------------------------
  Total USDC supply:    25,770,540,130.53

```
