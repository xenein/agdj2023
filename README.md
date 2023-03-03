# agdj2023
ich hab das nie gewollt.

wir bauen uns jetzt mal ein "Buschmann rück das SBG raus"-AGDJ. Kürzer, knackiger und nur über SBG mit VÄ/PÄ.

Das deployt automagisch nach https://2023.allegutendinge.jetzt

## lokal bauen und testen

well es ist ein Jekyll, wir brauchen ruby und wir brauchen bundle


```
git clone https://github.com/xenein/agdj2023.git
cd agdj2023
bundle install
bundle exec jekyll serve
```

und wir haben auf localhost:4000 einen Dev-Server. Nice. 

## build

```
bundle exec jekyll build
```

und wir haben in `_site` (die in der gitignore steht) eine deploybare Version der gebauten static site.
