# Заголовок 1
## Заголовок 2
### Заголовок 3
#### Заголовок4
##### Заголовок5
###### Заголовок 6

Заголовок 1
============

Заголовок 2
------------
  
Баскетбол
*Баскетбол*  
_Баскетбол_
**Баскетбол**  
__Баскетбол__
**Баскетбол и _Баскетбол_**
~~Баскетбол~~

-[] Шпаргалка по Markdown  
-[x] Шпаргалка по Markdown

1. Баскетбол
2. Баскетбол  
..* Баскетбол  
... Баскетбол  

  Баскетбол
  
[Баскетбол](https://www.Баскетбол)
`Баскетбол` b `Баскетбол`

```python
s = "Подсветка Python"
print s
```

| Баскетбол | Баскетбол |  Баскетбол| 
| --------- |:---------:| ---------:|
| *Баскетбол | `Баскетбол` | **Баскетбол** | 

> Баскетбол
> Баскетбол
>> Шпаргалка по Markdown
>>> Шпаргалка по Markdown

> БаскетболБаскетбол

---
***
___

Баскетбол  Баскетбол
Баскетбол
Баскетбол

Баскетбол

1. Шпаргалка по Markdown
	1. Шпаргалка по Markdown	
		1. Шпаргалка по Markdown
			1. Шпаргалка по Markdown  

. Шпаргалка по Markdown
	. Шпаргалка по Markdown
		. Шпаргалка по Markdown
		
		
- Шпаргалка по Markdown
	-[] Шпаргалка по Markdown
	-[x] Шпаргалка по Markdown

- Шпаргалка по Markdown:
	> Шпаргалка по Markdown
	
<https://.Шпаргалка.ru>


Шпаргалка по Markdown|Шпаргалка по Markdown|Шпаргалка по Markdown
:-|-|-:
Шпаргалка по Markdown   |    Шпаргалка по Markdown    |    Шпаргалка по Markdown    

`Шпаргалка по Markdown`

|| Шпаргалка по Markdown ||


```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```


```mermaid
sequenceDiagram
    participant user
    participant [example](example.com)
    participant iframe
    participant ![viewscreen](./.tiny-icon.png)
    user->>dotcom: Go to the [example](example.com) page
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```

```mermaid
  flowchart LR;
      A[CI MULTI CHAPTCHA]-->B{Select captcha service by developer?};
      classDef green color:#022e1f,fill:#00f500;
      classDef red color:#022e1f,fill:#f11111;
      classDef white color:#022e1f,fill:#fff;
      classDef black color:#fff,fill:#000;
      B--YES-->C[How to use?]:::green;
      
      C-->U[I choose recaptcha.]:::green;
      U--Views-->Q["echo CIMC_JS('recaptcha');\n echo CIMC_HTML(['captcha_name'=>'recaptcha']);"]:::green;
      U--Controller-->W["CIMC_RULE('recaptcha');"]:::green;
      
      C-->I[I choose arcaptcha.]:::white;
      I--Views-->O["echo CIMC_JS('arcaptcha');\n echo CIMC_HTML(['captcha_name'=>'arcaptcha']);"]:::white;
      I--Controller-->P["CIMC_RULE('arcaptcha');"]:::white;
      
      C-->X[I choose bibot.]:::red;
      X--Views-->V["echo CIMC_JS('bibot');\n echo CIMC_HTML(['captcha_name'=>'bibot']);"]:::red;
      X--Controller-->N["CIMC_RULE('bibot');"]:::red;
      
      B--NO-->D[How to use?]:::black;
      D---Views:::black-->F["echo CIMC_JS('randomcaptcha');\n echo CIMC_HTML(['captcha_name'=>'randomcaptcha']);"]:::black; 
      D---Controller:::black-->T["CIMC_RULE('archaptcha,recaptcha,bibot');"]:::black;
```

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```
