# RepositorioTemplate

Repositório que deve ser utilizado como template inicial pelos grupos da matéria de Arquitetura e Desenho de Software.

## Introdução

Este repositório traz um template de repo de documentação a ser seguido pelos grupos de arquitetura e desenho de software.

---

## 1. Clone este repositório

```bash
git clone https://github.com/UnBArqDsw2025-1-Turma01/2025.1-T01-_G1_Embarcado_Entrega_04
```

## 2. Pré-requisitos

### Linux (Ubuntu/Debian)

- Certifique-se de ter o `make`, `python3`, `pip` e `venv` instalados:

```bash
sudo apt update
sudo apt install -y make python3 python3-pip python3-venv
```

### Windows

- Instale o [Git for Windows](https://git-scm.com/download/win)
- Instale o [Chocolatey](https://chocolatey.org/install) (executando o terminal **como administrador**), ou use o `Makefile` que instala automaticamente.
- Em seguida, instale o Make com:

```cmd
choco install make
```

---

## 3. Construir e iniciar os serviços com Make

Após instalar os pré-requisitos, execute:

```bash
make build-up
```

O script irá:

- Verificar o Python e ambiente virtual
- Instalar dependências com barra de progresso interativa
- Iniciar o servidor local com MkDocs

---

## 4. Acesse a documentação no navegador

Abra o navegador e vá para:

👉 [http://127.0.0.1:8123](http://127.0.0.1:8123)

---

## Dica: Configuração inicial do Git no Windows

Após instalar o Git, configure seu nome de usuário e e-mail globalmente (eles serão usados nos commits):

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

Verifique suas configurações com:

```bash
git config --global --list
```
