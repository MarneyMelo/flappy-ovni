# Flappy OVNI

> An intergalactic remake of the classic Flappy Bird, developed as an academic project for the Software Development and Programming II course at UFMG.

![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)
![Badge C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

## About the Project

**Flappy OVNI** is an *endless runner* platform game based on the classic Flappy Bird. The main goal was to implement the classic flying and obstacle-avoidance mechanics, adding data persistence and RPG elements like power-ups and difficulty levels.

---

## Main Features

### Core Mechanics & Systems

* **Login and Register System:** Every player has a unique account.
* **Leaderboard (High Score):** A persistent ranking that shows the best scores from all users.
* **Flight Physics:** Precise jump and gravity control to dodge obstacles.

### Gameplay Extras

We added new mechanics to make the game more dynamic:

| Icon | Item | Effect |
| --- | --- | --- |
| 🟡 | **Yellow Circle (Power-up)** | Gives **temporary invincibility**. The UFO can pass through pipes without taking damage. |
| 🟢 | **Green Circle** | A special item that gives **bonus points** immediately when collected. |

### Difficulty Selector

The game adapts to the player's skill with three modes, which change the game speed and pipe generation:

1. **Easy**
2. **Medium**
3. **Hard**

### Original Design

All visual assets (character sprites, pipes, backgrounds, and items) are **original**, created specifically for this project.

---

## Technologies Used

This project was developed using:

* **Language:** C++ (C++11 standard or higher)
* **Graphics Library:** Allegro 5
* **Documentation:** Doxygen

---

##  How to Run the Game

### Prerequisites

Make sure you have installed:

* C++ Compiler (G++)
* Allegro 5 Library
* Make

### Step by Step

1. **Clone the repository:**
```bash
git clone https://github.com/MarneyMelo/flappy-ovni.git

```


2. **Enter the project folder:**
```bash
cd FLAPPY-OVNI

```


3. **Compile the code:**
```bash
make all

```

4. **Run the game:**
```bash
./bin/main.exe

```

## Documentation

The full code documentation was created using **Doxygen**.
To view it, follow these steps:

1. Make sure you have **Doxygen** installed.
2. In the project root, run:
```bash
doxygen Doxyfile

```

A folder named `html` will be created. Open the file `html/index.html` in your browser to see the classes and methods.

---

## Authors

This project was developed by:

* **Marney Melo** - [MarneyMelo](https://github.com/MarneyMelo)
* **Rafael Miranda** - [RRafaelMMiranda](https://github.com/RRafaelMMiranda)
* **Theo Duarte** - [theolara272727](https://github.com/theolara272727)
* **Victor Kaizer** - [KaizerBlank](https://github.com/KaizerBlank)
* **Vinicius Rocha** - [vrrocha-scs](https://github.com/vrrocha-scs)

---

## License

This project is under the [MIT](https://opensource.org/licenses/MIT) license.

---

-----

## 📄 Licença

Este projeto está sob a licença [MIT](https://www.google.com/search?q=./LICENSE).

