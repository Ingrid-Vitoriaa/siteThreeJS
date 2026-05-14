# Atividade Prática: Interface 3D com Three.js e Sketchfab

Este projeto consiste em uma cena 3D interativa desenvolvida para a disciplina de **Interação Humano-Computador (IHC)**. O objetivo é carregar um modelo tridimensional e permitir a manipulação da câmera via navegador utilizando a biblioteca Three.js.

##  Tecnologias Utilizadas
*   **Three.js**: Biblioteca principal para renderização 3D.
*   **GLTFLoader**: Extensão para carregamento de arquivos no formato `.glb`.
*   **OrbitControls**: Módulo para controle de câmera (rotação, zoom e pan).
*   **HTML5 / CSS3 / JavaScript (ES6 Modules)**.

##  Funcionalidades (Critérios de Avaliação)
- [x] **Modelo 3D**: Carregado via `GLTFLoader` a partir da pasta `/models`.
- [x] **OrbitControls**: Implementado para permitir rotação, zoom e pan com mouse e touch.
- [x] **Iluminação**: Configurada com uma luz ambiente (`AmbientLight`) e uma luz direcional (`DirectionalLight`).
- [x] **Loop de Animação**: Ciclo de renderização implementado com `requestAnimationFrame`.
- [x] **Responsividade**: Window resize handler configurado para ajustar câmera e renderer.
- [x] **Organização**: Código separado em arquivos HTML, CSS e JS para melhor legibilidade.

##  Detalhes do Modelo
*   **Modelo Utilizado:** Carro 2
*   **Origem:** [Sketchfab - Carro 2](https://sketchfab.com/3d-models/carro-2-eab580da6c084e32bf63edbf441073d4)
*   **Autor:** G3D
*   **Licença:** CC Attribution (Standard)

##  Como Executar
1. Clone este repositório.
2. Certifique-se de que o arquivo `carro_2.glb` está dentro da pasta `models/`.
3. Por questões de segurança do navegador (CORS), **é obrigatório** rodar o projeto através de um servidor local.
   * Recomendação: Use a extensão **Live Server** do VS Code.
4. Abra o `index.html` pelo servidor local.

---
Desenvolvido como atividade prática para a disciplina de IHC.