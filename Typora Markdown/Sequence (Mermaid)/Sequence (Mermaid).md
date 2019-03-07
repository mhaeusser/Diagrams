See https://support.typora.io/Draw-Diagrams-With-Markdown/ and https://mermaidjs.github.io/


Mermaid/Sequence:

~~~mermaid
%% Example of sequence diagram
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
~~~
