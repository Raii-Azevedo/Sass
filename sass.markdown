SASS - Syntactically Awesome Style Sheets

     - É uma forma de escrever código css, pe como se fosse um super css (de super poder).

    - O Sass funciona de forma pré-processado, não utilizar o arquivo em produção. Ele vai ser processado para a utilização final no arquivo css.

    - .scss(sassy css) e tem como diferencial no mesmo arquivo Sass
        $cor:blue;
        h1 {
            colo: $cor;
        }
    Ou seja, há a possibilidade de criar variáveis que podem utilizar em qualquer parte do CSS.

    PORQUE USAR O SASS?
    - Velocidade e facilidade
    - Separação facilitada dos arquivos (obtendo uma melhor organização)
    - Recursos:
      - Variáveis, operadores, funções internas e etc.

    -> OUTROS PRÉ PROCESSADORES DE CSS
    - Less
    - Stylus

    SASS OU SCSS?
    - SASS -> Identado
    - SCSS -> Formato CSS

COMO CONVERTER UM ARQUIVO SCSS PARA CSS
NO TERMINAL:
        sass file.scss file.css


PARA MONITORAR O ARQUIVO SCSS
    sass --watch file.scss:file.css
>>> Sass is watching for changes. Press Ctrl-C to stop.

O SASS também poermite monitorar uma pasta inteira.

sass --watch scss:css
>>> Sass is watching for changes. Press Ctrl-C to stop.
>>> New template detected: scss/file.scss
      write css/file.css
      write css/file.css.map

UM SOFTWARE PARA MONITORAR O SASS
    - koala







