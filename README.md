# tesla-charging-efficiency
Measurements of AC charging with a Model13 2019

I used a Metrawatt Metrahit Energy to measure AC input currentinthe Tesla UMC. Power source was a solar inverter.
To see how much energy actually went into the Tesla battery I read the CAN bus with [tescan](https://github.com/fl4p/tescan).

This is the spreadsheet: https://docs.google.com/spreadsheets/d/1Oi3W_DFBBovNbPTJ79Z7qiXGqlJmS1QXwg5fTbDIK8I/edit?usp=sharing
I usedlong cables though (30m 2.5mm2 + 10m 1.5mm2)

The measured AC current on the multimeter matched very well with the charging current displayed on the Tesla screen.
The board computer always consumes 120 W or more, so charging efficiency is bad for low current (5 A).
