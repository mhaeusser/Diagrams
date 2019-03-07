See https://support.typora.io/Draw-Diagrams-With-Markdown/ and https://mermaidjs.github.io/


Flow:

~~~flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
~~~
