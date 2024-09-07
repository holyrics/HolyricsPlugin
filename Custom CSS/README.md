# Custom CSS

Repositório de modelos CSS para utilização no Holyrics Plugin

Para compartilhar um modelo de código, crie uma pasta com seu nome para sua própria administração e crie um arquivo `css` com uma respectiva imagem de exemplo `png` ou `jpg` com o mesmo nome do arquivo `css`;

Exemplo:

```
pasta/abc.css
pasta/abc.png
```

<hr>

# Exemplos

## William Gerrit

## box

![box](William%20Gerrit/box.png)<details>
  <summary>Ver CSS</summary>

```css
.text-custom span {
  background-color: rgba(0, 0, 0, 0.6);
  display: grid;
}
```
</details>

<hr>

## line

![line](William%20Gerrit/line.png)<details>
  <summary>Ver CSS</summary>

```css
.text-custom span{
  display: inline;
  background: black;
  box-shadow: 50px 0 0 black, -50px 0 0 black;
}

.bible-header-custom {
  margin: auto !important;
  margin-bottom: 0.2em !important;
  display: table !important;
}

#invisible .bible-header-custom {
  margin: auto !important;
  margin-bottom: 0.2em !important;
  display: table !important;
}
```
</details>

<hr>

## line_fill

![line_fill](William%20Gerrit/line_fill.png)<details>
  <summary>Ver CSS</summary>

```css
.text-custom span {
  display: unset;
  --bsc: black;
  background: var(--bsc);
  box-shadow: 10px 0 0 var(--bsc), -10px 0 0 var(--bsc), 20px 0 0 var(--bsc), -20px 0 0 var(--bsc), 40px 0 0 var(--bsc), -40px 0 0 var(--bsc), 60px 0 0 var(--bsc), -60px 0 0 var(--bsc), 80px 0 0 var(--bsc), -80px 0 0 var(--bsc), 100px 0 0 var(--bsc), -100px 0 0 var(--bsc), 120px 0 0 var(--bsc), -120px 0 0 var(--bsc), 140px 0 0 var(--bsc), -140px 0 0 var(--bsc), 160px 0 0 var(--bsc), -160px 0 0 var(--bsc), 180px 0 0 var(--bsc), -180px 0 0 var(--bsc), 200px 0 0 var(--bsc), -200px 0 0 var(--bsc), 220px 0 0 var(--bsc), -220px 0 0 var(--bsc), 240px 0 0 var(--bsc), -240px 0 0 var(--bsc), 260px 0 0 var(--bsc), -260px 0 0 var(--bsc), 280px 0 0 var(--bsc), -280px 0 0 var(--bsc), 300px 0 0 var(--bsc), -300px 0 0 var(--bsc), 320px 0 0 var(--bsc), -320px 0 0 var(--bsc), 340px 0 0 var(--bsc), -340px 0 0 var(--bsc), 360px 0 0 var(--bsc), -360px 0 0 var(--bsc), 380px 0 0 var(--bsc), -380px 0 0 var(--bsc), 400px 0 0 var(--bsc), -400px 0 0 var(--bsc), 420px 0 0 var(--bsc), -420px 0 0 var(--bsc), 440px 0 0 var(--bsc), -440px 0 0 var(--bsc), 460px 0 0 var(--bsc), -460px 0 0 var(--bsc), 480px 0 0 var(--bsc), -480px 0 0 var(--bsc), 500px 0 0 var(--bsc), -500px 0 0 var(--bsc), 520px 0 0 var(--bsc), -520px 0 0 var(--bsc), 540px 0 0 var(--bsc), -540px 0 0 var(--bsc), 560px 0 0 var(--bsc), -560px 0 0 var(--bsc), 580px 0 0 var(--bsc), -580px 0 0 var(--bsc), 600px 0 0 var(--bsc), -600px 0 0 var(--bsc), 620px 0 0 var(--bsc), -620px 0 0 var(--bsc), 640px 0 0 var(--bsc), -640px 0 0 var(--bsc), 660px 0 0 var(--bsc), -660px 0 0 var(--bsc), 680px 0 0 var(--bsc), -680px 0 0 var(--bsc), 700px 0 0 var(--bsc), -700px 0 0 var(--bsc), 720px 0 0 var(--bsc), -720px 0 0 var(--bsc), 740px 0 0 var(--bsc), -740px 0 0 var(--bsc), 760px 0 0 var(--bsc), -760px 0 0 var(--bsc), 780px 0 0 var(--bsc), -780px 0 0 var(--bsc), 800px 0 0 var(--bsc), -800px 0 0 var(--bsc), 820px 0 0 var(--bsc), -820px 0 0 var(--bsc), 840px 0 0 var(--bsc), -840px 0 0 var(--bsc), 860px 0 0 var(--bsc), -860px 0 0 var(--bsc), 880px 0 0 var(--bsc), -880px 0 0 var(--bsc), 900px 0 0 var(--bsc), -900px 0 0 var(--bsc), 920px 0 0 var(--bsc), -920px 0 0 var(--bsc), 940px 0 0 var(--bsc), -940px 0 0 var(--bsc), 960px 0 0 var(--bsc), -960px 0 0 var(--bsc), 980px 0 0 var(--bsc), -980px 0 0 var(--bsc), 1000px 0 0 var(--bsc), -1000px 0 0 var(--bsc), 1020px 0 0 var(--bsc), -1020px 0 0 var(--bsc), 1040px 0 0 var(--bsc), -1040px 0 0 var(--bsc), 1060px 0 0 var(--bsc), -1060px 0 0 var(--bsc), 1080px 0 0 var(--bsc), -1080px 0 0 var(--bsc), 1100px 0 0 var(--bsc), -1100px 0 0 var(--bsc), 1120px 0 0 var(--bsc), -1120px 0 0 var(--bsc), 1140px 0 0 var(--bsc), -1140px 0 0 var(--bsc), 1160px 0 0 var(--bsc), -1160px 0 0 var(--bsc), 1180px 0 0 var(--bsc), -1180px 0 0 var(--bsc), 1200px 0 0 var(--bsc), -1200px 0 0 var(--bsc), 1220px 0 0 var(--bsc), -1220px 0 0 var(--bsc), 1240px 0 0 var(--bsc), -1240px 0 0 var(--bsc), 1260px 0 0 var(--bsc), -1260px 0 0 var(--bsc), 1280px 0 0 var(--bsc), -1280px 0 0 var(--bsc) !important;
  line-height: 1.6em;
}

.bible-header-custom {
  margin: auto !important;
  margin-bottom: 0.2em !important;
  display: table !important;
}

#invisible .bible-header-custom {
  margin: auto !important;
  margin-bottom: 0.2em !important;
  display: table !important;
}
```
</details>

<hr>

## shadow

![shadow](William%20Gerrit/shadow.png)<details>
  <summary>Ver CSS</summary>

```css
span.header {
  display: block;
  margin-bottom: 10px;
  white-space: nowrap;
  font-size: 4px;
  width: 100%;
  margin: auto;
}

.text-custom {
  border: none;
  text-shadow: 2px 2px 30px rgba(0,0,0) ;
  -webkit-text-stroke-width: 0px;
  -webkit-text-stroke-color: black;
}

.bible-header-custom {
  font-size: 4px;
}
```
</details>

<hr>