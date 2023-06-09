---
title: "Test"
categories: [Tests Parent, Tests Child]
tags: [tests] # TAG names should always be lowercase
mermaid: true
math: true
comments: true
toc: true
pin: false
---

## Section

### Subsection

#### Sub-subsection


## Page config

```yaml
---
title: "Test"
categories: [test1, test2]
tags: [tests] # TAG names should always be lowercase
mermaid: true
math: true
comments: true
toc: true
pin: false
---
```

Refer for [this page](https://chirpy.cotes.page/posts/write-a-new-post/) for more stuff.

## Stuff

> An example showing the `info` type prompt.
{: .prompt-info }

> An example showing the `danger` type prompt.
{: .prompt-danger }

> An example showing the `warning` type prompt.
{: .prompt-warning }

> An example showing the `tip` type prompt.
{: .prompt-tip }

`/path/to/a/file.extend`{: .filepath}


```python
import numpy as np
x = np.zeros((2,2))
print(x)
```

```
[[0. 0.]
 [0. 0.]]
```
{: .nolineno }

```diff
import numpy as np
- x = np.zeros((2,2))
+ x = np.ones((2,2))
print(x)
```

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

```mermaid
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch newbranch
checkout newbranch
commit
commit
checkout master
commit
commit
merge newbranch
```
{: w="200" h="200" }
