# GerenciaBike 🚲

Protótipo front-end de um sistema para gerenciamento de bicicletas compartilhadas, com acompanhamento do estado de cada bicicleta, alertas, relatórios e feedbacks.

> Projeto acadêmico em HTML, CSS e JavaScript. Ainda não possui back-end: os dados exibidos são estáticos.

## Telas

| Arquivo | Descrição |
| --- | --- |
| `telaLogin.html` | Tela de login (e-mail, senha e "lembrar de mim") |
| `telaInicial.html` | Página inicial com as bicicletas e seus estados e disponibilidade |
| `telaPrincipal.html` | Painel principal com menu lateral de navegação |
| `telaBicicletas.html` | Cadastro e edição de bicicletas (ID, modelo e estado) |
| `telaAlertas.html` | Lista de alertas por bicicleta, com data |

## Funcionalidades

- Menu lateral com submenus (Bicicletas e Relatórios) que abrem e fecham
- Estados da bicicleta: **Ativo**, **Manutenção** e **Inativo**
- Formulário de cadastro/edição de bicicletas em janela modal
- Seções de relatórios de manutenção e de uso, feedbacks e sobre

## Tecnologias

- HTML5
- CSS3
- JavaScript e jQuery
- Font Awesome (ícones)

## Estrutura do projeto

```
GerenciaBike/
├── assets/     # Ícones (SVG) e imagens
├── js/         # Scripts (menu e modal)
├── styles/     # Folhas de estilo de cada tela
└── tela*.html  # Páginas da aplicação
```

## Como executar

Não é necessário instalar nada:

```bash
git clone https://github.com/LiyDev/GerenciaBike.git
cd GerenciaBike
```

Abra `telaLogin.html` (ou `telaInicial.html`) no navegador. Se preferir, use a extensão Live Server do VS Code.

## Autora

**Lilian Emilly** — [@LiyDev](https://github.com/LiyDev)
