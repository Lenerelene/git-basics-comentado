# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Mostra qual branch está usando, se a branch está desatualizada e quais arquivos você modificou

**Quando usar / observação:**

Quando vai começar o trabalho no dia, antes de dar commit e quando altera a branch atual

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra as alterações que foram feitas por você que ainda não foram mandadas para o commit ou para o add

**Quando usar / observação:**

Pode ser usado para conferir as alterações feitas por você antes de add

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Prepara o arquivo selecionado para o commit

**Quando usar / observação:**

Antes de fazer commit

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Faz a comparação mas com os arquivos mandados para add

**Quando usar / observação:**

Antes de dar commit para conferir o que foi mandado para o add

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Remove do add o arquivo que foi mandado para ele

**Quando usar / observação:**

Caso tenho cometido um erro e precise cancelar o add

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Para fazer uma alteração na branch

**Quando usar / observação:**

Quando quer que a branch seja alterada com as suas modificações

---

## Checklist deste arquivo

- [X] 1. `git status`
- [X] 2. `git diff`
- [X] 3. `git add [arquivo]`
- [X] 4. `git diff --staged`
- [X] 5. `git reset [arquivo]`
- [X] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
