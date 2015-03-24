# swarm-graphics
edit css: https://github.com/erosson/swarm-graphics/tree/gh-pages

view css: https://erosson.github.io/swarm-graphics/graphics.css

after v1.0.37, to use custom styling:
* with one click: [Standalone](https://swarmsim.github.io/#/cleartheme?themeExtra=@import url%28'https://test.swarmsim.com/swarm-graphics/graphics.css'%29;) , [Kongregate](https://www.swarmsim.com?kongregate=1/#/cleartheme?themeExtra=@import url%28'https://test.swarmsim.com/swarm-graphics/graphics.css'%29;)
* or options > theme > `Additional styling (advanced)` > paste `@import url('https://test.swarmsim.com/swarm-graphics/graphics.css');`

git will host your css files for free. steps:
* create github account
* create a repository
* switch to your repository's gh-pages branch: http://github.com/{{your-account-name}}/{{your-repository-name}}/tree/gh-pages
* edit and commit your css file there. the "+" at the top adds a file.
* go to http://{{your-account-name}}.github.io/{{your-repository-name}}/graphics.css

relevant css classes: `tab-icon-{{name}}`, `desc-icon-{{name}}`. use them with background-url to insert images into tabs or descriptions. There's also `icon-{{name}}`, which applies one image to both places. replace `{{name}}` with a unit name from the spreadsheet: https://docs.google.com/a/swarmsim.com/spreadsheets/d/1ughCy983eK-SPIcDYPsjOitVZzY10WdI2MGGrmxzxF4/pubhtml

Thanks for reading the docs. Your reward: Kittensim! [Standalone](https://swarmsim.github.io/#/cleartheme?themeExtra=@import url%28'https://test.swarmsim.com/swarm-graphics/kittens.css'%29;), [Kongregate](https://www.swarmsim.com?kongregate=1/#/cleartheme?themeExtra=@import url%28'https://test.swarmsim.com/swarm-graphics/kittens.css'%29;)
