\# Fake News Detector



A browser-based tool that checks a news headline or article and gives it a credibility score out of 100. It marks the phrases that raise doubt in red and the phrases that build trust in green.



\*\*Live demo:\*\* https://aashikapal225-pixel.github.io/fake-news-detector/



\## Features



\- Credibility score and verdict: Looks credible, Unclear, or Likely fake or misleading

\- Marked-up text showing which phrases affected the score

\- A "Why this score" list explaining every signal found

\- Runs fully in the browser; no text is sent anywhere



\## How it works



The detector analyses writing style using rule-based checks.



\*\*Signals that raise doubt:\*\* sensational words, clickbait phrases, conspiracy framing, absolute claims, ALL-CAPS words, repeated exclamation marks, pressure to share, and no named source.



\*\*Signals that build trust:\*\* named sources, direct quotations, specific figures and measured wording.



Each signal adds or removes points from a starting score, and the final result is shown as a credibility meter.



\## Limitations



The detector does not verify facts. A well-written false article can score high, and a blunt true one can score low. Use the score as a prompt to check the source, the date and a second outlet.



\## Run locally



Download or clone the repository and open `index.html` in any browser.



\## Tech stack



HTML, CSS and JavaScript (no frameworks)



\## Version control



This project was built for the Version Control Systems course and uses Git branches (`main`, `feature/readme`, `feature/more-rules`), merges and tagged releases.

