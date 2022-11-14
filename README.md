## O que são modulos Javacsript ? 

  - Módulos são arquivos javascript que tem a capacidade de exportar e importar informações de outros arquivos do mesmo tipo.

---

### Vantagens
  - Organização de Código
  - Compartilhamento de variáveis em escopos diferentes
  - Explicítas as dependência de arquivos

---
### Tipos de Exportações | Importando

- Named Exports: Zero ou mais exports por módulo
- Default Exports: Uma por módulo
---

- Para importar o Named Exports Utilizamos:
    - `
        import {funcao, variavel, classe} from 'arquivo.js'
    `

- Para importar o Default Exports utilizamos:
    - `
        import valorDefault  from 'arquivo.js'
    ` 

- Trocando nome da importação:
    - `
        import valorDefault as outroNome  from 'arquivo.js'
    ` 

- Importar todos os dados de um arquivo :
    - `
        import * as Nome  from 'arquivo.js'
    ` 
---

### Vinculando com o HTML

`<script type="module" src="endereco"></script>`

***OBS:*** Para utilizar isso localmente temos que está rodando em um servidor. Pode-se usar o LIVE SERVER que é uma extensão do VsCode