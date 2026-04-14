# Olá! Eu sou o Rudson Alves
## Hello! I'm Rudson Alves

[Leia em Português](#pt) | [Read in English](#en)

---

<a name="pt"></a>
## Sobre Mim

Minha jornada sempre foi guiada pela curiosidade científica e pela oportunidade de aplicar tecnologia de forma prática. Comecei no meio acadêmico e agora foco minhas habilidades no desenvolvimento de software.

Sou Bacharel em Física com Mestrado em Semicondutores pela UNICAMP. Atuei como professor de Física para Engenheiros e Cientistas da Computação na Universidade de Vila Velha por 23 anos, onde fundei grupos de Linux e desenvolvimento de jogos em Python, promovendo a colaboração e aprendizado entre os estudantes, além de participar na organização dos eventos ENCASOFT (Encontro Capixaba de Software Livre) no Espírito Santo.

Em 2021, fiz uma transição de carreira para o desenvolvimento de software, inicialmente focando em GoLang e, nos últimos 18 meses, em Flutter. Tenho desenvolvido provas de conceito que demonstram minhas habilidades e que me ajudaram a aprofundar meu conhecimento na plataforma.

### Habilidades e Experiência em Educação e Gestão

Durante meu trabalho como professor, adquiri e desenvolvi diversas habilidades interpessoais e de liderança:

- **Coordenação e Liderança**: Projetei, planejei e implementei dois laboratórios de física básica, abrangendo toda a física de nível universitário, incluindo mecânica, ondas, termodinâmica, óptica, eletricidade e introdução à física moderna. Fui coordenador desses laboratórios desde sua criação, sendo responsável por toda a gestão e implantação de experimentos.
- **Gestão Acadêmica**: Atuei como coordenador de ensino da disciplina de Física, gerenciando uma equipe de 7 a 9 professores (mestres e doutores) por mais de 15 anos.
- **Inovação em Ensino**: Implementei técnicas pedagógicas, como **Just in Time Teaching** e **Peer Instruction**, para promover um aprendizado mais ativo e engajado dos estudantes.

Essas experiências me permitiram desenvolver habilidades de gestão, liderança de equipe e comunicação eficaz em ambientes acadêmicos, além de promover minha capacidade de adaptação e inovação.

## Tecnologias e Ferramentas

- **Linguagens**: Dart, GoLang, Python
- **Frameworks**: Flutter
- **Banco de Dados**: Firebase Firestore, Realtime Database, Sqflite, Shared Preferences
- **Backend e Serviços**: Parse Server, Firebase Emulator Suite (Authentication, Firestore, Realtime Database, Functions, Storage, Extensions)
- **Gerenciamento de Estado**: MobX, Flutter Bloc
- **Integração de APIs**: REST APIs, Google Maps Integration, Cloud Functions
- **Utilidades**: Geolocator, Path Provider, URL Launcher, PDF Generation
- **Design e UI**: Google Fonts, Flutter Colorpicker, Onboarding Overlay
- **Containers e Ambientes de Desenvolvimento**: Docker (para emulação do Parse Server e consistência de ambientes)

## Projetos em Destaque

- **[Boards](https://github.com/rudsonalves/boards)**: Boards é uma evolução do projeto **Virtual Trade Store (BgBazzar)**, criado para revisar e aprimorar o código original seguindo as orientações mais recentes do **Flutter Team** e incorporando melhorias baseadas nos princípios da **Arquitetura Limpa**, de Robert C. Martin. Este projeto busca não apenas refinar a arquitetura, mas também explorar novas ferramentas e práticas para alcançar maior consistência e escalabilidade.
  As principais melhorias incluem:
  - **Conformidade com as Diretrizes do Flutter Team:** A estrutura foi reorganizada para refletir uma abordagem moderna, com camadas claramente definidas, como **UI Layer**, **Logic Layer** e **Data Layer**.
  - **Gerenciamento de Estado Otimizado:** O uso de `ValueNotifier` no Store permitiu um gerenciamento de reatividade simples e eficiente, mantendo o foco em uma solução prática e alinhada às necessidades do projeto.
  - **Adoção do Firebase:** Substituí o Parse Server pelo Firebase, proporcionando melhor desempenho, integração nativa com Flutter e maior flexibilidade para o projeto. Essa migração também serviu para revisar as interfaces, garantindo maior desacoplamento e modularidade.
  - **Substituição do Sistema de Pagamentos:** O sistema de pagamentos MercadoPago foi substituído pelo Stripe (ainda em desenvolvimento), trazendo maior escalabilidade e suporte para transações globais.
  - **Reescrita de Funções Cloud:** As funções Firebase Cloud foram reescritas de JavaScript para TypeScript, aumentando a consistência do código, a robustez no tratamento de erros e a clareza no desenvolvimento.
  O Boards é um exemplo de como a adaptação às melhores práticas e uma abordagem crítica ao próprio código podem resultar em um aplicativo mais robusto, escalável e alinhado às exigências modernas de desenvolvimento.
- **[Delivery App](https://github.com/rudsonalves/delivery)**: Aplicativo de entrega desenvolvido em Flutter, com integração ao Google Maps e Firebase. O objetivo deste projeto foi aprofundar meus conhecimentos no ecossistema do Firebase e implementar funcionalidades de navegação, além de melhorar minha gestão de projetos com o Scrum. Utilizei o Firebase Emulator Suite para simular as funcionalidades de Authentication, Firestore, Realtime Database, Functions, Storage e Extensions durante o desenvolvimento.
- **[Loja Virtual de Trocas](https://github.com/rudsonalves/bgbazzar)**: Aplicativo para vendas e trocas de produtos usados, utilizando Parse Server para gerenciamento de dados. O objetivo principal deste projeto foi explorar o uso do Parse Server como uma API, familiarizando-me com a ferramenta e expandindo minhas habilidades no desenvolvimento utilizando APIs pré-configuradas, como o Parse Server. Durante o desenvolvimento, utilizei Docker para emular o Parse Server e garantir a consistência dos ambientes de desenvolvimento, permitindo uma integração contínua e eficiente com os serviços backend. A versão final emprega o backend hospedado no Back4App e está aguardando uma melhor opção de pagamentos, para ser finalizada.
- **[Trainers Stopwatch](https://github.com/rudsonalves/trainers_stopwatch)**: Aplicativo de múltiplos cronômetros digitais, utilizando Flutter Bloc para o gerenciamento de estados e eventos dos botões, proporcionando um controle mais robusto e organizado. O objetivo principal deste projeto foi revisitar o Flutter Bloc, explorando um projeto que permitisse utilizá-lo de maneira mais eficiente, indo além de um mero gerenciador de estado. No entanto, após experimentação, decidi não estender o uso do Bloc para outras partes do projeto.
- **[LabCalc2](https://github.com/rudsonalves/labcalc2)**: Calculadora de laboratório que realiza cálculos com incertezas e médias com desvios. Este projeto foi uma demanda pessoal que visa facilitar cálculos laboratoriais complexos para Android, sendo motivada pela necessidade de ferramentas mais acessíveis para estudantes e profissionais. Possuo também uma versão em Python2 com PyQt, desenvolvida para Linux/Windows durante meu período como professor.
- **[Finances](https://github.com/rudsonalves/finances)**: Meu primeiro projeto em Flutter, baseado no projeto do [@devkaio](https://www.youtube.com/@devkaio). Esse projeto foi um grande incentivo para me profissionalizar no desenvolvimento Flutter, oferecendo desafios interessantes e proporcionando aprendizado sobre boas práticas e padrões de design.
- **[Bares](https://github.com/rudsonalves/bares)**: Projeto realizado em paralelo ao Finances, focando no desenvolvimento de uma API em GoLang, com autenticação baseada em token, para posteriormente integrar com um app Flutter. Meu envolvimento com Flutter estimulou minha criatividade e me levou a explorar diferentes possibilidades de desenvolvimento, o que acabou postergando a continuidade do desenvolvimento da API em GoLang. Cheguei a trabalhar em uma segunda API para um serviço de medicina online, mas o projeto não prosseguiu.

---

Atualmente, estou focado em aprimorar minhas habilidades em Flutter e suas diversas ferramentas, sempre buscando a criação de um código mais limpo e bem estruturado. Busco constantemente novos projetos e desafios para expandir meu conhecimento e desenvolver ainda mais minhas habilidades como desenvolvedor.

Estou aprimorando meu inglês técnico para colaborar efetivamente em projetos internacionais e integrar equipes globais.

## Conecte-se Comigo

Estou aberto a novas oportunidades de colaboração e desenvolvimento. Sinta-se à vontade para entrar em contato!

- [LinkedIn alvesdev67](https://www.linkedin.com/in/alvesdev67/)
- [GitHub rudsonalves](https://github.com/rudsonalves)

---

<a name="en"></a>
## About Me

My journey has always been driven by scientific curiosity and the opportunity to apply technology in a practical and impactful way. I began in the academic field and now focus my skills on software development.

I hold a Bachelor's degree in Physics with a Master's in Semiconductors from UNICAMP. I worked as a Physics professor for Engineers and Computer Science students at the University of Vila Velha for 23 years, where I founded Linux and Python game development groups, promoting collaboration and learning among students. I also participated in organizing ENCASOFT (Capixaba Free Software Meeting) in Espírito Santo.

In 2021, I transitioned my career to software development, initially focusing on GoLang and, over the past 18 months, Flutter. I have developed proof-of-concept projects that showcase my skills and have helped me deepen my knowledge of the platform.

### Skills and Experience in Education and Management

During my work as a professor, I acquired and developed several interpersonal and leadership skills:

- **Coordination and Leadership**: I designed, planned, and implemented two basic physics laboratories, covering all university-level physics, including mechanics, waves, thermodynamics, optics, electricity, and an introduction to modern physics. I coordinated these laboratories since their creation, being responsible for all management and implementation of experiments.
- **Academic Management**: I served as coordinator of the Physics course, managing a team of 7 to 9 professors (Masters and PhDs) for over 15 years.
- **Teaching Innovation**: I implemented innovative teaching techniques, such as **Just in Time Teaching** and **Peer Instruction**, to foster more active and engaging learning among students.

These experiences allowed me to develop management skills, team leadership, and effective communication in academic environments, as well as promoting my adaptability and innovation capabilities.

## Technologies and Tools

- **Languages**: Dart, GoLang, Python
- **Frameworks**: Flutter
- **Databases**: Firebase Firestore, Realtime Database, Sqflite, Shared Preferences
- **Backend and Services**: Parse Server, Firebase Emulator Suite (Authentication, Firestore, Realtime Database, Functions, Storage, Extensions)
- **State Management**: MobX, Flutter Bloc
- **API Integration**: REST APIs, Google Maps Integration, Cloud Functions
- **Utilities**: Geolocator, Path Provider, URL Launcher, PDF Generation
- **Design and UI**: Google Fonts, Flutter Colorpicker, Onboarding Overlay
- **Containers and Development Environments**: Docker (for Parse Server emulation and environment consistency)

## Featured Projects

- **[Boards](https://github.com/rudsonalves/boards)**: Boards is an evolution of the **Virtual Trade Store (BgBazzar)** project, created to review and refine the original code following the latest guidelines from the **Flutter Team** and incorporating improvements based on the principles of **Clean Architecture** by Robert C. Martin. This project aims not only to enhance the architecture but also to explore new tools and practices to achieve greater consistency and scalability.
  Key improvements include:
  - **Compliance with Flutter Team Guidelines:** The structure was reorganized to reflect a modern approach, with clearly defined layers such as **UI Layer**, **Logic Layer**, and **Data Layer**.
  - **Optimized State Management:** The use of `ValueNotifier` in the Store enabled simple and efficient reactivity management, focusing on a practical solution tailored to the project's needs.
  - **Adoption of Firebase:** The Parse Server was replaced with Firebase, providing better performance, native integration with Flutter, and increased flexibility for the project. This migration also allowed for a comprehensive review of interfaces, ensuring greater decoupling and modularity.
  - **Replacement of the Payment System:** The MercadoPago payment system was replaced with Stripe (still under development), offering greater scalability and support for global transactions.
  - **Cloud Functions Rewritten:** Firebase Cloud Functions were rewritten from JavaScript to TypeScript, improving code consistency, error handling robustness, and development clarity.
  Boards is an example of how adhering to best practices and critically evaluating one’s own code can result in a more robust, scalable, and modern application aligned with current development demands.
- **[Delivery App](https://github.com/rudsonalves/delivery)**: Delivery application developed with Flutter, integrating Google Maps and Firebase. The objective of this project was to deepen my knowledge of the Firebase ecosystem and implement navigation features, as well as to improve my project management with Scrum. I used the Firebase Emulator Suite to simulate Authentication, Firestore, Realtime Database, Functions, Storage, and Extensions during development.
- **[Virtual Trade Store](https://github.com/rudsonalves/bgbazzar)**: Application for buying and trading used products, using Parse Server for data management. The main objective of this project was to explore the use of Parse Server as an API, familiarizing myself with the tool, and expanding my skills in using pre-configured APIs such as Parse Server. During development, I used Docker to emulate Parse Server and ensure consistency in development environments, allowing for seamless integration with backend services. The final version employs a backend hosted on Back4App and is awaiting a better payment option to be finalized.
- **[Trainers Stopwatch](https://github.com/rudsonalves/trainers_stopwatch)**: Multi-digital stopwatch application, using Flutter Bloc for state management and button event handling, providing a more robust and organized control. The main objective of this project was to revisit Flutter Bloc, exploring a project that allowed me to use it more effectively, beyond just state management. However, after experimenting, I decided not to extend the Bloc to other parts of the project.
- **[LabCalc2](https://github.com/rudsonalves/labcalc2)**: Laboratory calculator that performs calculations with uncertainties and average deviations. This project was a personal endeavor aimed at facilitating complex laboratory calculations for Android, driven by the need for more accessible tools for students and professionals. I also have a version in Python2 with PyQt, developed for Linux/Windows during my teaching period.
- **[Finances](https://github.com/rudsonalves/finances)**: My first Flutter project, based on [@devkaio's project](https://www.youtube.com/@devkaio). This project was a significant motivator to professionalize in Flutter development, providing interesting challenges and learning opportunities regarding best practices and design patterns.
- **[Bares](https://github.com/rudsonalves/bares)**: A project developed alongside Finances, focusing on building a GoLang API with token-based authentication, which would later integrate with a Flutter app. My work with Flutter boosted my creativity and led me to explore different development possibilities, which eventually delayed the continuation of the API development in GoLang. I also started work on a second API for an online medical service, but the project did not proceed.

---

Currently, I am focused on improving my skills in Flutter and its various tools, always striving for cleaner and more structured code. I am constantly seeking new projects and challenges to expand my knowledge and further develop my abilities as a developer.

I am improving my technical English to effectively collaborate on international projects and integrate into global teams.

## Connect With Me

I am open to new opportunities for collaboration and development. Feel free to reach out!

- [LinkedIn alvesdev67](https://www.linkedin.com/in/alvesdev67/)
- [GitHub rudsonalves](https://github.com/rudsonalves)
