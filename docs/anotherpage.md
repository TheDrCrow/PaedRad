# **Hello World**

## **Hello h2** 

### **Hello h3** 

#### Hello h4 

##### Hello h5 

###### Hello h6 

---

Paragraphs  
<code>Code</code>  
<text>Text</text>  

```
Code looks like this
```

|Table | Notes | More Notes|
|:---|:---|:---|
| 1 | some stuff | rubbish |

Referenced Stuff looks like this [^Smith2023]

[^Smith2023]: Smith AB et al. Blah in blah. J of Blah Stud. 123-145:4:2023. 

Links look like this: [DuckDuckGo](https://duckduckgo.org/)  
or [DuckDuckGo](https://duckduckgo.org/ "Search") with a nice hover title.

and images look like this: 

![Some alternative text for this child](paed_rad.png "Child Logo")

:fontawesome-regular-face-laugh-wink:

:fontawesome-solid-crow:

:smile:

---
### Diagrams 


``` mermaid
graph LR
  A[Square Bracket Box] --> B{Curly Braces Box};
  B -->|Between line comment| C( Parentheses Box );
  C --> D[Debug];
  D --> B;
  B ---->|Between line comment| E[Yay!];
```

##### Another Top to Bottom Graph.

```mermaid
graph TB
  A[Square Box A] --> B[Square Box B]
  A ---|No Arrow| C((Sphere C))
  A ==>|Thick Arrow| D([Lozenge])
```

##### And a lot more on the Mermaid JS website docs.
