# Climapp

**MATC84 - Laboratório de Programação Web  - Atividade workshop Vue**

## Atividade
Com base na estrutura e estilo abaixo:

![Climapp](./src/assets/image.png)

Finalize a interface do Climapp adicionando a função de obter os dados da API [Weatherapi](https://www.weatherapi.com/) quando o usuário clicar em "Pesquisar" e mostrar o resultado na tela.

Os locais para completar o código estão indicados pelos comentários:

Dentro do template em:

```html
<main class="clima__conteudo">
  <!-- Complete a estrutura -->
</main>
```
E dentro do Script:
```js
getClima() {
  [...]
  // Adicionar a chamada da API weatherapi.com
  // Armazenar o resultado em climaData
},
```
**Lista de todos os dados retornados após pesquisar por "Salvador"**

* OBS: Não é necessário exibir todos os dados retornados. Escolha os mais relevantes.

```json
{
    {
    "location": {
        "name": "Salvador",
        "region": "Bahia",
        "country": "Brazil",
        "lat": -12.98,
        "lon": -38.52,
        "tz_id": "America/Bahia",
        "localtime_epoch": 1686529270,
        "localtime": "2023-06-11 21:21"
    },
    "current": {
        "last_updated_epoch": 1686528900,
        "last_updated": "2023-06-11 21:15",
        "temp_c": 27,
        "temp_f": 80.6,
        "is_day": 0,
        "condition": {
            "text": "Parcialmente nublado",
            "icon": "//cdn.weatherapi.com/weather/64x64/night/116.png",
            "code": 1003
        },
        "wind_mph": 8.1,
        "wind_kph": 13,
        "wind_degree": 110,
        "wind_dir": "ESE",
        "pressure_mb": 1018,
        "pressure_in": 30.06,
        "precip_mm": 0,
        "precip_in": 0,
        "humidity": 74,
        "cloud": 25,
        "feelslike_c": 29.7,
        "feelslike_f": 85.5,
        "vis_km": 10,
        "vis_miles": 6,
        "uv": 1,
        "gust_mph": 15,
        "gust_kph": 24.1
    }
  }
}
```

## Executando o projeto pelo Vue playground
Acesse [Vue SFC Playground](https://play.vuejs.org) ou [Playcode](https://playcode.io/vue)

Copie o código do arquivo Clima.vue localizado em `src/components/Clima.vue` 

Cole o código no playground e execute o projeto.

Após concluir a atividade, copie o código final do playground, crie um novo arquivo com a extensão .vue e envie-o através do formulário disponibilizado pela equipe.

## Executando o projeto localmente
#### Instruções de instalação

Certifique-se de ter o Yarn instalado em sua máquina:

```bash
npm install --global yarn
```

Clone o projeto do repositório do Github:

```bash
# Para conexões https:
git clone https://github.com/moniquedsilva/climapp.git

# Para conexões ssh:
git clone git@github.com:moniquedsilva/climapp.git
```

Após concluir o clone do projeto, instale as dependências e o node_modules:

```bash
yarn install
```

Para executar o projeto localmente:

```bash
yarn serve
```

Para visualizá-lo, abra o navegador e digite: `localhost:8080`. A numeração da porta pode variar dependendo da sua rede.

Após concluir a atividade, envie apenas o arquivo Clima.vue para o formulário disponibilizado pela equipe.