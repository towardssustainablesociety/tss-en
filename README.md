# Towards Sustainable Society (TSS) – English version

TSS is a knowledge site about a sustainable society: **a good life for all, within planetary boundaries**. It builds on the UN Sustainable Development Goals (Agenda 2030), the planetary boundaries and Doughnut Economics, and describes society as four societal systems – the ecological, the economic, the social and cultural, and the democratic – with people at the centre.

The site: <https://en.towardssustainablesociety.org> (Swedish original: <https://sv.towardssustainablesociety.org>, language choice: <https://www.towardssustainablesociety.org>)

## The English version and the Swedish original

- Swedish is the original language. The Swedish texts, the build script, the glossary and the management log are in [tss-sv](https://github.com/towardssustainablesociety/tss-sv). This repository only holds the English texts and images.
- The English site has the same pages, in the same order and folder structure, as the Swedish one. The page names follow the name table in `tss-sv/forvaltning/Ordlista svenska-engelska.md`, and the same glossary is used for all terms.
- Swedish examples are kept and framed ("In Sweden, …"). Sources that only exist in Swedish are marked "(in Swedish)".
- Changes are made in Swedish first and then carried over to English.

## Licence

The texts and images may be used under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). State that the material comes from TSS (*Towards Sustainable Society*, en.towardssustainablesociety.org), link to the licence, indicate any changes and share what you make on the same terms. The full licence text is in [LICENSE](LICENSE).

## What is here

| Folder | Contents |
|---|---|
| `texter/` | The pages in markdown, one folder per page. The file is named after the folder. Images lie in the page's folder. The Society Map is an SVG with links. |
| `texter/Sidordning.md` | All pages in the order they are shown. |
| `.github/workflows/publicera.yml` | Fetches the build script from tss-sv, builds the site and publishes it on GitHub Pages on every change in `main`. |

How a page is written and how the build works is described in the [README of tss-sv](https://github.com/towardssustainablesociety/tss-sv#readme). Build locally with the tss-sv repository next to this one:

```
python3 ../tss-sv/bygg/bygg.py texter _site --lang en --preview
```

## Suggest a change

Open an *issue* here, or write to towards.sustainable.life@gmail.com. State the page and, if possible, the source.
