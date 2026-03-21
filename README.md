# 🎩 The Hat Below

> Landing page do jogo **The Hat Below** — um jogo low code criado no Construct, com galeria de fotos, seção sobre o jogo, acesso para jogar e contato profissional.

🌐 **[Acesse o site aqui](https://francescogris.github.io/Jogo-low-code/)**

---

## 📋 Sobre o Projeto

**The Hat Below** é uma landing page de página única desenvolvida como vitrine para um jogo criado na engine **Construct**. O site reúne em um só lugar tudo sobre o jogo: a história, screenshots, acesso direto para jogar e um canal de contato.

O jogo acompanha um gato que, após entrar em um esgoto radioativo em busca de seu chapéu, se depara com um grande rato sonolento que o pegou. Resgatar o chapéu parece fácil, mas as surpresas escondidas no esgoto vão botar a vida do gato em risco.

---

## 📄 Seções

| Seção | Descrição |
|-------|-----------|
| 🏠 Hero | Título animado e botão de acesso ao jogo |
| 📖 Sobre | História e controles do jogo |
| 🖼️ Galeria | Screenshots do jogo |
| 📬 Contato | Formulário de contato funcional |

---

## 🕹️ Controles do Jogo

| Ação | Tecla |
|------|-------|
| Correr | ← → (Setas) |
| Pular | ↑ (Seta para cima) |
| Atirar | `C` |

---

## 🛠️ Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) **HTML5**
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) **CSS3**
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) **JavaScript** *(menu mobile)*
- **Font Awesome** *(ícones)*
- **Web3Forms** *(envio do formulário de contato)*
- ![Construct](https://img.shields.io/badge/Construct-00BFFF?style=flat&logoColor=white) **Construct** *(engine do jogo, exportado para web)*
- ![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white) **Visual Studio Code** + **Live Server**

---

## 🚀 Como Rodar Localmente

### Pré-requisitos

- [Visual Studio Code](https://code.visualstudio.com/)
- Extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) instalada no VSCode

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/FrancescoGris/Jogo-low-code.git

# 2. Acesse a pasta do projeto
cd Jogo-low-code
```

3. Abra a pasta no **VSCode**
4. Clique com o botão direito no arquivo `index.html`
5. Selecione **"Open with Live Server"**
6. O site abrirá automaticamente no navegador em `http://localhost:5500`

---

## 📁 Estrutura do Projeto

```
Jogo-low-code/
│
├── index.html          # Página principal (página única)
├── jogar.html          # Página do jogo
├── style.css           # Estilos globais do site
│
├── css/                # Bibliotecas CSS externas
│   └── all.min.css     # Font Awesome
│
├── imgs/               # Imagens do site
│   ├── logo.png
│   ├── print1.PNG ... print5.PNG
│   └── ...
│
└── jogo/               # Jogo exportado pelo Construct
    ├── index.html
    ├── data.json
    ├── images/
    ├── media/
    └── scripts/
```

---

## 👤 Autor

Desenvolvido por **Francesco Gris**

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/fran_grisf/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/francesco-gris-053092355/)

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
