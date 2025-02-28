# Desconto Sustentável (Aplicativo mobile)

![Mkt Alimentos](https://github.com/user-attachments/assets/882439d5-2fea-42aa-a10b-859c6cfd2d5f)

O Desconto Sustentável é uma plataforma focada em reduzir o desperdício de alimentos, oferecendo produtos alimentícios com desconto e próximos da data de validade. O serviço conecta consumidores com varejistas e produtores que têm itens alimentícios que precisam ser vendidos rapidamente. Os usuários podem encontrar uma grande variedade de produtos, como mantimentos, refeições prontas e muito mais, todos com preços reduzidos devido à proximidade da data de validade. Esta iniciativa ajuda tanto o meio ambiente, minimizando o desperdício de alimentos, quanto os consumidores, fornecendo produtos acessíveis e de qualidade.

## Tecnologia

Projeto criado com React Native utilizando a plataforma Expo (SDK 52.0.0), acessível pelo Expo Go 2.32.19. O banco de dados utilizado é o Firebase Cloud Firestore.

## Configuração

- Instale o NodeJS;<br/>

- Instale as dependências com o comando "npm install" no diretório do projeto;<br/>

- Crie um arquivo .env na pasta raíz do projeto e adicione a API Key do Google Maps e as variáveis de conexão do Firebase ao arquivo, como no exemplo abaixo:
```
MAPS_API_KEY=AIzaSy1234567890abcdefgHIJKLMNOPQRST

FIREBASE_API_KEY = "AIzaSy1234567890abcdefgHIJKLMNOPQRST"
FIREBASE_AUTH_DOMAIN = "exemplo-app.firebaseapp.com"
FIREBASE_PROJECT_ID = "exemplo-app"
FIREBASE_STORAGE_BUCKET = "exemplo-app.firebasestorage.app"
FIREBASE_MESSAGING_SENDER_ID = "123456789012"
FIREBASE_APP_ID = "1:123456789012:web:abcdef1234567890abcdef"
```
A API Key do Google Maps é necessário para conseguir mostrar os supermercados presentes próximos ao usuário.<br/>
Já as variáveis do Firebase, são necessárias para se conectar ao banco de dados. Elas podem ser obtidas pelo site, nas configurações do projeto, em "Apps da Web".<br/>

- Utilize "npx expo start" para iniciar o aplicativo no modo desenvolvimento.

## Autores

- José Robson Cabral (Aluno do PPGASA);<br/>

- Paulo Rogério Barbosa (Orientador);<br/>

- Matheus Pedrosa Souza (Desenvolvedor do sistema);<br/>

- Mozart de Melo Alves (Coordenador do núcleo de pesquisa).