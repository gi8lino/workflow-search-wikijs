# Alfred workflow - search wikijs

[Alfred](https://www.alfredapp.com) workflow to search articles on your [wikijs](https://js.wiki).

## usage

Press "w" followed by the text, you want to search in your wikijs.  
Press "command" to show the path to the article.

## requirements

- [jq](https://github.com/stedolan/jq)

## variables

When importing this workflow, you have to set the following variables:

| variable     | description           | example                  |
| :----------- | :-------------------- | :----------------------- |
| WIKIJS_URL   | URL to wikijs         | https://wiki.example.com |
| WIKIJS_TOKEN | wikijs access token * | VERY-LONG-TOKEN          |

\**to create a wikijs access token goto `Administration` => `API Access` => Add `NEW API KEY`*

## preview

![preview](.github/img/preview.png)
