# README - Projeto "Qual é o Animal?"

## Descrição do Projeto
O projeto "Qual é o Animal?" é um jogo interativo desenvolvido com o objetivo de educar crianças sobre animais de fazenda. Utilizando as ferramentas Unity e Vuforia, o jogo oferece uma experiência imersiva de realidade aumentada (RA), onde os jogadores identificam animais a partir de dicas e reconhecimento de imagens.

## Autores
- Danny Machado - 822141543
- João Victor Batista Barreto - 822138704
- Julia Caroline de Paiva Silva - 822150064
- Thais Aires Paiva - 822147596

## Professores Orientadores
- Evandro Catelani Ferraz
- Viktor Danko Perkusich Novaes
- Igor Colado Porto Martins
- José Francisco Toledo Melara

## Estrutura do Projeto

### 1. Resumo
Este trabalho descreve o desenvolvimento do jogo "Qual é o Animal?", utilizando Unity e Vuforia. O objetivo é educar crianças sobre animais de fazenda através de dicas e reconhecimento de imagens. A implementação inclui configuração de cenas no Unity, uso de RA com Vuforia e programação da lógica do jogo em C#.

### 2. Introdução
O avanço da tecnologia de RA oferece novas formas de interação e aprendizado. Este projeto apresenta o desenvolvimento de um jogo educativo que utiliza RA para ensinar crianças sobre animais de fazenda. A proposta é criar uma experiência interativa e educativa, onde os jogadores identificam animais com base em dicas fornecidas.

### 3. Desenvolvimento

#### Ferramentas Utilizadas
- **Unity:** IDE para criação de jogos 3D.
- **Vuforia:** Plataforma de RA para reconhecimento de imagens e objetos.

#### Configuração do Vuforia
- **Importação do SDK Vuforia:** O pacote Vuforia Engine foi importado da Unity Asset Store.
- **Configuração da Licença:** Chave de licença obtida no site do Vuforia e configurada no Unity.
- **Criação de Imagens Alvo:** Banco de dados com imagens de animais configuradas no Vuforia Target Manager e importadas para o Unity.
- **Configuração no Unity:** Adição de `Image Targets` no Unity, vinculando cada imagem a uma representação 3D.

#### Desenvolvimento das Cenas
- **Menu:**
  - Elementos de UI: Botões "Sair" e "Começar".
  - Script em C# para gerenciamento de transições entre cenas.
- **Main:**
  - Configuração da AR Câmera do Vuforia.
  - Adição e configuração de modelos 3D de animais associados aos `Image Targets`.
  - Interface de usuário com temporizador e pontuação.
- **GameOver:**
  - Exibição da pontuação final.

#### Interface de Usuário
Desenvolvida utilizando TextMeshPro para garantir textos nítidos e personalizáveis. Elementos de UI foram adicionados nas cenas "Menu" e "Main", garantindo uma experiência de usuário intuitiva e responsiva. O `Canvas Scaler` permitiu a adaptação eficiente da interface a diferentes resoluções de tela.

#### Programação em C#
- **SceneMenuManager:** Gerencia as transições entre as cenas "Menu" e "Main".
- **GameManager:** Controla a lógica do jogo, incluindo atualização de pontuação e temporizador.

#### Implementação da Realidade Aumentada
A AR Camera foi configurada substituindo a câmera padrão do Unity pela `ARCamera` do Vuforia. Cada `Image Target` foi associado a um modelo 3D correspondente, proporcionando uma experiência interativa onde os modelos 3D aparecem sobre as imagens quando detectadas pela câmera.

### 4. Conclusão
O desenvolvimento do jogo "Qual é o Animal?" demonstrou o potencial da RA para criar experiências educativas interativas. Utilizando Unity e Vuforia, foi possível integrar modelos 3D com reconhecimento de imagem, proporcionando um ambiente lúdico e informativo para crianças. Este projeto serve como base para futuras expansões, incluindo a adição de novos animais e funcionalidades.

### 5. Referências
- Unity Technologies. (2024). Unity User Manual. Disponível em: [https://docs.unity3d.com/Manual/index.html](https://docs.unity3d.com/Manual/index.html).
- PTC Inc. (2024). Vuforia Engine Developer Library. Disponível em: [https://library.vuforia.com](https://library.vuforia.com).
