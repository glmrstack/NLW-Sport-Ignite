# BACK-END DETAILS

## ENTITIES

### GAMES
  id
  title
  bannerUrl

### ADS
  - id
  - gameId
  - name
  - yearsPlaying
  - discord
  - weekDays
  - hourStart
  - hourEnd
  - useVoiceChannel
      [0 or 1]
  - createdAt
      [0, 1, 2, 3, 4, 5, 6]

## USE CASES
  - Listagem de games com contagem de anúncios
  - Criação de novo anúncio
  - Listagem de anúncios por game
  - Buscar discord pelo ID do anúncio
