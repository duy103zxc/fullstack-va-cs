Anki Card Template, keep it simple
### Front

```html
<div class="wrap">
    <header>
        {{#Focus}}
        <div class="tags">{{Focus}}</div>
        {{/Focus}} {{#Tags}}
        <div class="tags">{{Tags}}</div>
        {{/Tags}}
    </header>

    <div class="sent-center" id="tsc" visible="true">
        <div class="jpsentence" lang="ja">
            {{Sentence}}
        </div>
    </div>

</div>
```

### Back

```html
<div class="wrap">
    <div class="fside">{{FrontSide}}</div>

    <div class="sent-center">
        {{#SentenceTranslation}}
        <div class="ensentence" lang="en">{{SentenceTranslation}}</div>
        {{/SentenceTranslation}}
    </div>

    {{#WordMeaning}}
    <section class="headword_section">
        <div class="vocab">
            <span id="vocab-audio">{{WordAudio}}</span>
            <span id="sent-audio">{{SentenceAudio}}</span>
            <div class="target_word" lang="ja">{{furigana:WordFurigana}}</div>
        </div>
				
				<div class="target_word" lang="ja">「{{Word}}」</div>

        <div class="definitions">{{WordMeaning}}</div>
    </section>
    {{/WordMeaning}} 
    
    {{#Note}}
    <details open class="Note">
        <summary>Note</summary>
        <div>{{Note}}</div>
    </details>

    {{/Note}} {{#Image}}
    <details class="images-details">
				<summary>Image</summary>
        <div class="images">{{Image}}</div>
    </details>
    {{/Image}}
    <hr />
</div>
```

### CSS

```css
@charset "UTF-8";

@font-face {
    font-family: "Local Mincho";
    src: local("Yu Mincho"), local("Noto Serif CJK JP");
    font-weight: normal;
}

*,
*::before,
*::after {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

b,
strong {
    font-weight: 600;
}

.jpsentence b,
.jpsentence strong {
    color: #5586cd;
}

.card {
    background-color: #fffaf0;
    color: #2a1b0a;
    font-family: "Noto Serif", "Noto Serif CJK JP", Serif;
    font-size: 24px;
    text-align: left;
    line-height: 1.4;
    margin: 0 auto;
}



@media screen and (min-width: 820px) {
    .card {
        background-color: #e5d7c9;
        display: flex;
        justify-content: center;
    }

    .wrap {
        width: 800px;
        padding: 0 5px 0;
        background-color: #fffaf0;
        border-left: 1px solid #c9bcbc;
        border-right: 1px solid #c9bcbc;
        min-height: 100vh;
    }

    .wrap .wrap {
        width: auto;
        padding: 0;
        min-height: 0;
        border: 0;
    }
}

hr {
    margin: 8px 0;
    clear: both;
    border: 0;
    border-top: 1px solid #c9bcbc;
}


/* Top */
header {
    display: flex;
    clear: both;
    margin: 0 0 8px;
}

header .tags {
    border-radius: 0px 0px 3px 3px;
}

header > div:not(:last-child) {
    margin-right: 3px;
}

/* Space between elements */

.sent-center {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column nowrap;
}


/* Japanese sentence */

.jpsentence {
    font-size: 35px;
}

.jpsentence b {
    display: inline-block;
}

/* Definition */

.definitions,
.Note {
    font-weight: 300;
}


.tags {
    font-family: "Noto Sans", sans-serif;
    text-align: center;
    display: inline-block;
    text-transform: lowercase;
    background-color: #333;
    color: #fffaf0;
    font-weight: bold;
    padding: 1px 3px;
    margin: 0;
    cursor: pointer;
    border-radius: 3px;
    font-size: 12px;
    line-height: 14px;
    user-select: none;
}

/* AnkiDroid replay button */
/* a.replaybutton > span > svg */

.replaybutton {
    margin: 0;
    text-decoration: none;
}

.replaybutton span {
    padding: 0;
    font-size: 16px;
}

.replaybutton span svg {
    fill: #fffaf0;
    background: #333;
    border-radius: 3px;
    vertical-align: top;
    min-width: 16px;
    min-height: 16px;
}

/* PC replay button */
/* a.replay-button > svg */

a.replay-button {
    top: -0.125em;
    position: relative;
    margin: 0;
    user-select: none;
    cursor: pointer;
}

a.replay-button svg {
    height: 1em;
    width: 1em;
    user-select: none;
}

a.replay-button svg path {
    fill: #fffaf0;
}

a.replay-button svg circle {
    fill: #333;
}


/* Vocab */

.vocab {
    display: flex;
    flex-flow: row wrap;
    margin-top: 2px;
    align-items: center;
    gap: 5px;
}

.vocab > .target_word::before {
    content: "【";
}

.vocab > .target_word::after {
    content: "】";
}

.vocab div {
    display: inline-block;
}

.vocab br {
    display: none;
}

.vocab .tags {
    align-self: flex-start;
    vertical-align: top;
}

.Note .tags {
    vertical-align: bottom;
}

/* Images */

.images {
    margin: 10px 0;
    display: grid;
    justify-items: center;
    align-items: start;
    align-content: start;
    justify-content: space-around;
    gap: 5px;
    grid-auto-columns: minmax(100px, 1fr);
    grid-auto-rows: minmax(100px, auto);
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
}

.images br,

.images > :not(img) {
    display: none;
    visibility: hidden;
}
.images div {
    display: contents;
    visibility: visible;
}

.images img {
    display: block;
    border-radius: 4px;
    filter: sepia(33%);
    max-height: 95vh;
    width: 100%;
    object-fit: contain;
}

.images img:only-of-type {
    width: auto;
}

/* Images on front, toggled by JavaScript if "imageonfront" tag is set. */


/* Fix for Yomichan defs */

.headword_section ul,
.headword_section ol {
    list-style-type: none;
    display: inline;
    margin: 0px;
    padding: 0px;
}

/* Fix for Yomichan pitch accents */

.vocab ol > li {
    display: inline;
}

.vocab ol > li:after {
    content: "・";
}

.vocab ol > li:last-child:after {
    content: "";
}

/* Furigana style */

rt {
    color: black;
    line-height: 1;
}
.nightMode rt {
    color: white;
}


/* Details */

details,
.headword_section {
    background-color: hsl(0deg 80% 50% / 3%);
    border-radius: 4px;
    padding: 3px;
    margin-block-end: 0.4rem;
    border: 1px solid hsl(0deg 80% 50% / 15%);
}

summary {
    font-size: 18px;
    color: hsl(0 80% 10% / 70%);
    font-weight: 500;
    user-select: none;
}

/* Night Mode */

.nightMode.card {
    background-color: #2f2f31;
}

.nightMode .wrap {
    color: #ffffff;
    background-color: inherit;
    border-color: #6d6868;
}

.nightMode .tags {
    background-color: #ffffff;
    color: #2f2f31;
}

.nightMode a.replay-button svg path {
    fill: #2f2f31;
}

.nightMode a.replay-button svg circle {
    fill: #ffffff;
}

.nightMode .replaybutton span svg {
    fill: #2f2f31;
    background: #ffffff;
}

.nightMode .images > img {
    filter: sepia(0%);
}

.nightMode summary {
    color: hsl(0 80% 100% / 70%);
}
```



