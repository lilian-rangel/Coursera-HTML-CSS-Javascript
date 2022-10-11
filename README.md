# Coursera-HTML-CSS-Javascript

***HTML***

(<): &lt ;
(>): &gt ;
(&): &amp ;
&nbsp: non-breaking space

<!-- comentário -->

***CSS***

Seletor de elemento
p {
  color:blue;
}

Seletor de classe <class="blue">
.blue {
  color: blue;
}

Seletor de id <id="name">
#name {
  color:blue
}

Agrupamento de seletores
div, .blue {
  color: blue;
}

Elemento com seletor de classe <p class="big">
p.big {
  font-size: 20px;
}
  
  Seletor filho (<article> <p> </p> </article>)
  article > p {
    color: blue;
 }
 ex2:
 article > .colored {
  color:blue;
}
  
 Seletor descendente (altera mesmo sem ser filho)
 article p {
  color: blue;
}
ex2: 
.colored p {
  color:blue;
}
  

Seletor pseudo-classe
:link
:visited
:hover
:active

ex: [a:link, a:visited {
display:flex;
text-decoration: none;
}
]
ex2: [a:hover, a:active {
background-color: black;
color: purple;
}
]

:nth-child(..)
ex: [header li:nth-child(3) {
font-size:24px;
}
]
ex2: [section div:nth-child(odd) {
background-color:gray;
}
]
ex3: [section div:nth-child(4):hover {
background-color: green;
cursor: pointer;
}
]

Specificity (score)
style='inline' > id > classe, pseudo-classe, atributo > seletor do elemento

