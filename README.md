# JFV - José Flávio Versionamento

Padrão de versionamento de produtos.

Especificação: [http://joseflavio.com/jfv/](http://joseflavio.com/jfv/)

Este repositório consiste na documentação da especificação do JFV, a qual tem sido feita através da ferramenta [Jekyll](https://jekyllrb.com/).

## Preparação Inicial

Este projeto foi preparado inicialmente da seguinte forma:

```sh
jekyll new web
cd web
cp -R $(bundle show minima)/_includes .
cp -R $(bundle show minima)/_layouts .
cp -R $(bundle show minima)/_sass .
```

## Edição Local

Para editar e visualizar localmente esta documentação, execute no terminal:

```sh
git clone https://github.com/joseflaviojr/jfv.git
cd jfv/web
bundle exec jekyll serve
```

Posteriormente, acesse no navegador o endereço `http://127.0.0.1:4000/`.

## Publicação

Para criar os arquivos finais da documentação, prontos para publicação, execute no terminal:

```sh
jekyll build
```

Os arquivos serão gerados no diretório `./_site`.

A publicação oficial está localizada em [http://joseflavio.com/jfv/](http://joseflavio.com/jfv/).
