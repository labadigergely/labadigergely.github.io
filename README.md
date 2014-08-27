## Labádi Gergely &lt;/filológia&gt;

Személyes honlap, amely saját tartalmakat és mások által gondozott tartalmakra mutató linkeket tartalmaz. Digitális és nem digitális bölcsészet… Szóval ahogy a honlapon áll.

A weboldal [Jekyll](http://jekyllrb.com) site-generátorral készült, ennek [Lanyon](#development) nevű témáját használva. 

## Hogyan készült?

Az időm legnagyobb részében régi szövegekkel foglalkozom. Kanyargós utakon jutottam el tehát – egyszer majd megírom, hogyan –  az egyszerűsített jelölőnyelvekig, mint a [`markdown`][markdown], illetve a szöveges fájlok konvertálását forradalmasító svájci bicskáig – ez volna a [`pandoc`][pandoc].

> Markdownból docx, epub, html, odt, pdf. Ésatöbbi. Aztán vissza. Sőt a `pandoc` maga is egy `markdown`-klón, de bővített jelölési képességekkel. Komolyan: lelkesítő. 

És akkor jött 2014, meg az ígéret, ez a `Flat-File CMS` éve [lesz](http://www.typeandgrids.com/blog/goodbye-wordpress-2014-will-be-the-year-of-flat-file-cmses). Persze ezek igazából nem CMS-ek, de a lényeg, hogy egy sima (rendszerint [markdown][markdown]) szövegfájlból automatikusan generálják az oldalakat. [Egyszerű és gyors](http://www.queness.com/post/16142/11-lightning-fast-flat-file-cms).

Egyszerű és gyors, ám van abban valami, hogy [megint elmarad a forradalom](https://www.ostraining.com/blog/general/2014-static-websites/), többet kipróbáltam: [phrozn][phrozn],[pico][pico]… Szóval érdemes megnézni a tutorialokat. Én végül a [jekyll][jekyll] mellett döntöttem, úgyhogy ezeket használtam

- a telepítéshez: [a jekyll dokumentációja][jekyll-doc], [segédlet az ubuntu 14.04-hez](http://michaelchelen.net/81fa/install-jekyll-2-ubuntu-14-04/),
- a felépítéshez, generáláshoz: ismét [a jekyll dokumentációja][jekyll-doc], valamint [a jekyll by example leírása](https://www.andrewmunsell.com/tutorials/jekyll-by-example), a kategóriák és a címkék elrendezését pedig [ez](http://stackoverflow.com/questions/8991995/using-liquid-to-sort-posts-alphabetically), illetve [emez](http://stackoverflow.com/questions/1408824/an-easy-way-to-support-tags-in-a-jekyll-blog/21002505#21002505) alapján készítettem,
- a dizájn pedig a [Lanyon](http://lanyon.getpoole.com/) nevű [jekyll][jekyll]-témát követi – és a `favicon` is ebből a projektből maradt a nevem mellett;
- a hosztolás alapvetően roppant egyszerű folyamatának megértéséhez [ez](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/).

Egy csomó mást meg nem, pedig bőszen túrtam értük a netet. Majd máskor.

[jekyll]: http://jekyllrb.com/
[jekyll-doc]: http://jekyllrb.com/docs/home/
[markdown]: http://daringfireball.net/projects/markdown/basics
[pandoc]: http://johnmacfarlane.net/pandoc/
[phrozn]: http://phrozn.info/
[pico]: http://picocms.org/


## Development

> Az eredeti Lanyon-Readme vége.

Lanyon has two branches, but only one is used for active development.

- `master` for development.  **All pull requests should be to submitted against `master`.**
- `gh-pages` for our hosted site, which includes our analytics tracking code. **Please avoid using this branch.**


## Author

> A Lanyon-téma szerzője.

**Mark Otto**
- <https://github.com/mdo>
- <https://twitter.com/mdo>


## License

> A Lanyon-téma jogi nyilatkozata.

Open sourced under the [MIT license](LICENSE.md).

<3
