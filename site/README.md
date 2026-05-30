# Cérebro Tendoshk — Site Público Sanitizado

Este diretório contém a vitrine pública sanitizada do Cérebro Tendoshk.

## Natureza

```txt
camada pública
site estático
conteúdo conceitual
sem núcleo operacional privado
vitrine v0.2.1
navegação interna entre páginas HTML
linhas vivas públicas validadas
```

## O que este site apresenta

- visão pública do Cérebro Tendoshk;
- problema de continuidade entre conversas e projetos;
- proposta de governança de memória;
- governança de estado como conceito público;
- linhas vivas de projeto como conceito público;
- exemplos sanitizados de linhas vivas;
- separação entre público e privado;
- páginas internas da própria vitrine publicada;
- casos de uso públicos e sanitizados;
- aviso explícito de sanitização.

## Páginas internas

```txt
index.html
manifesto.html
arquitetura.html
governanca-de-estado.html
linhas-vivas.html
casos-de-uso.html
limites-publicos.html
roadmap.html
release.html
```

## O que este site não contém

```txt
conteúdo pessoal ou sensível
material operacional reservado
estado interno completo
mecanismos privados
registros reais de operação
```

## Relação com a EV-21

Este site foi preparado como solução segura para a EV-21:

```txt
EV-21 — GitHub Pages / publicação controlada da vitrine pública sanitizada
```

A publicação deve usar somente o conteúdo deste diretório `site/`.

## Ajuste v0.2.1

A vitrine pública foi alinhada à versão `0.2.1` para refletir melhor:

```txt
governança pública de continuidade
governança de estado como página interna
linhas vivas como página interna validada
retomada de projetos vivos
separação público/privado
casos de uso públicos
navegação local dentro da vitrine publicada
```

Como o workflow de Pages publica apenas a pasta `site/`, os links principais da vitrine devem apontar para páginas HTML dentro de `site/`, e não para arquivos Markdown no GitHub.

## Validação pós-NRO-PUBLIC-08

```txt
linhas_vivas_publicas = sim
site/linhas-vivas.html = presente no artifact
href="linhas-vivas.html" = validado no index
GitHub Pages = success
```

## Regra de manutenção

Antes de publicar ou alterar este diretório, verificar:

```txt
1. O conteúdo é público por design?
2. O conteúdo é sanitizado?
3. O conteúdo evita estrutura operacional privada?
4. O conteúdo evita material sensível ou reservado?
5. O conteúdo está alinhado com SECURITY.md e docs/limites_publicos.md?
6. Os links funcionam quando apenas a pasta site/ é publicada?
7. A navegação principal permanece dentro da vitrine, salvo quando o link externo for intencional?
8. Novas páginas HTML internas foram adicionadas ao workflow Pages quando necessário?
```
