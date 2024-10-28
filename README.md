# Rotina de Versionamento

Verificar em qual branch está

```bash
git checkout
```

Se estiver em branch errada

```bash
git checkout sua-branch
```

Atualizar seu repositório remoto com o com o git

```bash
git pull
```

Faça seus codigos e seus devidos commits

```bash
git add .
git commit -m "sua mensagem"
git push -u origin sua-branch --force
```

Atualize novamente seu repositório remoto com o com o git, essa é uma boa prática, alguém pode ter trabalhado na sua branch

```bash
git pull
```

Trate os Merge Conflits, se houver, e sincronize suas mudanças

### Agora é hora de dar merge no seu desenvolvimento com a branch main

Vá para a Main Branch e atualize ela, alguém pode ter trabalhado nela também

```bash
git checkout main
git pull
```

A boa prática, é sempre primeiro dar merge com da main na sua branch, e depois levar essas mudanças para a main

Volte para a sua branch

```bash
git checkout sua-branch
```

Dê merge com a main

```bash
git merge main
```

Trate os Merge Conflits, se houver, e sincronize suas mudanças

Agora podemos voltar para a main e atualizar ela, alguém pode ter trabalhado nela enquanto estava fazendo merge

```bash
git checkout main
git pull
```

Merge na sua-branch

```bash
git merge sua-branch
```

Trate os Merge Conflits, se houver, e sincronize suas mudanças

Pronto, suas mudanças estão todas salvas, atualizadas, "mergeadas" e comentadas!!!
