# Carteira

Crie uma classe onde o usuário poderá instanciar uma carteira de um jogo de rpg, a carteira pode armazenar ouro e prata, a carteira terá um limite de peso e não pode ser ultrapassado, gerando um erro caso a quantidade de moeda depositada ultrapassar o limite de peso. Para melhorar a experiência do usuário a carteira deve converter automaticamente as moedas.


Regras:
- A carteira armazena apenas ouro e prata;
- A carteira tem um limite de peso e deve lançar um erro se for ultrapassado;
- O peso máximo da carteira deve ser informado na inicialização;
- A carteira deve converter automaticamente prata para ouro quando for possível; 
- O cambio é 5 moedas de prata para 1 moeda de ouro;
- O peso das moedas é o mesmo;
- A carteira deve possuir os métodos `.deposit` e `.withdraw` que devem receber os parâmetros quantidade e tipo de moeda;
