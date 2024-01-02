# Contrato Inteligente de Reserva de Hotel

Este contrato inteligente, escrito em Solidity, gerencia reservas de quartos de hotel entre hóspedes e proprietários de hotéis. O contrato possui funcionalidades para reservar quartos, cancelar reservas e receber pagamentos.

## Funcionalidades

### Reservar Quarto

Os hóspedes podem reservar um quarto de hotel indicando o ID do quarto, a data de check-in e a data de check-out. O pagamento é exigido no momento da reserva para confirmar a reserva.

### Cancelar Reserva

Os hóspedes têm a capacidade de cancelar suas reservas desde que sejam o hóspede registrado para o quarto de hotel.

### Sacar Pagamentos

O proprietário do contrato pode sacar pagamentos de reservas bem-sucedidas após a conclusão da estadia.

## Estrutura do Contrato

O contrato é composto por:

- `RoomBooking`: Estrutura de dados que armazena informações sobre a reserva de um quarto.
- `bookings`: Mapeamento que associa o ID do quarto à reserva feita.
- `bookingFee`: Taxa de reserva definida pelo proprietário do contrato.
- `owner`: Endereço do proprietário do contrato.

## Uso do Contrato

Para utilizar este contrato, é necessário interagir com as seguintes funções:

- `bookRoom`: Realiza uma reserva de quarto.
- `cancelBooking`: Cancela uma reserva existente.
- `withdrawPayments`: Permite que o proprietário retire os pagamentos após a conclusão da estadia.

## Requisitos

Para interagir com este contrato, é necessário utilizar uma carteira Ethereum compatível com contratos inteligentes, como Metamask, e ter saldo suficiente para realizar as reservas.

## Autor

WEB3DEV.

## Recursos Educacionais

Para aprender mais sobre contratos inteligentes e Solidity, você pode consultar o seguinte recurso educacional:

- [Canal Educativo no YouTube WEB3DEV](https://www.youtube.com/watch?v=vdlS8P0Qu9o)

Sinta-se à vontade para contribuir ou sugerir melhorias neste contrato!

