# Meus Gastos

Aplicativo Android desenvolvido em Kotlin com o objetivo de registrar, visualizar e gerenciar seus gastos pessoais de forma prática e eficiente.

## Funcionalidades

-  Cadastro de novos gastos (nome, valor, data e descrição)
-  Listagem de todos os gastos registrados
-  Exclusão de gastos individualmente
-  Persistência de dados local com Room Database
-  Interface responsiva com Material Design
-  Armazenamento local (não requer conexão com internet)

## Funcionalidades Implementadas

1. **Cadastro de Gastos**: permite ao usuário inserir nome, valor, data e uma descrição opcional.
2. **Listagem de Gastos**: exibe todos os gastos salvos em um RecyclerView de forma clara e organizada.
3. **Exclusão de Gastos**: cada item possui um botão de lixeira que permite remover gastos individualmente.
4. **Persistência com Room**: todos os dados são salvos localmente no dispositivo, mesmo ao fechar o app.
5. **Navegação entre Fragments**: fluxo intuitivo entre tela inicial e tela de cadastro com NavController.

## Tecnologias e Bibliotecas Utilizadas

- **Linguagem**: Kotlin
- **Arquitetura**: MVVM (Model-View-ViewModel)
- **Persistência**: Room Database
- **UI**: ViewBinding, Material Design, RecyclerView, ConstraintLayout
- **AndroidX**: Navigation Component, LiveData, Lifecycle

## Estrutura de Pastas
  meusgastos
 ┣ *adapter           # Adapter do RecyclerView
 ┣ *model             # Entidade, DAO, Database, Repository, ViewModel
 ┣ *ui                # Fragments e layouts
 ┣ *res               # Strings, ícones e layouts
 ┗ MainActivity.kt     # Ponto de entrada da aplicação

## Como rodar o projeto
 Requisitos

- **Android Studio Giraffe ou mais recente**
- **Android SDK 21+ (API mínima 21)**
- **Emulador configurado ou dispositivo real com Android 5.0+**
- **Computador com memória ram no mínimo 8gb** 

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/meus-gastos.git

Autor
Patrini Dantas de Melo
