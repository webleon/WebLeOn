# Markdown Plus

![Markdown Plus](icon.png)
Markdown Plus ("M+" or "mdp" for short) is a versatile markdown editor. Besides common markdown, GitHub flavored markdown, it also supports task lists, emojis, Font Awesome icons, Ionicons icons, mathematical formulae, flowcharts, sequence diagrams, gantt diagrams, Vim mode and Emacs mode.


##### Fork me on GitHub: <i class="fa fa-github" style="font-size: 64px;"/> [tylingsoft/markdown-plus](https://github.com/tylingsoft/markdown-plus).

##### Buy our Mac app: <i class="fa fa-apple" style="font-size: 64px;"/> [tylingsoft.com/mdp](https://tylingsoft.com/mdp)

---


## Code blocks with syntax highlight

    <?php
        echo "Hello world!";

```python
from fabric.api import local

def update():
    local('rm -rf bower_components')
    local('bower cache clean')
    local('bower update')
```


## Tables and alignment

Function name | Description
------------- | -----------
`help()`      | Display the help window.
`destroy()`   | **Destroy your computer!**

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |


## Task lists

- [ ] a bigger project
  - [x] first subtask
  - [x] follow up subtask
  - [ ] final subtask
- [ ] a separate task

[Task Lists Syntax](https://help.github.com/articles/writing-on-github/#task-lists)


## Emojis

<img src="https://s.tylingsoft.com/emoji-icons/smile.png" width="64"/>
<img src="https://s.tylingsoft.com/emoji-icons/whale.png" width="64"/>
<img src="https://s.tylingsoft.com/emoji-icons/santa.png" width="64"/>
<img src="https://s.tylingsoft.com/emoji-icons/panda_face.png" width="64"/>
<img src="https://s.tylingsoft.com/emoji-icons/dog.png" width="64"/>
<img src="https://s.tylingsoft.com/emoji-icons/truck.png" width="64"/>

[Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/)


## Font Awesome icons

<i class="fa fa-cloud" style="font-size: 64px;"/>
<i class="fa fa-flag" style="font-size: 64px;"/>
<i class="fa fa-car" style="font-size: 64px;"/>
<i class="fa fa-truck" style="font-size: 64px;"/>
<i class="fa fa-heart" style="font-size: 64px;"/>
<i class="fa fa-dollar" style="font-size: 64px;"/>

[All the Font Awesome icons](http://fontawesome.io/icons/)


## Ionicons icons

<i class="icon ion-beer" style="font-size: 88px;"/>
<i class="icon ion-key" style="font-size: 88px;"/>
<i class="icon ion-locked" style="font-size: 88px;"/>
<i class="icon ion-location" style="font-size: 88px;"/>
<i class="icon ion-plane" style="font-size: 88px;"/>
<i class="icon ion-ios-eye" style="font-size: 88px;"/>

[All the Ionicons icons](http://ionicons.com/)




## Flowcharts

```
graph TD
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```

[Flowchart Syntax](http://knsv.github.io/mermaid/flowchart.html)


## Sequence diagrams

```
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you?
    alt is sick
        Bob->>Alice: Not so good :(
    else is well
        Bob->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        Bob->>Alice: Thanks for asking
    end
```

[Sequence Diagram Syntax](http://knsv.github.io/mermaid/sequenceDiagram.html)


## Gantt diagrams

```
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1, 20d
    section Another
    Task in sec      :2014-01-12, 12d
    anther task      : 24d
```

[Gantt Diagram Syntax](http://knsv.github.io/mermaid/gantt.html)
