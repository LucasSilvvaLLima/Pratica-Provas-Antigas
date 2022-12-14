# Pratica-Provas-Antigas
Enunciados:
PROVA 1:

1. Fábio tem um quiosque de coco, ele vende somente Água engarrafada e Coco fechado, faça um programa para auxiliá-lo no controle de suas vendas.

a) Após inserir os valores de Água engarrafada e Coco fechado e clicar no botão "Abrir o quiosque", valide as quantidades da seguinte forma:

    a.1) Se a quantidade de Água engarrafada for menor que 100, exiba a mensagem "Com essa quantidade de Água engarrafada não dá para abrir o quiosque" e não faça mais nada;  

    a.2) Se a quantidade de Coco fechado for menor que 200, exiba a mensagem "Com essa quantidade de Coco fechado não dá para abrir o quiosque" e não faça mais nada;

    a.3) Se a quantidade de Água engarrafada estiver entre 100 e 1000, exiba a mensagem "Engarrafe mais água de coco" e siga para a validação a.4);

    a.4) Se a quantidade de Coco fechado estiver entre 200 e 2000, exiba também a mensagem "Compre mais cocos" e siga para o item b).



b) Se as validações passarem, atualize o estoque inicial dos dois produtos no sistema e atualize também a mensagem que mostra esses estoques na tela.



c) Ao preencher os campos para registrar venda e clicar em "Registrar a Venda" faça o seguinte:

    c.1) Exiba a seguinte mensagem (não deve apagar as anteriores):  

        "Com a venda de XXXX de YYYY o saldo no estoque é de ZZZZ",  

    OBS:  
        XXXX é a quantidade de produto vendido;

        YYYY é o produto que foi vendido;

        ZZZZ é o estoque atual do produto;



d) Ao clicar no botão "Encerrar o Turno" faça:

    d.1) Apague todas as mensagens na página; 

    d.2) Exiba as seguintes mensagens: 

        Vendas de Água engarrafada

        Saldo de produto no estoque: XXXX 

        Quantidade de vendas: YYYY

        Porcentagem das vendas: ZZZZ



        Vendas de Coco fechado 

        Saldo de produto no estoque: XXXX 

        Quantidade de vendas: YYYY

        Porcentagem das vendas: ZZZZ



        Obs: A "porcentagem das vendas" é a quantidade vendida daquele produto / quantidade de vendas total. 



![image](https://user-images.githubusercontent.com/111443602/197091298-eee8edb1-1079-4009-acc3-ebdacdac9aaf.png)
![image](https://user-images.githubusercontent.com/111443602/197091398-6b5739f2-280c-4764-9ab6-a6d3093315fe.png)


PROVA 2: 

2. Crie um programa que ilustre o quanto o Zé Buduia reage a bebidas alcóolicas. Use o arquivo .html em anexo e NÃO MEXA nele. Acrescente somente o conteúdo da tag <script>. Quem alterar o conteúdo .html terá um desconto de 3pts na prova. Não precisa enviar as imagens, pois todos usarão imagens com o mesmo nome e o professor já as tem!


a) O programa deve ter as sequintes entradas (já está tudo pronto no arquivo .html em anexo, por isso 0 pontos):
    - Pergunte quantas taças de vinho ele bebeu.
    - Pergunte também o preço de uma taça de vinho.
    - Pergunte ainda, numa combo qual sua tolerância a álcool com os seguintes itens na combo:
        Fraco pra bebida
        Bebe todo final de semana
        Só fica bêbado com Querosene

b) Abaixo dessas entradas, deve haver um botão "Tomar vinho". Ao clicar nesse botão deve acontecer o seguinte:
 - Caso a quantidade de taças de vinho for menor que 0 ou maior que 30, exiba num alert "Só é possível beber de 0 a 30 taças". Caso contrário, vá para o item c)
 - Caso o preço da taça de vinho for menor que 0.01, exiba num alert "Onde já se viu vinho grátis?". Caso contrário, vá para o item c)

c) Abaixo do botão, na própria página, não num alert, deve aparecer a seguinte frase:
    Zé Buduia tomou um total de X taças de vinho, pagando R$ Y por isso
OBS: Calcule Y usando o valor da taça informado em a)


d) Abaixo do texto do item c), deve aparecer ou a figura de uma pessoa apenas sorridente (levemente embriagada) ou de algúem muito eufórico (visivelmente embriagada) ou de alguém super bêbado (exemplos: desmaiado com garrafa na mão ou com os olhos tortos). Use as imagens em anexo neste anunciado. O critério para isso será:
   d.1) Se a pessoa for "Fraco pra bebida"
   - levemente embriagada: 1 a 2 taças
   - visivelmente embriagada: 3 a 4 taças
   - super bêbado: 5 ou mais taças

   d.2) Se a pessoa for "Bebe todo final de semana"
   - levemente embriagada: 3 a 4 taças
   - visivelmente embriagada: 5 a 7 taças
   - super bêbado: 8 ou mais taças

   d.3) Se a pessoa for "Só fica bêbado com Querosene"
   - levemente embriagada: 10 a 13 taças
   - visivelmente embriagada: 14 a 19 taças
   - super bêbado: 20 ou mais taças

e) Atenção! Caso o usuário clique várias vezes no botão, as imagens não devem ficar se multiplicando! Deve sempre aparecer uma imagem na página
