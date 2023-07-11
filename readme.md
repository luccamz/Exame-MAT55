# Projeto do Exame de MAT-55 - Álgebra Linear Computacional

## Instruções de uso

As versões de `Julia` e das dependências do *notebook* `Jupyter` se encontram especificadas em `Project.toml` e `Manifest.toml`.
Para evitar incompatibilidades entre diferentes versões, ao clonar esse repositório, utilize:

```julia
import Pkg
Pkg.activate()
Pkg.instantiate()
```

no `REPL` de `Julia` aberto no mesmo diretório em que o repositório foi clonado para que as versões corretas das dependências sejam instaladas caso ausentes.