# Heritage Themes for yazi

Colour themes drawn from the colour traditions of different cultures. This repository holds the [yazi](https://github.com/sxyazi/yazi) flavors, one folder for each theme, generated from [Heritage Themes](https://github.com/heritage-themes/heritage-themes); report issues and changes there.

## Install

Install a dark and a light flavor with yazi's package manager:

```bash
ya pkg add heritage-themes/yazi-flavors:heritage-holi-night
ya pkg add heritage-themes/yazi-flavors:heritage-holi-day
```

Then name them in `theme.toml` in yazi's configuration folder, `~/.config/yazi/theme.toml` on Linux and macOS:

```toml
[flavor]
dark = "heritage-holi-night"
light = "heritage-holi-day"
```

yazi applies the flavor that matches the terminal's background. It draws on the terminal's own background, so run it in a terminal with 24-bit colour that runs the matching theme of the [Heritage Themes for terminals](https://github.com/heritage-themes/heritage-themes/releases/latest). Update installed flavors with `ya pkg upgrade`.

## Flavors

| Flavor | Mode | Family |
|---|---|---|
| `heritage-ainu-kaparamip-dark` | Dark | [Ainu](https://github.com/heritage-themes/heritage-themes/tree/master/themes/ainu) |
| `heritage-ainu-attus-light` | Light | [Ainu](https://github.com/heritage-themes/heritage-themes/tree/master/themes/ainu) |
| `heritage-aizome-kachi-dark` | Dark | [Aizome](https://github.com/heritage-themes/heritage-themes/tree/master/themes/aizome) |
| `heritage-aizome-kamenozoki-light` | Light | [Aizome](https://github.com/heritage-themes/heritage-themes/tree/master/themes/aizome) |
| `heritage-bengal-baluchari-dark` | Dark | [Bengal](https://github.com/heritage-themes/heritage-themes/tree/master/themes/bengal) |
| `heritage-bengal-laal-paar-light` | Light | [Bengal](https://github.com/heritage-themes/heritage-themes/tree/master/themes/bengal) |
| `heritage-danqing-ink-dark` | Dark | [Danqing](https://github.com/heritage-themes/heritage-themes/tree/master/themes/danqing) |
| `heritage-danqing-paper-light` | Light | [Danqing](https://github.com/heritage-themes/heritage-themes/tree/master/themes/danqing) |
| `heritage-edo-cha-dark` | Dark | [Edo](https://github.com/heritage-themes/heritage-themes/tree/master/themes/edo) |
| `heritage-edo-nezumi-light` | Light | [Edo](https://github.com/heritage-themes/heritage-themes/tree/master/themes/edo) |
| `heritage-gujarat-navratri-dark` | Dark | [Gujarat](https://github.com/heritage-themes/heritage-themes/tree/master/themes/gujarat) |
| `heritage-gujarat-rann-light` | Light | [Gujarat](https://github.com/heritage-themes/heritage-themes/tree/master/themes/gujarat) |
| `heritage-hmong-batik-dark` | Dark | [Hmong](https://github.com/heritage-themes/heritage-themes/tree/master/themes/hmong) |
| `heritage-hmong-hemp-light` | Light | [Hmong](https://github.com/heritage-themes/heritage-themes/tree/master/themes/hmong) |
| `heritage-holi-night` | Dark | [Holi](https://github.com/heritage-themes/heritage-themes/tree/master/themes/holi) |
| `heritage-holi-day` | Light | [Holi](https://github.com/heritage-themes/heritage-themes/tree/master/themes/holi) |
| `heritage-kalaallisuut-qernertoq-dark` | Dark | [Kalaallisuut](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kalaallisuut) |
| `heritage-kalaallisuut-qaqortoq-light` | Light | [Kalaallisuut](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kalaallisuut) |
| `heritage-kalamkari-indigo-dark` | Dark | [Kalamkari](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kalamkari) |
| `heritage-kalamkari-cotton-light` | Light | [Kalamkari](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kalamkari) |
| `heritage-kashubia-zemia-dark` | Dark | [Kashubia](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kashubia) |
| `heritage-kashubia-niebo-light` | Light | [Kashubia](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kashubia) |
| `heritage-kerala-backwaters-dark` | Dark | [Kerala](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kerala) |
| `heritage-kerala-kasavu-light` | Light | [Kerala](https://github.com/heritage-themes/heritage-themes/tree/master/themes/kerala) |
| `heritage-lowicz-wycinanka-dark` | Dark | [Łowicz](https://github.com/heritage-themes/heritage-themes/tree/master/themes/lowicz) |
| `heritage-lowicz-kodra-light` | Light | [Łowicz](https://github.com/heritage-themes/heritage-themes/tree/master/themes/lowicz) |
| `heritage-maramures-zadie-dark` | Dark | [Maramureș](https://github.com/heritage-themes/heritage-themes/tree/master/themes/maramures) |
| `heritage-maramures-canepa-light` | Light | [Maramureș](https://github.com/heritage-themes/heritage-themes/tree/master/themes/maramures) |
| `heritage-maya-corte-dark` | Dark | [Maya](https://github.com/heritage-themes/heritage-themes/tree/master/themes/maya) |
| `heritage-maya-huipil-light` | Light | [Maya](https://github.com/heritage-themes/heritage-themes/tree/master/themes/maya) |
| `heritage-morocco-majorelle-dark` | Dark | [Morocco](https://github.com/heritage-themes/heritage-themes/tree/master/themes/morocco) |
| `heritage-morocco-marrakech-dark` | Dark | [Morocco](https://github.com/heritage-themes/heritage-themes/tree/master/themes/morocco) |
| `heritage-morocco-zellige-dark` | Dark | [Morocco](https://github.com/heritage-themes/heritage-themes/tree/master/themes/morocco) |
| `heritage-mudhif-qir-dark` | Dark | [Mudhif](https://github.com/heritage-themes/heritage-themes/tree/master/themes/mudhif) |
| `heritage-mudhif-qasab-light` | Light | [Mudhif](https://github.com/heritage-themes/heritage-themes/tree/master/themes/mudhif) |
| `heritage-mughal-night` | Dark | [Mughal](https://github.com/heritage-themes/heritage-themes/tree/master/themes/mughal) |
| `heritage-mughal-wasli-light` | Light | [Mughal](https://github.com/heritage-themes/heritage-themes/tree/master/themes/mughal) |
| `heritage-ndebele-nzima-dark` | Dark | [Ndebele](https://github.com/heritage-themes/heritage-themes/tree/master/themes/ndebele) |
| `heritage-ndebele-mhlophe-light` | Light | [Ndebele](https://github.com/heritage-themes/heritage-themes/tree/master/themes/ndebele) |
| `heritage-peru-kulli-dark` | Dark | [Peru](https://github.com/heritage-themes/heritage-themes/tree/master/themes/peru) |
| `heritage-peru-puka-dark` | Dark | [Peru](https://github.com/heritage-themes/heritage-themes/tree/master/themes/peru) |
| `heritage-podhale-klobuk-dark` | Dark | [Podhale](https://github.com/heritage-themes/heritage-themes/tree/master/themes/podhale) |
| `heritage-podhale-sukno-light` | Light | [Podhale](https://github.com/heritage-themes/heritage-themes/tree/master/themes/podhale) |
| `heritage-punjab-phulkari-dark` | Dark | [Punjab](https://github.com/heritage-themes/heritage-themes/tree/master/themes/punjab) |
| `heritage-punjab-basant-light` | Light | [Punjab](https://github.com/heritage-themes/heritage-themes/tree/master/themes/punjab) |
| `heritage-rajasthan-blue-city-dark` | Dark | [Rajasthan](https://github.com/heritage-themes/heritage-themes/tree/master/themes/rajasthan) |
| `heritage-rajasthan-pink-city-light` | Light | [Rajasthan](https://github.com/heritage-themes/heritage-themes/tree/master/themes/rajasthan) |
| `heritage-sardinia-orbace-dark` | Dark | [Sardinia](https://github.com/heritage-themes/heritage-themes/tree/master/themes/sardinia) |
| `heritage-sardinia-camisa-light` | Light | [Sardinia](https://github.com/heritage-themes/heritage-themes/tree/master/themes/sardinia) |
| `heritage-shaker-prussian-dark` | Dark | [Shaker](https://github.com/heritage-themes/heritage-themes/tree/master/themes/shaker) |
| `heritage-shaker-plaster-light` | Light | [Shaker](https://github.com/heritage-themes/heritage-themes/tree/master/themes/shaker) |
| `heritage-shuimo-night` | Dark | [Shuimo](https://github.com/heritage-themes/heritage-themes/tree/master/themes/shuimo) |
| `heritage-shuimo-day` | Light | [Shuimo](https://github.com/heritage-themes/heritage-themes/tree/master/themes/shuimo) |
| `heritage-tamil-kolam-dark` | Dark | [Tamil](https://github.com/heritage-themes/heritage-themes/tree/master/themes/tamil) |
| `heritage-tamil-olai-light` | Light | [Tamil](https://github.com/heritage-themes/heritage-themes/tree/master/themes/tamil) |
| `heritage-wixarika-haramara-dark` | Dark | [Wixárika](https://github.com/heritage-themes/heritage-themes/tree/master/themes/wixarika) |
| `heritage-wixarika-wirikuta-light` | Light | [Wixárika](https://github.com/heritage-themes/heritage-themes/tree/master/themes/wixarika) |
| `heritage-wuxing-night` | Dark | [Wuxing](https://github.com/heritage-themes/heritage-themes/tree/master/themes/wuxing) |
| `heritage-wuxing-day` | Light | [Wuxing](https://github.com/heritage-themes/heritage-themes/tree/master/themes/wuxing) |
| `heritage-yolngu-galawu-dark` | Dark | [Yolŋu](https://github.com/heritage-themes/heritage-themes/tree/master/themes/yolngu) |
| `heritage-yolngu-gapan-light` | Light | [Yolŋu](https://github.com/heritage-themes/heritage-themes/tree/master/themes/yolngu) |
| `heritage-zalipie-sadza-dark` | Dark | [Zalipie](https://github.com/heritage-themes/heritage-themes/tree/master/themes/zalipie) |
| `heritage-zalipie-wapno-light` | Light | [Zalipie](https://github.com/heritage-themes/heritage-themes/tree/master/themes/zalipie) |
| `heritage-zlotnica-aksamit-dark` | Dark | [Złotnica](https://github.com/heritage-themes/heritage-themes/tree/master/themes/zlotnica) |
| `heritage-zlotnica-plotno-light` | Light | [Złotnica](https://github.com/heritage-themes/heritage-themes/tree/master/themes/zlotnica) |

Each flavor's folder has a `preview.png`. The flavors are tested with yazi 26.9.1.
