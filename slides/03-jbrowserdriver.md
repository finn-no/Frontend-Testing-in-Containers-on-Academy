# JBrowserDriver

Note:
Som et alternativ til PhantomJS, har vi sett på JBrowserDriver som er en ren Java-løsning der en kjører opp WebKit-en som er bundlet med JavaFX og styrer denne. Det prosjektet er ganske aktivt så hadde vært en god løsning. Grunnen til at vi ikke har byttet, er at det er en del "features" eller bugs i PhantomJS som vi har skrevet oss rundt i testene våre som krasjer i JBrowserDriver.

En annen ting er så klart at dette ikke løser at man skal kjøre en browser som folk bruker.
