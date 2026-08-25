<div align="center">

```text
██╗ ██████╗  ██████╗ ██████╗ ██████╗ ███████╗██╗   ██╗    ███████╗██╗  ██╗███████╗
██║██╔════╝ ██╔═══██╗██╔══██╗██╔══██╗██╔════╝██║   ██║    ██╔════╝╚██╗██╔╝██╔════╝
██║██║  ███╗██║   ██║██████╔╝██║  ██║█████╗  ██║   ██║    █████╗   ╚███╔╝ █████╗  
██║██║   ██║██║   ██║██╔══██╗██║  ██║██╔══╝  ╚██╗ ██╔╝    ██╔══╝   ██╔██╗ ██╔══╝  
██║╚██████╔╝╚██████╔╝██║  ██║██████╔╝███████╗ ╚████╔╝     ███████╗██╔╝ ██╗███████╗
╚═╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═════╝ ╚══════╝  ╚═══╝      ╚══════╝╚═╝  ╚═╝╚══════╝
```

### `> Opa! Meu nome é Igor ★.°☆`

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=500&color=FF6B9D&center=true&vCenter=true&width=600&lines=Software+Engineering+%40+UnB+%F0%9F%8E%93;Meu+portf%C3%B3lio+roda+dentro+de+um+VS+Code+%F0%9F%96%A5%EF%B8%8F;HTML%2C+CSS+e+JS+puros+%E2%80%94+sem+build%2C+sem+framework;Open+to+internship+opportunities+%F0%9F%9A%80)](https://git.io/typing-svg)

[![Ver portfólio ao vivo](https://img.shields.io/badge/▶_VER_PORTFÓLIO_AO_VIVO-FF6B9D?style=for-the-badge&logoColor=white)](https://igordev-exe.github.io/igor-portfolio/)

</div>

---

<img align="right" width="400" src="https://raw.githubusercontent.com/igordev-exe/igordev-exe/output/github-contribution-grid-snake-dark.svg" alt="cobrinha das contribuições" />

### `< sobre_mim />`

```c
typedef struct {
    char  *nome;
    char  *universidade;
    char  *curso;
    char  *projeto_atual;
    char  *objetivo;
    bool   disponivel_para_estagio;
} Igor;

Igor eu = {
    .nome               = "Igor",
    .universidade       = "UnB — Brasília",
    .curso              = "Engenharia de Software",
    .projeto_atual      = "igor-portfolio 🖥️",
    .objetivo           = "Crescer como dev & contribuir de verdade",
    .disponivel_para_estagio = true
};
```

<br clear="right"/>

---

### `< projeto_destaque />`

<div align="center">

## 🖥️ igor-portfolio

**Meu portfólio, montado como se fosse um editor de código.**

[![Ver ao vivo](https://img.shields.io/badge/▶_VER_AO_VIVO-FF6B9D?style=for-the-badge&logoColor=white)](https://igordev-exe.github.io/igor-portfolio/)
[![Código](https://img.shields.io/badge/CÓDIGO-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/igordev-exe/igor-portfolio)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Sem build](https://img.shields.io/badge/sem_build-1a1a1a?style=flat-square)

</div>

```text
 _______________________________________________________________________
|igor-portfolio                                                   |F]|!"|
|"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""|"|
|~/igordev-exe $ whoami                                               | |
|Igor Alves — Engenharia de Software, UnB/FGA                         | |
|                                                                     | |
|~/igordev-exe $ open projects                                        | |
|abrindo projects.json...                                             |_|
|_____________________________________________________________________|/|
```

#### Como foi feito

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#161b22','primaryTextColor':'#c9d1d9','primaryBorderColor':'#FF6B9D','lineColor':'#FF6B9D','secondaryColor':'#0d1117','tertiaryColor':'#0d1117','fontFamily':'monospace'}}}%%
flowchart LR
    A["🎨 Figma<br/>layout, paleta, estados"] --> B["📄 export estático<br/>caixas, cores, espaçamento"]
    B --> C{"o que o export<br/>não entrega"}
    C --> D["terminal que<br/>interpreta comandos"]
    C --> E["command palette<br/>com busca fuzzy"]
    C --> F["folding, sticky scroll,<br/>3 temas"]
    D --> G["index.html<br/>~100 KB · sem build"]
    E --> G
    F --> G
```

O desenho vem primeiro: paleta, hierarquia dos painéis e cada estado da interface nascem no Figma antes de qualquer linha de código. O export dá conta do que é estático — o comportamento é escrito à mão.

| | |
|---|---|
| **Terminal funcional** | `ls`, `cat`, `open`, `grep`, `theme`, `whoami`, `status` |
| **Command palette** | busca fuzzy em `Ctrl+Shift+P`, ir para linha em `Ctrl+G` |
| **Editor de verdade** | folding, indent guides, sticky scroll, minimap interativo, bracket colorization |
| **3 temas** | Dark+ / Light+ / Monokai |
| **Responsivo** | no mobile o código quebra em vez de rolar pro lado, e a numeração acompanha |

> **Stack:** HTML, CSS e JS puros. Arquivo único, ~100 KB, zero framework, zero build. A única dependência externa é a fonte JetBrains Mono.

---

### `< outros_projetos />`

#### ☕ Byte and Brew — [`repo`](https://github.com/igordev-exe/byte-and-brew)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![POO](https://img.shields.io/badge/POO-5382a1?style=flat-square)

Sistema de vendas e fidelidade (XP) para a cafeteria geek Byte & Brew. Construído 100% em Java, com foco na aplicação rigorosa de conceitos de Orientação a Objetos para garantir regras de negócio seguras — do bloqueio de vendas sem estoque ao resgate de pontos por clientes VIPs.

---

### `< stack />`

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**Ferramentas & Ambiente**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Neovim](https://img.shields.io/badge/NeoVim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

</div>

---

### `< contato />`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/igordev-exe)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:igoralvesrodrigues12@gmail.com)
[![Portfólio](https://img.shields.io/badge/Portfólio-FF6B9D?style=for-the-badge&logo=googlechrome&logoColor=white)](https://igordev-exe.github.io/igor-portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/igordev-exe)

</div>

<div align="center">

![Seguidores](https://img.shields.io/github/followers/igordev-exe?style=flat-square&logo=github&color=FF6B9D&labelColor=0d1117&label=seguidores)
![Último commit](https://img.shields.io/github/last-commit/igordev-exe/igor-portfolio?style=flat-square&color=FF6B9D&labelColor=0d1117&label=último%20commit)
![Profile Views](https://komarev.com/ghpvc/?username=igordev-exe&color=FF6B9D&style=flat-square&label=visitas+no+perfil)

</div>

---

<div align="center">

```c
while (alive) {
    lift();
    learn();
    code();     //
    nerd_out();
}
```

</div>

---
