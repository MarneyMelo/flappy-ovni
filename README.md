# 🛸 Flappy OVNI

> Uma reinterpretação intergaláctica do clássico Flappy Bird, desenvolvida como projeto acadêmico da disciplina de Programação e Desenvolvimento de Software II na UFMG.

![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)
![Badge C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

## 📖 Sobre o Projeto

O **Flappy OVNI** é um jogo de plataforma no estilo *endless runner*, baseado no clássico Flappy Bird. O objetivo principal foi implementar a mecânica clássica de voo e desvio de obstáculos, enriquecendo a experiência com sistemas de persistência de dados e elementos de RPG (power-ups e níveis de dificuldade).

Diferente do original, este projeto foca na progressão do jogador através de um sistema de contas e placares globais.

---

## 🎮 Funcionalidades Principais

### ⚙️ Core Mechanics & Sistemas
- **Sistema de Cadastro e Login:** Cada jogador possui uma conta única.
- **Placar de Líderes (High Score):** Um ranking persistente que exibe as melhores pontuações registradas entre todos os usuários.
- **Física de Voo:** Controle preciso de pulo e gravidade para desviar dos obstáculos.

### 🌟 Diferenciais de Gameplay
Implementamos mecânicas que vão além do jogo original para tornar a partida mais dinâmica:

| Ícone | Item | Efeito |
|:---:|:---|:---|
| ⭐ | **Estrela (Power-up)** | Concede **invencibilidade temporária**. O OVNI pode atravessar canos sem sofrer dano por um curto período. |
| 💰 | **Coletável de Pontos** | Um item especial que, ao ser coletado, concede **pontuação bônus** imediata. |

### 🕹️ Seletor de Dificuldade
O jogo se adapta ao nível do jogador através de três modos distintos, que influenciam diretamente a velocidade do jogo e a geração procedural dos canos:
1. **Fácil**
2. **Médio**
3. **Difícil**

### 🎨 Design Original
Todos os ativos visuais (sprites do personagem, canos, fundos e itens) são de **autoria própria**, criados exclusivamente para este projeto.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

* **Linguagem:** C++ (Padrão C++11 ou superior)
* **Biblioteca Gráfica:** Allegro 5
* **Documentação:** Doxygen

---

## 🚀 Como Executar o Jogo

### Pré-requisitos
Certifique-se de ter instalado em sua máquina:
* Compilador C++ (G++)
* Biblioteca Allegro 5
* Make

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/MarneyMelo/flappy-ovni.git](https://github.com/MarneyMelo/flappy-ovni.git)
````

2.  **Acesse a pasta do projeto:**

    ```bash
    cd FLAPPY-OVNI
    ```

3.  **Compile o código:**

    ```bash
    # Exemplo:
    make all
    ```

4.  **Execute o jogo:**

    ```bash
    ./bin/main.exe
    ```

-----

## 📚 Documentação

A documentação completa do código foi gerada utilizando a ferramenta **Doxygen**.
Para acessá-la, você pode gerar os arquivos localmente seguindo estes passos:

1. Certifique-se de ter o **Doxygen** instalado na sua máquina.
2. Na raiz do projeto, execute o comando:
   ```bash
   doxygen Doxyfile
Uma pasta chamada html será criada. Abra o arquivo html/index.html no seu navegador para visualizar a estrutura de classes, métodos e hierarquias do projeto.

-----

## 👥 Autores

Este projeto foi desenvolvido por:

  * **Marney Melo** - [MarneyMelo](https://github.com/MarneyMelo)
  * **Rafael Miranda** - [RRafaelMMiranda](https://github.com/RRafaelMMiranda)
  * **Theo Duarte** - [theolara272727](https://github.com/theolara272727)
  * **Victor Kaizer** - [KaizerBlank](https://github.com/KaizerBlank)
  * **Vinicius Rochar** - [vrrocha-scs](https://github.com/vrrocha-scs)

-----

## 📄 Licença

Este projeto está sob a licença [MIT](https://www.google.com/search?q=./LICENSE).

```
```
