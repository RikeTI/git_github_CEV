# Linguagem Markdown
## Tipos de Marcas:
***
* *: gera marcação de lista não numerada (bolinha cheia)
* duplo "*", "_": geram o começo e o fim da formatação em negrito. Ex.: **negrito**
* único "*", "_": geram \\ \\ em itálico. Ex.: _itálico_
* "#": gera título; o equivalente ao h1 do HTML; ## <=> h2, ### <=> h3, etc; é necessário espaço entre o "#" e o texto.
* triplo "---" ou "***": gera uma linha horizontal; o equivalente ao hr.
---
## Listas
#### Lista Numerada
"Número qualquer" + "." (Não precisa estar em ordem)
1. Teste
2. Teste2
   1. NovoTeste (precisa começar por "1")
200. Teste3
#### Lista Demarcada (Não Numerada)
"*" ou "-" + "espaço": item da lista
- Teste4: item da lista
  - NovoTeste2: subitem da lista
- Teste5
#### Lista de Tarefas
- [x] Criar página principal
- [] Criar página de Compras
- [] Criar langpage
---

## Tabelas

Num | Nome | Nota
--- | --- | ---
1 | Rike | 9,0
2 | Elysia | 10
3 | Spell | 8,5

---

## Destaques (para comandos, por exemplo)
Ex.: Não entendi o comando `document.getIdElementById()` de JS.
Ex.: Código valor par-ímpar em python:
```
num = int(input('Informe um número: '))
if num % 2 == 0:
    print(f'{num} é par')
else:
    print(f'{num} é ímpar')
```
