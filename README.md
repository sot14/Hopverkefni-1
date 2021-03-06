# Hópverkefni 1

**Keyrsla verkefnis:**

Til þess að opna verkefnið þarf að fylgja eftirfarandi leiðbeiningum:

1. Fyrst þarf að hala niður git og node, en tenglar til að hala því niður eru látnar fylgja fyrir neðan. Passa þarf upp á að fylgja réttum leiðbeiningum fyrir stýrikerfið í þeirri tölvu sem notast er við.

2. Næst þarf á að klóna repositoryið, sem tengill hér að neðan vísar á, af github inn á local hjá notanda. Það er gert með því að fara upp í hægra hornið á upphafssíðunni á githup repository verkefnisins. Þar er grænn takki sem á stendur "clone or download". Þá kemur upp gluggi sem m.a. inniheldur link. Það þarf að copy-a þann link, en hann mun gera notandanum keift að opna þetta verkefni í sinni tölvu.

3. Síðan er farið í command line glugga og stimpla inn eftirfarandi skipanir

    - cd /
    - cd -*slóð á þann stað í tölvunni sem verkefnið á að vera í*-
    - npm install (setur upp node pakkastjórann í tölvunni)
    - git clone -*klónaður tengill á repositoryið*-
    - npm run dev (dev er skipun sem er búin að linka saman sass og browser-sync í pacagejson skránni)

Núna ætti síðan að vera búin að opnast á vefnum.

**Tenglar:**

- git download: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- node download: https://nodejs.org/en/download/current/
- github repo: https://github.com/sot14/Hopverkefni-1

**Uppsetning verkefnis:**

Verkefnið hefur þrjár möppur:
- img með öllum myndum verkefnisins
- pages með öllum síðum verkefnisins fyrir utan forsíðu
- scss með öllum scss skrám verkefnisins sem eru importaðar inn í styles.scss

Fyrir utan möppurnar eru mikilvægu skrárnar, þ.e. index.html og styles.scss sem er aðalskráin og importar allar scss skrárnar sem eru í verkefninu.

Við stílingu verkefnisins notuðum við class skilgreiningar og skilreindum litina inn í config skránni. Header og footer var stílaður í sérskrá sem er importuð á allar skrárnar og annað sameiginlegt útlit eins og letur er skilgreint beint inn í styles.scss.


**Upplýsingar um þá sem unnu verkefnið:**

- Jenný Hildur Ómarsdóttir - jho6@hi.is
- Sara Ósk Þorsteinsdóttir - sot14@hi.is
- Tómas Jónsson - toj6@hi.is
