# DIO-Desafio-de-modelagem-E-Commerce-
Bootcamp Database Experience

##Desafio 01

Cliente PF e PJ uma conta pode ser Pessoa física e jurídica, mas não pode ter as duas informações.
Adicionei o atributo ENUM na tabela de cliente com as opções de 'PF,PJ', sendo assim, não achei necessário criar outra tabela para armazenar a informação específica.

Pagamento pode ter cadastrado mais de uma forma.
Criei uma tabela principal chamada "pagamento" e outras chamandas "Boleto bancário", "Cartão de crédito" e "Pix". Onde a tabela principal recebe as informações de: Boleto bancário, cartão de crédito e pix.

Entrega: possui status e códigos de rasreio.
A tabela entrega contém o atributo "trackin" que liga a chave primária e o código de rastreio. E o status eu dei o atributo ENUM, com os valores: enviado e entregue.
