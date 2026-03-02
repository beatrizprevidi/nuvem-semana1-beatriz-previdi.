# Semana 1 - Deploy estatico (GitHub Pages)
## Links
- Repositorio:   https://github.com/beatrizprevidi/nuvem-semana1-beatriz-previdi.?tab=readme-ov-file
- Site (GitHub Pages): https://beatrizprevidi.github.io/nuvem-semana1-beatriz-previdi./
## O que foi feito
- Criei index.html, style.css e script.js pelo navegador
- Ativei GitHub Pages (main / root)
## Dificuldades
- A atividade foi bem tranquila até certo ponto. Na hora de colar o link do repositório, ele dava erro 404. Segui as instruções do professor, mas mesmo assim não deu certo. O repositório está público e tudo certo. Se eu colo o link no navegador, funciona. Mas se eu clico no link aparece um erro.

# Semana 2 - ( GET + POST)
- Tinha um único erro que estava atrapahlhando a minha atividade, acredito que era culpa do meu navegador. Alguma extensão que estava impedindo o funcionamento do código. Para resolver, eu abri em uma aba anônima e colei o código lá, e então funcionou sem erros.
GET:
{
  "fonte": "open-meteo.com",
  "temperatura": 24,
  "vento": 15.6,
  "unidade_temp": "°C",
  "unidade_vento": "km/h",
  "bruto": {
    "latitude": -24.375,
    "longitude": -53.875,
    "generationtime_ms": 0.03886222839355469,
    "utc_offset_seconds": 0,
    "timezone": "GMT",
    "timezone_abbreviation": "GMT",
    "elevation": 329,
    "current_units": {
      "time": "iso8601",
      "interval": "seconds",
      "temperature_2m": "°C",
      "wind_speed_10m": "km/h"
    },
    "current": {
      "time": "2026-03-02T11:45",
      "interval": 900,
      "temperature_2m": 24,
      "wind_speed_10m": 15.6
    }
  }
POST:
{
  "fonte": "jsonplaceholder.typicode.com",
  "resposta": {
    "turma": "Serviços em Nuvem",
    "atividade": "Semana 2",
    "timestamp": "2026-03-02T12:03:22.929Z",
    "id": 101
  }
}
