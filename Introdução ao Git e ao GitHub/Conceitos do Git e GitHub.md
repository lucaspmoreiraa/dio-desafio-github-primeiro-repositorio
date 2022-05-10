# Conceitos do Git/GitHub :bulb:

*No documento abaixo listo alguns conceitos importantes aprendidos no curso sobre Git e Git Hub*.

 `_____________________________________________________________________`

1. **Git Bash:** é um terminal estendido para otimizar o uso do *Git.*
2. **Chave SSH**: forma de estabelecer uma conexão segura e encriptada entre duas máquinas.
3. **SHA:** é um algoritmo de segurança *(encriptação)* que vai pegar seu arquivo e embaralha-lo de uma forma muito específica. Tão específica que essa encriptação gera um conjunto de 40 dígitos únicos.
4. **Git**: é um software que ajuda e monitora diferentes versões do nosso código dentro da máquina. 
5. **Blob:** *(bolhas)*: é o bloco mais básico dentro da *'tree'* e do *'commit'*. Os arquivos do *Git* ficam dentro desse objeto chamado *Blob*. Dentro de uma bolha, o usuário encontra os seguintes *metadados:*
   - _tipo, tamanho do arquivo ou string, \0 + conteúdo do arquivo (o Sha1, texto, imagem...)._

6. **Tree:** *(árvore)*: é a responsável por toda a estrutura do arquivo e armazenam as *blobs*. Dentro de uma *árvore*, temos:
   - *tipo, tamanho, \0, blob, nome do arquivo e conteúdo.*

7. **Commit**: é o objeto mais importante dentre esses três *(blob, tree e commit)*. Ele é o responsável por juntas todos os dados do arquivo, sendo eles:
   - *tree, tamanho, parente, autor, mensagem, timestamp, SHA1.*

 `_____________________________________________________________________`

***Link para download do Git: https://git-scm.com/downloads***