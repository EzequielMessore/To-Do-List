# LAB - Criando um app de lembretes e tarefas com Kotlin.
O curso pode ser acessado na plataforma da [Digital Innovation One](https://digitalinnovation.one/).

## Sobre o Autor
<img align="left" width="190" height="190" margin-right="150px" src="https://drive.google.com/uc?export=view&id=1Kn8aRAQbLZx9BejvZD2eK8kLhp8j9i5m"> Sou um desenvolvedor Android que ama novos desafios e não perde a oportunidade de aprender coisas novas, sou organizado, pontual e estou sempre disponível para o ajudar, procuro estar cercado de pessoas que extraem o melhor de mim, me ajudando a sempre desempenhar o meu máximo. Por isso, quero compartilhar com vocês um pouco do que sinto quando programo e retribuir com tudo o que sei.

[![Linkedin Badge](https://img.shields.io/badge/-Ezequiel_Messore-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ezequielmessore/)](https://www.linkedin.com/in/ezequielmessore/)  [![Gmail Badge](https://img.shields.io/badge/-ezequielmessore@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ezequielmessore@gmail.com)](mailto:ezequielmessore@gmail.com)

## <br />Descrição do Lab.
O objetivo do projeto é criar um App de `To do list` do zero mostrando o processo de desenvolvimento usando Kotlin, uma das linguagens de programação de maior ascensão dos últimos anos. Além disto, desafiar a evolução do App e entregar uma solução mais robusta pensando sempre na melhor experiência do usuário.

## Aulas e materiais de estudo.
- Aula - 01: Apresentação pessoal e apresentação do curso.
  - [Apresentação](https://drive.google.com/file/d/1KhneglCpya7VgAsczDsa7zXmpWkyo0XZ/view?usp=sharing)
- Aula - 02: Configurando nosso primeiro projeto.
- Aula - 03: Um pouco do Android Studio.
  - [Conheça o Android Studio](https://developer.android.com/studio/intro)
- Aula - 04: Temas
  - [Documentação dos temas](https://developer.android.com/guide/topics/ui/look-and-feel/themes?hl=pt-br)
  - Link de referência do [stackoverflow](https://stackoverflow.com/questions/22192291/how-to-change-the-status-bar-color-in-android/24997241#24997241)
  - Customização do Floating Action Button [stackoverflow](https://stackoverflow.com/questions/30969455/android-changing-floating-action-button-color/56158913#56158913)
- Aula - 05:  Começando por a mão na massa.
  - [Protótipo](https://xd.adobe.com/view/77c56d1f-232d-41e9-a220-371d51991646-2296/)
  - [Material Design](https://material.io/design)
- Aula - 06: Criando a tela criar tarefas.
- Aula - 07: ViewBinding e DatePicker.
  - [Documentação do View Binding](https://developer.android.com/topic/libraries/view-binding)
  - [Artigo sobre View Binding](https://medium.com/androiddevelopers/use-view-binding-to-replace-findviewbyid-c83942471fc)
- Aula - 08: Time Picker.
  - Problema com o TimeZone [stackoverflow](https://stackoverflow.com/a/60979837)
- Aula - 09: RecyclerView.
  - Documentação do [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=pt-br).
- Aula - 10: Mostrando lista de tarefas.
  - [Popup menu](https://material.io/components/menus#usage)
- Aula - 11: Editando tarefas.
- Aula - 12: Finalizando o app.
   - [Empty States](https://material.io/design/communication/empty-states.html#content)


## Desafios
Tornar nosso aplicativo um aplicativo resiliente que não perca nossas tarefas salvas quando é encerrado, para isto podemos usar a estratégia de salvar nossos dados localmente.  
Podemos fazer isto de duas maneiras usar nossas [Shared Preferences](https://developer.android.com/training/data-storage/shared-preferences?hl=pt-br) ou nosso [SQLite](https://developer.android.com/training/data-storage/sqlite) para utilizar os esses conceitos de uma maneira facilitada devemos usar as seguintes bibliotecas:

 - [Room](https://developer.android.com/training/data-storage/room): é um banco de dados que oferece uma camada de abstração sobre o SQLite, e nos ajuda a lidar melhor com a complexidade do mesmo.

 - [DataStore](https://developer.android.com/topic/libraries/architecture/datastore?hl=pt-br): é uma solução de armazenamento de dados que permite armazenar pares de chave-valor ou objetos tipados.