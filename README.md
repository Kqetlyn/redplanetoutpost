# Red Planet Outpost

A Mars-base survival game for curious kids (ages 7–12). Keep a 4-person crew alive in Jezero Crater from sunrise to sunrise by deciding where your solar power goes: heaters, air, grow lights, lab and radio.

**Play it:** https://kqetlyn.github.io/redplanetoutpost/

## The five sols
| Sol | What happens | The trade-off |
|---|---|---|
| 1 · Sunrise to sunrise | Sun shines only 12 hours | Spend power now, or save it for tonight? |
| 2 · Phone home | A satellite passes at 15:00 and 03:00 | When is it worth switching the radio on? |
| 3 · Dust storm | Solar power drops to a third | Get ready before the dust rolls in |
| 4 · Breakdown | Air maker drops to 25% at 16:00 | Fix it yourselves (fast, 10 kW) or wait for Earth (no power, fix at 03:00)? |
| 5 · Everything at once | Dust storm, solar storm and breakdown in one sol | Repair it outside in the radiation, or wait and protect the crew? |

## Built on real data
Temperatures are shaped to Perseverance's MEDA weather station at Jezero, dust effects to Opportunity's 2018 dust storm, radiation to Curiosity's RAD instrument (including the 20 May 2024 solar storm), and oxygen use to NASA's life-support value of 0.84 kg per astronaut per sol. The in-game "Where the numbers come from" page lists every source and marks what is real, shaped by data, or game scale.

## Run it
It is a single file: open `index.html` in any modern browser. No install needed.

## AI acknowledgment
This project was built with AI assistance. The code (HTML, CSS, JavaScript), the in-game text and the code-drawn graphics were generated with **Claude**, an AI assistant made by Anthropic. Claude was also used to look up and cite the NASA data and to run automated balance tests of each level.

Our team came up with the idea, chose the features, levels and trade-offs, played and tested every version, and directed each change.

- The page's metadata says so too (`<meta name="ai-generated">`, `<meta name="ai-disclosure">`, `<meta name="generator">`), and so does the comment at the top of `index.html`.
- The game shows a visible "AI-generated with Claude" label on screen, and an AI acknowledgment on the title screen and the sources page.
- No NASA logos, flags, mission patches or other NASA branding are used.
