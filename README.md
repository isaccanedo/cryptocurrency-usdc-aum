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

## Example Output as of 2021-07-03
```
USDC Supply
-----------------------------------------
      Ethereum USDC:    24,681,900,738.20
      Algorand USDC:       176,105,114.26
       Stellar USDC:        11,249,152.85
        Solana USDC:       785,000,020.00
          Tron USDC:       111,719,980.49
-----------------------------------------
  Total USDC supply:    25,765,975,005.80
```
