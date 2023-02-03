# Stats

## Match Analysis

Recebe matchID como parâmetro e retorna dados das partidas dos últimos 7 dias e dos próximos 7 dias.

- Head to head -> Últimos 20 confrontos diretos dos 2 times em questão
- Home Last Matches -> Últimos 20 jogos do time da casa
- Away Last Matches -> Últimos 20 jogos do time visitante
- Todos estes retornan os seguintes dados:

  - MatchID
  - LeagueID
  - League
  - Color
  - MatchTime
  - MatchType
  - HomeTeamID
  - Home
  - AwayteamId
  - Away
  - HomeScore
  - HomeHalfScore
  - AwayScore
  - AwayHalfScore
  - Result (MoneyLine)
  - ScoreGap
  - Spread odds
  - SpreadResult ()
  - Total
  - TotalOdds
  - TotalResult

- Home Schedule -> Últimos 3 e próximos 3 confrontos do time da casa
- Away Schedule -> Últimos 3 e próximos 3 confrontos do time visitante
- Esses 2 retornam os seguintes dados
  - MatchId
  - LeagueId
  - League
  - Color
  - MatchTime
  - HomeTeamId
  - Home
  - Score
  - AwayTeamId
  - Away
  - Day

## Match Stats

Envia a data como parâmetro e recebe jogos que aconteceram no dia. Tem opção default que retorna partidas nas últimas 24 horas.

- MatchId
- HomeTeamName
- AwayTeamName
- CostTime
- HomeScore
- HomeFastScore
- HomeInsideScore
- HomeLeadingScore
- HomeTotalMiss
- AwayScore
- AwayFastScore
- AwayInsideScore
- AwayLeadingScore
- AwayTotalMiss
- Home Players / Away Players
  - PlayerId
  - PlayerName
  - Location
  - Playing Time
  - ShotHit
  - Shot
  - ThreePointHit
  - ThreePointShot
  - PenaltyShotHit (free throw)
  - PenaltyShot
  - Attack (offensive rebouds)
  - Defend (defensive rebounds)
  - Assist
  - Foul
  - Rob (Steal)
  - Miss (TurnOver)
  - Cover (block)
  - Score
  - OnFloor(ta no jogando?)

## Standing

Envia id da liga e recebe dados dos times em ordem de colocação na tabela

- LeagueName
- TeamId
- TeamName
- MatchSeason
- HomeWin
- HomeLoss
- AwayWin
- AwayLoss
- WinScale
- State (Numero de derrotas ou vitórias em sequencia)
- HomeRank
- AwayRank
- TotalRank
- Home Score
- Home Loss Score
- Away Score ( AWAY SCORE + HOME SCORE = TOTAL DE PONTOS )
- AwayLossScore
- NearlyTenWin (Quantos dos últimos 10 jogos ganhou)
- NearlyTenLoss (Quantos dos últimos 10 jogos perdeu)
