# vim-script-change-encoding

Através de um script vim é possível mudar a codificação de N arquivos dentro de um repositório.

É possível alterar o script para que realize qualquer comando vim em massa.

Para mais informações dos comandos disponíveis do vim, acessar:

- https://www.vim.org/docs.php


# Utilização

Com o script copiado para a raiz do seu projeto, execute o comando abaixo via terminal:

find . -type f -name "*.php" -exec vim -S script.vim {} \;

Notas:

Mudar em "*.php" para qualquer extensão de arquivo.
