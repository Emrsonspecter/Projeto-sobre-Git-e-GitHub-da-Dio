# Desafio de Projeto sobre Git/GitHub



###  O que é chave SSH?

**Chaves SSH** são uma forma segura de identificar usuários conhecidos, substituindo o tradicional "usuário e senha".

### O que é um git commit?

O comando **git commit** captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com **commit** podem ser considerados versões "seguras" de um projeto, o **Git** nunca os altera, a menos que você peça a ele.

### blob

Cada arquivo no **Git** é armazenado como um objeto **blob**, por exemplo, a partir do conteúdo do arquivo logo. png ele gera um hash que será armazenado em algum lugar endereçável como aa1b2fb696a831c89c53f787e03d863691d2b671 . O mesmo ocorre com o arquivo app.



### Tree

A **tree** representa um diretório, contendo uma mistura de blobs e **trees**. Podemos descobrir que ela resolve usar **git** rev-parse, para determinar que essa **tree** é um objeto com o hash 2b61e34…. Como é que essa **tree** é criada? Bem, mais uma vez, é um objeto bem formatado que é numerado de acordo com o sha1.



**Unmodified** é o estado onde o arquivo não sofreu alterações em relação a sua referência. **Modified** é o estado onde o arquivo sofreu alterações em relação a sua referência. **Staged** é o estado onde o arquivo já foi endereçado e aguarda ser transferido ao repositório.

