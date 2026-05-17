# Real-Time System Conference Deadlines

Live countdown to upcoming full-paper submission deadlines for real-time and
hardware-systems conferences (RTSS, RTAS, DAC).

Single static `index.html` — open in a browser, or visit the deployed page.

## Tracked conferences

| Conference | Track | Source |
|------------|-------|--------|
| RTSS | Full Paper Submission | <https://2026.rtss.org/cfp/> |
| RTAS | Full Paper Submission | <https://2026.rtas.org/cfp/> |
| DAC  | Full Paper Submission | <https://dac.com/2026/program/research-manuscript-submissions> |

Entries marked **예정** are estimates derived from the previous year's
schedule; they are replaced with confirmed dates once the official CFP is
published.

## Updating a deadline

Edit the `DEADLINES` array in `index.html`. Use the `aoe('YYYY-MM-DD')`
helper for "Anywhere on Earth" deadlines and `pst5pm('YYYY-MM-DD')` for
DAC-style 5 PM Pacific deadlines. Drop the `estimated: true` flag once the
official CFP is announced.

## License

MIT &mdash; see [LICENSE](LICENSE).
