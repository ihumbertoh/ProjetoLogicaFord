O projeto que você apresentou é uma calculadora de consumo de combustível implementada em uma página HTML com JavaScript. Com base no código `index.html` que você forneceu, o programa interage com o usuário para coletar informações e exibe os resultados.

Aqui está um README para o seu repositório, com as informações fornecidas e adaptado para o projeto que você criou:

-----

# Calculadora de Consumo de Combustível - Ford

Este repositório contém uma aplicação web simples, desenvolvida em HTML, CSS e JavaScript, para auxiliar os colaboradores da FORD na tomada de decisões sobre o abastecimento de seus veículos. A ferramenta permite que cada colaborador insira dados específicos de sua região e calcule o consumo, o gasto diário e identifique o local mais acessível para abastecer.

-----

## Motivação

O cenário atual de aumento nos preços dos combustíveis tem gerado preocupação para muitas famílias. Para os colaboradores da FORD, é fundamental ter uma ferramenta que auxilie na avaliação de:

  * O consumo necessário em litros para o deslocamento da casa para o trabalho.
  * O local mais acessível para abastecimento de combustível.
  * A média de valores de preços de combustíveis na região pesquisada.
  * O gasto diário com combustível.

Com base nesta necessidade, cada colaborador pode realizar uma pesquisa na região onde mora e inserir os dados nesta calculadora para obter insights rápidos e práticos.

-----

## Funcionalidades

A calculadora interage com o usuário através de prompts para coletar os seguintes dados:

1.  **Distância percorrida (casa-trabalho):** Em quilômetros (km).
2.  **Consumo médio do veículo:** Em quilômetros por litro (km/L).
3.  **Quantidade de postos pesquisados:** Número inteiro de postos.
4.  **Valor do combustível em cada posto:** Preço em Reais (R$) por litro.

Após a coleta dos dados, o programa calcula e exibe:

  * **Consumo necessário em litros:** Quantidade de litros para o deslocamento de ida.
  * **Menor valor de combustível encontrado:** O preço mais baixo entre os postos pesquisados.
  * **Média dos valores pesquisados:** A média aritmética dos preços informados.
  * **Gasto diário com combustível (ida e volta):** O custo total considerando a ida e volta, utilizando o menor valor de combustível encontrado.

-----

## Como Usar

Para utilizar a calculadora, siga os passos abaixo:

1.  **Clone o repositório** para o seu ambiente local:
    ```bash
    git clone https://github.com/seu-usuario/calculadora-combustivel-ford.git
    ```
2.  **Navegue até o diretório do projeto**:
    ```bash
    cd calculadora-combustivel-ford
    ```
3.  **Abra o arquivo `index.html`** no seu navegador web preferido.

Ao abrir o `index.html`, a aplicação irá iniciar automaticamente, solicitando as informações através de janelas de `prompt`. Siga as instruções e insira os dados conforme solicitado. Os resultados serão exibidos diretamente na página.

-----

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

  * `index.html`: Contém a estrutura HTML da página, os estilos CSS incorporados e o código JavaScript responsável pela lógica da calculadora.
  * `posto.jpg`: Imagem de fundo utilizada na página.
  * Arquivos de logotipo (`data:image/png;base64,...`): Os logotipos do SENAI CIMATEC e da Ford são incorporados diretamente no HTML como dados Base64.

-----

## Contribuição

Se você deseja contribuir com melhorias para este projeto, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

-----

## Licença

Este projeto é de código aberto e está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo `LICENSE` (se houver, caso contrário, adicione um, ou mencione que a licença está implícita para fins de demonstração).

-----
