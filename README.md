# robotron-2000

Ao concluir o projeto pelo curso da Alura, percebi que o programa original estava com um erro:
  [erro-robotron-2000.webm](https://user-images.githubusercontent.com/110543447/223449169-70794168-9e71-4e79-815f-e506ee1c6464.webm)
  As estatísticas sempre somavam, não importava se eu clicava no '+' ou no '-'
  O código da implementação da função que manipula esses dados estava assim:
  ![image](https://user-images.githubusercontent.com/110543447/223449972-e493ae58-0aae-4d5c-9b79-b64aa9ae1ecb.png)

Não sei se é a melhor solução, mas resolvi passando o parâmetro 'operacao' para a função 'atualizaEstatisticas()' para decidir se soma ou subtrai:
  ![image](https://user-images.githubusercontent.com/110543447/223450799-4adb3601-444f-43a8-9114-21fb17e80e4a.png)
 
Agora funciona perfeitamente :)
  [robotron-2000-consertado.webm](https://user-images.githubusercontent.com/110543447/223451852-99f3d940-2fba-481a-96d4-2d1854489b8e.webm)

