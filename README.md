# NewProject
## Day Trader skills

The 11 skills from [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill)
(MIT, commit `3d0f4ef`) are installed project-local in `.claude/skills/trader-*`.
Invoke them as `/trader-scanner`, `/trader-timemachine`, etc. They need Python 3.8+
and network access to `query1/query2.finance.yahoo.com`, `feeds.finance.yahoo.com`,
`www.nasdaqtrader.com`, `data.sec.gov`, `www.sec.gov` and `disclosures-clerk.house.gov`.
Output goes in `trader/`. Paper trading by default; nothing places an order without your yes.
