# 🖥️ Jogo da Velha - Usuário vs Máquina (Python - Terminal)

![Feito com Python](https://img.shields.io/badge/feito%20com-Python-FFC0CB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-concluído-FFC0CB)
![Licença](https://img.shields.io/badge/licença-Livre-FFC0CB)
![Autoria](https://img.shields.io/badge/feito%20por-Lavínia%20Butinholi%20Basílio-FFC0CB)

---

## 📖 Descrição
Este projeto implementa o **Jogo da Velha contra a Máquina** em **Python**, totalmente jogável no terminal.  
O objetivo é permitir que o **usuário jogue contra o computador**, que faz jogadas aleatórias.  
O jogo termina quando o usuário ou a máquina vence, ou quando ocorre empate.

---

## ⚙️ Funcionalidades
- 🧩 Criação dinâmica do tabuleiro (3x3)  
- 🤖 Jogabilidade contra a **Máquina (CPU)**  
- ✅ Verificação de vitória em linhas, colunas e diagonais  
- 🤝 Detecção de empate  
- 💬 Interface simples via terminal  

---

## 🧠 Estrutura do Código
| Função | Descrição |
|--------|------------|
| `criar_tabuleiro(dimensao)` | Cria uma matriz NxN com espaços vazios (`_`) |
| `imprimir_tabuleiro(tabuleiro)` | Exibe o tabuleiro formatado no terminal |
| `verificar_vitoria(tabuleiro, simbolo)` | Verifica se o jogador venceu |
| `jogar_vs_maquina()` | Controla o fluxo do jogo contra a máquina, alternando jogadas |

---

## 👩‍💻 Autor

**Lavínia Butinholi Basílio**  
Projeto criado para fins de estudo em **lógica de programação**, **estruturas de repetição** e **funções em Python**.



## 🪶 Licença

Este projeto é de **uso livre** para fins **educacionais e de aprendizado**.  
Sinta-se à vontade para estudar, modificar e aprimorar. 💡



## 🎮 Como Jogar

1. O terminal exibirá o tabuleiro com posições vazias (`_`).  
2. Cada jogador, por vez, escolhe uma **linha** e uma **coluna** digitando dois números separados por espaço (ex: `0 2`).  
3. O símbolo (**X** ou **O**) será marcado na posição escolhida.  
4. O jogo continua até que um jogador vença ou todas as posições sejam preenchidas (empate).

**Exemplo de rodada:**

 _ | _ | _
------------
 _ | _ | _
------------
 _ | _ | _

Sua vez! Escolha a linha e coluna (0-2) para 'X': 1 1


## 🚀 Como Executar

### 1️⃣ Pré-requisitos
- Ter o **Python 3** instalado no sistema

### 2️⃣ Clonar o repositório
```bash
git clone https://github.com/seuusuario/jogo-da-velha.git
cd jogo-da-velha

python jogar_vs_maquina.py
