# Player de Vídeo com Módulos - Aplicativo React

![Player de Vídeo com Módulos](link_para_imagem)

Este projeto é um aplicativo React desenvolvido com Vite e gerenciamento de estado usando Zustand. O objetivo principal é criar um player de vídeo interativo que permita aos usuários selecionar e assistir a diferentes vídeos organizados em módulos (ou playlists).

## Funcionalidades Principais

1. **Player de Vídeo Interativo:** O aplicativo possui um player de vídeo que reproduz os vídeos selecionados pelos usuários. O player é capaz de exibir vídeos de diversos formatos e fornecer controles de reprodução, como pausar, avançar, retroceder e ajustar o volume.

2. **Listagem de Módulos:** Os módulos (ou playlists) são apresentados em uma lista para que os usuários possam navegar facilmente entre eles. Cada módulo contém um conjunto de vídeos relacionados a um tópico específico.

3. **Listagem de Vídeos:** Dentro de cada módulo, os vídeos são listados em ordem, permitindo que os usuários vejam todos os vídeos disponíveis para um tópico específico.

4. **Reprodução Contínua:** Ao terminar a reprodução de um vídeo, o aplicativo reproduz automaticamente o próximo vídeo na sequência. Isso proporciona uma experiência contínua e ininterrupta ao assistir a vários vídeos consecutivamente.

5. **Troca Automática de Módulo:** Quando o último vídeo de um módulo é reproduzido, o aplicativo realiza automaticamente a troca para o próximo módulo. Isso permite que os usuários explorem e assistam a vídeos de diferentes tópicos de forma prática.

## Demonstração e Desenvolvimento

Para fins de desenvolvimento e demonstração, este aplicativo utiliza uma API simulada criada com o JSON Server. A API fornece os dados dos módulos e vídeos que são consumidos pelo aplicativo para criar a experiência do player de vídeo com múltiplos módulos.

## Como Executar o Projeto

1. Certifique-se de ter o Node.js instalado em sua máquina.

2. Clone este repositório para o seu ambiente local.

3. Instale as dependências do projeto usando o seguinte comando:

```bash
npm install
```

4. Inicie o servidor da API simulada (JSON Server) com o seguinte comando:

```bash
npm run server ou yarn server
```

5. Em outro terminal, inicie o aplicativo React:

```bash
npm run dev ou yarn dev
```

6. Acesse o aplicativo em seu navegador utilizando o endereço `http://localhost:5173/`.
