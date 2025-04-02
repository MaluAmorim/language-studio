# language-studio

Neste projeto são utilizadas 4 sentenças para analise no languege studio. Essas sentenças são analisadas para determinar o estado da pessoa, positivo ou negativo, referente ao que foi dito sobre a localidade visitada. São utilizadas palavras chaves para conseguir determinar o estado da pessoa naquela avaliação.

## Coleta das sentenças

Essas sentenças foram coletadas no google conforme imagem:

![image](https://github.com/user-attachments/assets/d2cd89a0-6552-4424-8b7b-410c818a99b5)

Dentre todas as avaliações existentes, foram coletadas somente 4 que variam na quantidade de estrelas para termos perpectivas diferentes e poder avaliar diferentes graus de avaliações.

## Analise das sentenças no Language Studio

Conforme arquivo input/sentencas-utilizadas.md, foram coletadas 4 sentenças. Todas as 4 foram analisadas conforme imagens abaixo:

**1.**
![image](https://github.com/user-attachments/assets/56329b24-516d-4df7-84f5-6b41403d0483)

Essa primeira sentença teve um Documento sentiment e Sentence sentiment 100% positivo. Foram encontrados dois Targets e o assessment mais baixo foi de 96%.

**2.**
Sentenças analisadas | Sentimento da sentença/Opnião
--------- | ------
![image](https://github.com/user-attachments/assets/a0c4aaaf-3627-49cc-a408-33fea8357f8d) | ![image](https://github.com/user-attachments/assets/19ed5b13-8115-4129-b8de-1e881067d547)
![image](https://github.com/user-attachments/assets/9a6c6602-8c30-4d05-9eec-9322136e53c6) | ![image](https://github.com/user-attachments/assets/b974356d-e605-4535-98c8-5ade7935a00b)
![image](https://github.com/user-attachments/assets/c4ace5e6-f389-4a7f-a766-69915f2c58cf) | ![image](https://github.com/user-attachments/assets/db6d38f3-b454-4a92-b697-6d80109ef255)
![image](https://github.com/user-attachments/assets/ab718ef5-767f-407e-bf28-b62de6da9e18) | ![image](https://github.com/user-attachments/assets/bf233a5e-5f97-4919-9559-3f357a39f11d)
![image](https://github.com/user-attachments/assets/fb1a3724-5b7e-4c0a-9be9-bf4051ddeaf4) | ![image](https://github.com/user-attachments/assets/1a24e1ea-7547-4b4d-b550-e18da89329fb)
![image](https://github.com/user-attachments/assets/41b6162f-467e-48d6-b29e-0109bab7d1b9) | ![image](https://github.com/user-attachments/assets/ba6beabb-72ed-4d6f-8f66-a9697d71690f)
![image](https://github.com/user-attachments/assets/4076e0ad-5956-49bc-8ee6-3275d3e131fa) | ![image](https://github.com/user-attachments/assets/29649fd4-c112-486f-bcec-b839cf14326e)

Texto completo | Resultado final da Analise do documento
--------- | ------
![image](https://github.com/user-attachments/assets/6d876b4d-1be7-4d37-8494-5d1af0fa95d2) | ![image](https://github.com/user-attachments/assets/a86fc213-0f09-48de-bdf5-c0e339636d30)

Conforme esta segunda analise, foi identificado que nem sempre é obtida uma opnião para cada sentença mas é apresentado o sentimento geral dela. Creio que mesmo ele não tendo sido capaz de enxergar esses targets e assessments, nós podemos ter uma idiea de quais seriam eles. Como na 5° setença onde diz "Vou comprar frequentemente e aproveito para um lanche nas lojinhas de conveniência que tem no térreo" nós podemos deduzir que, em minha opnião, o **target** seria *comprar* e o **assessment** seria *frequentemente* onde podesse deduzir que esta é uma sentença possitiva, apesar de eu não ser capaz de informar uma porcentagem, pois o consumidor informa que voltará a fazer compras no local.

**3.**
Sentenças analisadas | Sentimento da sentença/Opnião
--------- | ------
![image](https://github.com/user-attachments/assets/67075c80-df38-4c11-b240-3c033f6d548a) | ![image](https://github.com/user-attachments/assets/09b49cc7-ba3f-40ef-bb0c-ce614d6ced61)
![image](https://github.com/user-attachments/assets/f9801567-f384-4be8-b06b-ca3a210315d1) | ![image](https://github.com/user-attachments/assets/d2c8b849-365b-413f-a077-f56ccb5d37b2)
![image](https://github.com/user-attachments/assets/470416aa-db7f-4b7a-8722-e4b6bd36bf41) | ![image](https://github.com/user-attachments/assets/3620e511-f178-451a-94a6-9b1b030d3b43)

Texto completo | Resultado final da Analise do documento
--------- | ------
![image](https://github.com/user-attachments/assets/e83b9735-2b86-485c-80f6-0f31fefe7182) | ![image](https://github.com/user-attachments/assets/e5babbab-8c12-4559-9c9a-b300022db9fd)

A casos intrigantes como nesta analise onde ocorre de todos os assessments da primeira sentença serem de 100% mas ele dizer que o sentimento da sentença é de 99% possitivo e 1% neutro. Na segunda ser 98% positivo na opnião oque da marge para que realmente tenha 2% neutro, porém em meu ponto de vista há a chance de ser observado um ponto negativo que é a parte "na Internet, há coisas que vc encontra com valores melhores." pois informa que a loja possuí produtos com preços mais altos do que o encontrado em outros lugares, dando assim uma porcentagem negativa para esta sentença.

Com isso podemos deduzir que o Language Studio ainda tem alguns pontos onde ele não consegue identificar certos tagets e assessments, mas mesmo com esses "furos" é uma ferramenta que consegue auxiliar e muito nas analises das avaliações e comentários dos clientes.

**4.**
Sentenças analisadas | Sentimento da sentença/Opnião
--------- | ------
![image](https://github.com/user-attachments/assets/4da9dcb5-7e66-4190-b674-917bf8adef5d) | ![image](https://github.com/user-attachments/assets/8b9228c8-1049-4cff-affa-1b562fbb0a3b)
![image](https://github.com/user-attachments/assets/6b7014de-af7f-4b48-ab86-944bb2d069a3) | ![image](https://github.com/user-attachments/assets/9ec15d36-da47-4d68-9e49-64ae85c3518c)
![image](https://github.com/user-attachments/assets/cd5d351c-2c42-4f9e-894d-7bf4dc7a5daf) | ![image](https://github.com/user-attachments/assets/7f79e5b5-9fd6-4929-8ddb-ac9dff59179e)

Texto completo | Resultado final da Analise do documento
--------- | ------
![image](https://github.com/user-attachments/assets/6df28228-5967-4e0f-954d-8729c7cedbe7) | ![image](https://github.com/user-attachments/assets/f1d1e748-c627-4816-80d4-0685e7351a12)

Apesar do observado nas demais analises podemos ver que mesmo com suas falhas em identificar pontualmente algumas palavras chaves, ele é capaz não só de ideitificar assessments possitivos mas também negativos.

## Conclusão
Mesmo com suas impefeições, deixando claro que são bem pontuais não ocorrendo frequentemente, esse é um recurso muito bom e que eu me proporia a utiliza-lo pois o mesmo consegue gerar boa analises expressando bem aquilo que o cliente esta sentindo.
