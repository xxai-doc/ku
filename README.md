<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Tête pêşniyar kirin ku pêşî nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) saz bikin, û dûv re jî `direnv allow` piştî ku têkevin pelrêça ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) piştî têketina pelrêçê dê bixweber were darve kirin).

Wate ev e: Wergera Çînî bo Japonî, Koreyî, Îngilîzî, wergera Îngilîzî ji bo hemû zimanên din. Heke hûn tenê dixwazin piştgirî bidin Çînî û Îngilîzî, hûn dikarin tenê `zh: en` .

Wate ev e: Wergera Çînî bo Japonî, Koreyî, Îngilîzî, wergera Îngilîzî ji bo hemû zimanên din. Heke hûn tenê dixwazin piştgirî bidin Çînî û Îngilîzî, hûn dikarin tenê `zh: en` .

* [koda pêş-end](https://github.com/xxai-art/web)
* [Ji bo malperê bi tevahî pakêtên zimanî](https://github.com/xxai-art/web/tree/main/i18n)
* [Ji bo modulên têketinê pakêtên ziman](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Malpera Belgekirina Pirzimanî](https://github.com/xxai-doc)

Zimanê bernamesaziya pêşîn [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) e, ku li ser bingeha hevoksaziya qehwenivîsê hin taybetmendiyan zêde dike, li [./coffee_plus.md](./coffee_plus.md) binêre.

## Navneteweyîkirina malper û belgeyan

Li ser 3 projeyên jêrîn ava bikin

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Paşgira `.mdt` e, hûn dikarin hevoksaziya mîna `<+ ./coffee_plus/import.js>` bikar bînin da ku li pelên derve bigerin, û bi paşgira `.md` nîşanek çêbikin.

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Wergera Markdown dê kod û girêdan wernegerîne, û dê hevokên wergerandî cache bike. Ger werger were guheztin lê metna orîjînal neyê guheztin, ger ew werger ji nû ve were guheztin dê guheztina werger ji ser nekeve.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Pelên zimanî ji bo wergerandina malperên ku `yaml` hatine çêkirin.

### Talîmatên Xweseriya Wergera Belge

Binêre depoya kodê [xxai-art/doc](https://github.com/xxai-art/doc)

Tête pêşniyar kirin ku pêşî nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) saz bikin, û dûv re jî `direnv allow` piştî ku têkevin pelrêça ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) piştî têketina pelrêçê dê bixweber were darve kirin).

Ji bo ku ez ji bingeha koda mezin a ku bi sedan zimanan hatî wergerandin dûr bixim, min ji bo her zimanî bingehek kodek cihê afirand û rêxistinek ku bingeha kodê hilîne çêkir.

Danîna guhêrbara jîngehê `GITHUB_ACCESS_TOKEN` û dûv re xebitandina [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) dê bixweber depoya kodê biafirîne.

Bê guman, hûn dikarin wê di bingehek kodê de jî bixin.

Referansa script werger [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Koda skrîptê wiha tê şîrovekirin:

[bunx](https://bun.sh/docs/cli/bunx) şûna npx-ê ye, ku zûtir e. Bê guman, heke we bun saz nekiribe, hûn dikarin li şûna wê `npx` bikar bînin.

`bunx mdt zh` `.mdt` di pelrêça zh de wekî `.md` nîşan dide , li 2 pelên girêdayî li jêr binêre

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ji bo wergerandinê koda bingehîn e (heke we tenê `nodejs` sazkirî be, lê `bun` û `direnv` nehatine saz kirin, hûn dikarin `npx i18n` jî ji bo wergerandinê bimeşînin).

Ew ê [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) parsek bike, veavakirina `i18n.yml` di vê belgeyê de wiha ye:

```
en:
zh: ja ko en
```

Wate ev e: Wergera Çînî bo Japonî, Koreyî, Îngilîzî, wergera Îngilîzî ji bo hemû zimanên din. Heke hûn tenê dixwazin piştgirî bidin Çînî û Îngilîzî, hûn dikarin tenê `zh: en` .

Ya dawî [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) ye, ku naverokê di navbera sernavê sereke û jêrnivîsa yekem a `README.md` ya her zimanî de derdixe da ku têketinek `README.md` çêbike. Kod pir hêsan e, hûn dikarin bi xwe lê binêrin.

Google API ji bo wergera belaş tê bikaranîn. Ger hûn nikaribin bigihîjin Google, ji kerema xwe proxyek mîheng bikin û saz bikin, wek:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Skrîpta wergerê dê di pelrêça `.i18n` de cache-ya wergerî çêbike, ji kerema xwe wê bi `git status` kontrol bike û li depoya kodê zêde bike da ku ji wergerên dubare dûr bikevin.

Ji kerema xwe her gava ku hûn werger biguherînin da ku cache nûve bikin, `bunx i18n` bimeşînin.

Ger nivîsa orîjînal û werger di heman demê de bêne guheztin, cache dê tevlihev bibe, ji ber vê yekê heke hûn bixwazin biguhezînin, hûn dikarin tenê yek biguhezînin, û dûv re `bunx i18n` bimeşînin da ku kaşê nûve bikin.
