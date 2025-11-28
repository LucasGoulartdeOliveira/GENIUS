# 🎮 Genius (Simon) – Versão com Setas do Teclado

Este projeto é uma implementação moderna do clássico jogo **Genius/Simon**, onde o jogador deve repetir sequências crescentes de botões iluminados.  
Nesta versão, o jogo utiliza **as setas do teclado** (↑ → ↓ ←) ou cliques nas áreas coloridas para reproduzir os movimentos.

O projeto foi desenvolvido inteiramente com **HTML + CSS + JavaScript**, sem bibliotecas externas, com foco em visual moderno, efeitos visuais suaves e áudio gerado via Web Audio API.

---

## 🚀 Funcionalidades

- 🔁 **Gera sequências aleatórias** de setas para o jogador repetir.  
- 🎨 **Feedback visual** com destaque e animações nos botões.  
- 🔊 **Efeitos sonoros** usando Web Audio API.  
- 🧠 **Modo Rígido (Strict Mode):**  
  - ON → erro reinicia o jogo desde o início  
  - OFF → erro apenas repete a mesma sequência  
- 🎮 **Controles por teclado** ou clique no mouse.  
- 🔄 Botões de **Iniciar**, **Resetar** e alternância do **Modo Rígido**.  
- 📱 Interface responsiva para telas menores.  

---

## 🛠️ Tecnologias Utilizadas

### **HTML5**
- Estrutura do layout do jogo.
- Uso de `data-key` para mapear teclas e pads.

### **CSS3**
- Gradientes e estilo moderno no estilo *glass UI*.
- Design responsivo com media queries.
- Animações suaves nos botões e no fundo.

### **JavaScript (Vanilla JS)**
- Lógica do jogo Genius:
  - Geração da sequência.
  - Playback com animações.
  - Verificação de respostas.
- Controle da interface e interação com o jogador.
- Event listeners para teclado e mouse.

### **Web Audio API**
- Geração de tons simples para cada direção:
  - ⬆ 440 Hz  
  - ➡ 660 Hz  
  - ⬇ 880 Hz  
  - ⬅ 550 Hz  
- Uso de rampas de volume para evitar artefatos sonoros.

---

## 📂 Estrutura do Projeto
/seu-projeto
│── index.html # Arquivo principal contendo todo o jogo



Todo o código está contido em um único arquivo HTML para fácil portabilidade.

---

## ▶️ Como Jogar

1. Clique em **Iniciar**.  
2. Observe a sequência piscando no tabuleiro.  
3. Reproduza usando:
   - Teclas **↑ → ↓ ←**, ou  
   - Clique nas áreas coloridas.  
4. A cada rodada a sequência aumenta.  
5. Se errar:
   - **Modo Rígido OFF:** você apenas repete a rodada.  
   - **Modo Rígido ON:** o jogo reinicia desde o começo.  

---

## 📜 Licença

Este projeto pode ser usado livremente para estudo, modificação e melhorias.

---

