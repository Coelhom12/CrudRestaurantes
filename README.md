**Gestão de Restaurantes**

Este é um aplicativo de gerenciamento de restaurantes desenvolvido em Flutter com Firebase. Ele permite adicionar, editar e excluir restaurantes, incluindo informações como nome, descrição e tipo de comida. O aplicativo utiliza uma paleta de cores amigável e acolhedora, com tons de bege e detalhes em marrom para criar uma interface visualmente agradável.


**Funcionalidades**

Adicionar Restaurante: Crie novos registros com informações detalhadas.

Editar Restaurante: Atualize informações existentes de forma simples.

Excluir Restaurante: Remova registros facilmente.

Persistência de Dados: Utiliza Firebase Firestore para salvar os dados de forma segura e em tempo real.

**Estrutura de Pastas**

bash

Copiar código

lib/
│
├── main.dart                    # Arquivo principal que inicia o app
├── firebase_options.dart        # Configurações do Firebase
│
├── models/
│   └── restaurante.dart         # Modelo de dados para os restaurantes
│
└── screens/
    ├── lista_restaurantes.dart  # Tela principal que lista os restaurantes
    ├── adicionar_restaurante.dart # Tela para adicionar um novo restaurante
    └── editar_restaurante.dart  # Tela para editar um restaurante existente
    
**Tecnologias Utilizadas**
Flutter: Para desenvolvimento do aplicativo.

Firebase Firestore: Para armazenamento e persistência de dados em tempo real.

Dart: Linguagem de programação principal do Flutter.

**Como Rodar o Projeto**

Clone o repositório:

bash

Copiar código

git clone <URL_DO_REPOSITORIO>

**Instale as dependências:**

arduino

Copiar código

flutter pub get

Configure seu projeto Firebase e adicione o arquivo google-services.json na pasta android/app.

Execute o aplicativo:

arduino

Copiar código

flutter run
