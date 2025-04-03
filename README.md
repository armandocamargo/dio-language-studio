# dio-language-studio

Foram coletadas 4 avaliações de clientes da loja Petz Osasco (conforme imagem abaixo), estas sentenças estão armazenadas no inputs/sentencas.md e serão utilizadas para a analise de sentimento e opnião do Azure Language Studio.

![image](https://github.com/user-attachments/assets/7ba832d2-37e6-4e62-b6e0-4d468522bf16)

## Analise das sentenças

1.
Parte | Sentença analisada | Sentimento da sentença e opnião
:--------- | :------: | -------:
1 | ![image](https://github.com/user-attachments/assets/65929d3e-e5f6-4003-b6b0-98c11775e7c6) | ![image](https://github.com/user-attachments/assets/a6d78903-5ac0-4286-96ce-8fd35a2263b6)
2 | ![image](https://github.com/user-attachments/assets/a2e0235d-f1db-4cd4-be37-b40da0598586) | ![image](https://github.com/user-attachments/assets/d11686a5-8f22-4cb1-9b1e-f8893cb64278)
3 | ![image](https://github.com/user-attachments/assets/c1beb1a0-d549-4281-b138-21970a68a395) | ![image](https://github.com/user-attachments/assets/2a19c85d-8b4c-4839-b33e-2c86d4b19fcf)
4 | ![image](https://github.com/user-attachments/assets/84a7b051-8b26-40d4-a1b0-3d4d4d49b696) | ![image](https://github.com/user-attachments/assets/760a62ad-939f-4530-81e6-bdd3fea95633)
5 | ![image](https://github.com/user-attachments/assets/02c69227-1d81-44c9-be9a-a757924c6ed5) | ![image](https://github.com/user-attachments/assets/a5cd6348-bed5-465e-afdd-13bf68df2514)

Avaliação analisada | Sentimento do documento
--------- | ------
![image](https://github.com/user-attachments/assets/e07b4c7c-de5c-47d0-9c47-b87cf75db405) | ![image](https://github.com/user-attachments/assets/ccc30d72-d641-4fd7-849f-11ec8037b07e)


A sentenças que não são geradas opniões, alguns realmente não a o que ser selecionado mas a outros onde é possível fazer essas identificação porém o Language não consegue identificar. É observado que ele não simplesmente determina o sentimento final como positivo, negativo ou neutro, ele também pode classificar como mesclado.

2.
Avaliação analisada | Sentimento do documento
--------- | ------
![image](https://github.com/user-attachments/assets/ca46d312-5ee0-45c9-9072-50de59ab9c42) | ![image](https://github.com/user-attachments/assets/2b58db29-6970-4cd1-bb7a-014fa2bb1dc7)

É curioso que mesmo ele determinando que a única opnião existente é classificada com 100% o resultado final é considerado como 99%.

3.
Parte | Sentença analisada | Sentimento da sentença e opnião
:--------- | :------: | -------:
1 | ![image](https://github.com/user-attachments/assets/8650d452-ff04-4127-a170-8a642da4d8f6) | ![image](https://github.com/user-attachments/assets/f9ef09da-4382-431f-bd5d-26bbfa2e054f)
2 | ![image](https://github.com/user-attachments/assets/b3adaaac-1cd5-4d2f-bd57-43d722c0baa7) | ![image](https://github.com/user-attachments/assets/db539e87-039a-4a39-91eb-927138c93f1d)
3 | ![image](https://github.com/user-attachments/assets/a4b895b3-4551-4ebc-b0b1-e8b4c2c5a0df) | ![image](https://github.com/user-attachments/assets/51eebfd3-d4bc-48f2-990d-87ecbcf2a0ff)

Avaliação analisada | Sentimento do documento
--------- | ------
![image](https://github.com/user-attachments/assets/c125507a-a9c0-46ec-b795-90fa0a435ab2) | ![image](https://github.com/user-attachments/assets/049cfcd2-94fe-4ef6-81eb-9b56e3b7a6eb)

O Language, apesar de não conseguir gerar opniões as vezes, ele consegue enxergar o sentimento geral da sentença e determinar se é positivo, negativo ou neutro.

4.
Parte | Sentença analisada | Sentimento da sentença e opnião
:--------- | :------: | -------:
1 | ![image](https://github.com/user-attachments/assets/5925a141-6950-4135-83ee-85503a60b350) | ![image](https://github.com/user-attachments/assets/57f1793e-420e-4d82-b209-48b313acaae5)
2 | ![image](https://github.com/user-attachments/assets/23061f8f-217b-4c97-8d47-98bf102b9e7f) | ![image](https://github.com/user-attachments/assets/7671ebfc-620c-40bb-9ff4-a6a4a9b3ccf5)

Avaliação analisada | Sentimento do documento
--------- | ------
![image](https://github.com/user-attachments/assets/ce2a1205-6e9d-4d09-ad0b-d7c0b0557299) | ![image](https://github.com/user-attachments/assets/15a32fc7-19c0-49f1-a739-4f9137d01ffe)

Foi escolhida está avaliação por ela conter abreviações como o "vc" para analisar se isso interferiria na analise do Language. Após ele efetuar as analises desta sentença foi observado que ele considerou ela como neutra, tanto na analise geral como nas individuais. Não consigo afirmar que este resultado tenha ocorrido exclusivamente por conta da abreviação do "você", mas é claro que esta analise não esta correta pois nas duas partes é possivel observar que são feitos comentários negativos referentes a loja tendo desta forma um sentimento negativo e não neutro.
