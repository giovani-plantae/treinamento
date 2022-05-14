# TAMAGOTCHI / ANIMAL VIRTUAL 

Crie uma classe onde poderá ser instanciado um ou mais tamagotchis (animais virtuais), contendo as funções básicas: comer, beber água, brincar, dormir, envelhecer, e morrer. O usuário também poderá pausar/continuar e reiniciar.

O tamagotchi irá rodar no console, não terá interface gráfica e suas interações serão feitas via comando, a comunicação e alertas devem ser feitos por `console.log` ou `console.alert`.


Regras:
- A classe do tamagotchi deve possuir métodos fluentes;
- O tamagotchi deve avisar quando estiver com fome, sede ou com vontade de brincar (sem spam);
- O tamagotchi deve acordar quando sentir alguma necessidade (antes de morrer);
- O tamagotchi não deve dormir enquanto sente alguma necessidade;
- Enquanto o tamagotchi estiver dormindo ele não pode comer, beber água ou brincar;
- Depois de morto não deve haver mais interações, apenas restart;