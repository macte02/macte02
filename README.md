## Hi, I'm Mac

I'm doing an MSc in Machine Learning, Data Science and AI at Aalto, plus a bachelor's in economics alongside it.
Most of what I build is ML on real market data, mainly housing and used cars. I also run a YouTube network
(307k subscribers) and co-founded a small used-car company, LT Auto Oy.

### Things I've built

**[Housing price model](https://github.com/macte02/asuntovahti)**: estimates what Finnish homes actually sell
for, trained on 104k+ completed sales. On sales after the training cutoff it gets R² 0.92 for apartments and
row houses, and around 10% median error in Helsinki, Espoo and Vantaa.

<a href="https://github.com/macte02/asuntovahti"><img src="https://raw.githubusercontent.com/macte02/asuntovahti/main/assets/estimate_vs_actual.png" width="480" alt="Housing model: estimate vs actual price"></a>

**[What a fault does to a car's price](https://github.com/macte02/car-fault-prices)**: how much an engine
light, rust or a gearbox problem takes off a used car's price, measured on 21,911 sold Finnish auction
cars. On a car worth 2,000 €, an engine warning light costs about 466 €.

**Used-car deal finder** (private repo): watches new private-seller listings, works out each car's exact
model generation from its plate and flags anything listed €1,500+ under comparable sales. We've bought 30+
cars through it at LT Auto. The same repo now has a Telegram bot that writes our auction listings: send it a
plate, photos and a few notes and it comes back with a ready-to-review draft.

**YouTube retention model + creator tools** (private repo): an NLP model that reads a video's transcript and
predicts where viewers drop off; on videos it never saw, its top flags are real drop-offs twice as often as
chance. Plus a DaVinci Resolve panel that bakes spring animations into Fusion keyframes, which cut my routine
production time by 30%+.

### Stack

Python, PyTorch, CatBoost, LightGBM, scikit-learn, sentence-transformers, pandas · C++ / CUDA · Scala · JavaScript · SQL · Docker, Git, Linux

You can find me on [LinkedIn](https://www.linkedin.com/in/mac-teppo).
