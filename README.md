# Egern Config

Egern configuration snippets and JavaScript widgets.

## Widgets

### World Cup Schedule

- Script: `scripts/WorldCup_Widget.js`
- Config snippet: `configs/WorldCup_Widget.yaml`
- Data source: ESPN FIFA World Cup (`fifa.world`)

Required widget env:

```yaml
DATA_SOURCE: "espn"
ESPN_LEAGUE: "fifa.world"
```

The widget shows yesterday, today, and tomorrow in Beijing time. Finished matches show scores in the middle of the team names, live matches show `进行中`, and scheduled matches show kickoff time. Team names are displayed in Chinese with country flags when the team can be matched.

### QWeather

- Script: `scripts/QWeather_Widget.js`
