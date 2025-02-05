# Desafio de Front-end

Criar um web app que liste cidades específicas (listadas abaixo) e, após a seleção de alguma por parte do usuário, exiba uma tela de detalhes da cidade escolhida com informações do seu clima através de uma API pública de dados meteorológicos.

## Sugestões de APIs

- https://www.openweathermap.org/current
- https://www.weatherapi.com

## Layout
Tela inicial: 
![image](https://github.com/user-attachments/assets/25d169fe-a037-4d18-9827-c9fae02b6f57)

Exemplo de tela após selecionar
![image](https://github.com/user-attachments/assets/c0a2844c-736f-4f56-b5a6-b5cd9332b3b4)


## Hospedagem

O projeto precisa ser publicado numa das duas opções abaixo:

- [Netlify](https://www.netlify.com)
- [Vercel](https://www.vercel.com)

## Requisitos de avaliação

- Faça um fork deste repositório;
- As cidades listadas devem ser:
    - Dallol (NG);
    - Fairbanks (US);
    - Londres (GB);
    - Recife (BR);
    - Vancouver (CA);
    - Yakutsk (RU).
- Implementação de testes unitários;
- Fidelidade ao layout enviado;
- Frameworks JavaScript opcional (de preferência, nesta ordem 😉):
    - React com Vite;
    - React com Next.js;
    - Vue;
    - Angular.
- Responsividade atendendo 3 breakpoints:
    - Smartphone;
    - Tablet;
    - Desktop.

## Observações

- Você deve usar os ícones do layout que melhor se encaixarem em cada condição climática;
- Considere os horários 3:00, 9:00, 15:00 e 21:00 para as definições das temperaturas de Dawn, Morning, Afternoon, Night, respectivamente.
- Siga a seguinte lógica para mudar as cores do layout:
    - temperatura abaixo de 5º: fundo cinza (#C0C0C0) com texto preto
    - temperatura entre 6 e 15º: fundo azul claro (#87CEFA) com letra branca
    - temperatura de 16 a 25º: fundo azul escuro (#00BFFF) com letra branca

## Diferenciais

- Rodar a aplicação fazendo o uso de um container do Docker.

Agora é com você! Faça o fork e responda o nosso contato com o link, ok?

Boa sorte!
