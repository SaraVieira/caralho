# PostCSS Caralho Plugin [![Travis](https://travis-ci.org/SaraVieira/postcss-caralho.svg?branch=master)](https://travis-ci.org/SaraVieira/postcss-caralho)
[![Coverage Status](https://coveralls.io/repos/github/SaraVieira/postcss-caralho/badge.svg?branch=master)](https://coveralls.io/github/SaraVieira/postcss-caralho?branch=master)
[![npm](https://badge.fury.io/js/postcss-caralho.svg)](https://www.npmjs.com/package/postcss-caralho)

<a target='_blank' rel='nofollow' href='https://app.codesponsor.io/link/TcwA1EShekGpPzRyQvGn9ysQ/SaraVieira/postcss-caralho'>
  <img alt='Sponsor' width='888' height='68' src='https://app.codesponsor.io/embed/TcwA1EShekGpPzRyQvGn9ysQ/SaraVieira/postcss-caralho.svg' />
</a>

[PostCSS] plugin for that changes curse words after ! to !important because why not ?

[PostCSS]: https://github.com/postcss/postcss

```css
.foo {
    top: 20px !fuck;
}
```

```css
.foo {
    top: 20px !important;
}
```

You can also use:


### Portuguese
* caralho (fuck)
* foda-se (fuck)
* merda (shit)
* desculpa (sorry)
* putaqpariu (fuck this)
* desisto (I quit)
* bardamerda (This rally does not have a translation)

### Brazilian
* filhodaputa (son of a bitch)
* demonio (demon)
* satanas (satan)
* desgraça (disgrace)
* paunocu (stick in the ass)
* feijoada (This rally does not have a translation)

### English
* fuckthis
* fuck
* sorry
* shit
* please

### German
* scheisse (fuck)
* scheiße (crap)
* verdammt (damned)
* kacke (shit)

### Persian
* jakesh (Pander)
* daus (Cuckold)
* antar (Baboons)
* pofuz (Nerveless)
* lanati (Damn)
* lamasab (Damn)
* kooni (Catamite)

### Konkani (Google cannot translate PR anyone ?)
* chont
* fodo
* fodri
* zov

### Hindi (Googles translations are horrible PR anyone ?)
* lund
* lavda
* choot

### Russian
* блять (fuck)
* сука (bitch)
* тварь (creature)
* работай (work)
* чезахуйня (chezahuyna?)
* гандон (Gondon?)
* скемнебывает (It happens to everyone)
* упс (oops)
* ебанина (fucker)
* какаятоебанина (a kind of banana)

### Spanish
* joder (fuck)
* mierda (shit)
* perdona (sorry)
* porfavor (please)

### French
* merde (shit)
* putain (fuck)
* saloperie (fucking thing)
* couillon (fucker)
* con (twat)
* foutu (fucked)
* trouduc (asshole)
* enfoiré (untranslatable, lit. "covered in shit")
* bordel (used like fuck, lit. "bordello")
* chier (to shit)
* abruti (dulled by work)
* crève (die)
* enflure (untranslatable, lit. "swollen inflamation")
* pardon (sorry)
* stp (please)

### Serbian
* sranje (shit)
* govno (shit)
* jebiga (fuck)
* jebeno (fucking thing)
* picka (cunt)
* sisica (means small boob, but context is pussy)
* kurac (dick)
* cmar (asshole)
* izvini (sorry)
* ups (ooops)
* upickumaterinu ("u picku materinu" in mother pussy)
* mrsupickumaterinu ("mars u picku materinu" go to your mother's pussy)
* stakojikurac ("sta koji kurac" what the fuck)
* jebemmumisa ("jebem mu misa" I fuck his mouse)
* jebotebog ("jebo te bog" god fuck you)
* jebotipasmater ("jebo ti pas mater" dog fucks your mother)
* jebotikonjmater ("jebo ti konj mater" horse fucks your mother)
* jebotikonjkrvavimkurcemmater ("jebo ti konj krvavim kurcem mater" horse fucks your mother with bloody dick)
* jebemtisvestosezakvakuuhvati ("jebem ti sve sto se za kvaku uhvati" i fuck your everyone who used your door knob)


And all of this will become important after PostCSS does his thing.

## Why ?

Idk, mainly boredom and the need to write !caralho or !fuck in every stylesheet I own.

## I want to add words !

Awesome ! You can create a PR here:
[https://github.com/SaraVieira/curse-words](https://github.com/SaraVieira/curse-words) and these tests and the ones in [https://github.com/SaraVieira/babel-plugin-caralho](https://github.com/SaraVieira/babel-plugin-caralho) will be generated automatically 🎉

## Install

Install from NPM using:

```
npm i postcss-caralho --save-dev
```

Or Yarn:

```
yarn add postcss-caralho --dev
```

## Usage

```js
postcss([ require('postcss-caralho') ])
```

See [PostCSS] docs for examples for your environment.


## License

Use as you please to confuse people and enjoy (MIT)
