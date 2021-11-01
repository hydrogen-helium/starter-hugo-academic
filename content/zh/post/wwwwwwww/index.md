---
title: 测试文章
subtitle: 测试文章
date: 2021-10-14T10:09:41.942Z
summary: 一个测试
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
# this is H1
## this is H2
### this is H3
#### this is H4
##### this is H5
###### this is H6

**这是加粗**
__这也是加粗__
*这是倾斜*
_这也是倾斜_
***这是加粗倾斜***
~~two tildes~~

### 分割线
* * *
***
**********
- - -
_________________

> 这是引用
> 这也是是引用

# 这是反斜杠
\> \* \_ \- 

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> > > > Back to the first level.

- 列表内容
+ 列表内容
* 列表内容

1. 列表内容
2. 列表内容
3. 列表内容

* 一级无序列表内容
   * 二级无序列表内容
   * 二级无序列表内容
   * 二级无序列表内容

*   况吾与子渔樵于江渚之上，侣鱼虾而友麋鹿，驾一叶之扁舟，举匏樽以相属。寄蜉蝣于天地，渺沧海之一粟。
    哀吾生之须臾，羡长江之无穷。挟飞仙以遨游，抱明月而长终。知不可乎骤得，托遗响于悲风。
*   逝者如斯，而未尝往也；盈虚者如彼，而卒莫消长也。盖将自其变者而观之，则天地曾不能以一瞬；
    自其不变者而观之，则物与我皆无尽也，而又何羡乎!且夫天地之间，物各有主,苟非吾之所有，虽一毫而莫取。
    惟江上之清风，与山间之明月，耳得之而为声，目遇之而成色，取之无禁，用之不竭，是造物者之无尽藏也，而吾与子之所共适。

![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/
u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

[百度](http://baidu.com)

表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

这是 {{< hl >}}高亮{{< /hl >}}.

  `代码内容`

(```)
  代码...
  代码...
  代码...
(```)

1. First item
   1. A sub-item
2. Another item

- First item
  - A sub-item
- Another item

- [x] Write math example
  - [x] Write diagram example
- [ ] Do something else

I have more [^1] to say.

[^1]: Footnote example.

gallery_item:
- album: <ALBUM FOLDER>
  image: <IMAGE 1 NAME>.jpg
  caption: Write your image 1 caption here
- album: <ALBUM FOLDER>
  image: <IMAGE 2 NAME>.jpg
  caption: Write your image 2 caption here

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
  Alice->John: Hello John, how are you?
  loop Healthcheck
      John->John: Fight against hypochondria
  end
  Note right of John: Rational thoughts <br/>prevail...
  John-->Alice: Great!
  John->Bob: How about you?
  Bob-->John: Jolly good!
```

```mermaid
gantt
  dateFormat  YYYY-MM-DD
  section Section
  A task           :a1, 2014-01-01, 30d
  Another task     :after a1  , 20d
  section Another
  Task in sec      :2014-01-12  , 12d
  another task      : 24d
```

```python
# Example of code highlighting
input_string_var = input("Enter some data: ")
print("You entered: {}".format(input_string_var))
```
$$\gamma_{n} = \frac{ 
\left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T 
\left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}
{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$

$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\\\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$

{{% callout note %}}
A Markdown callout is useful for displaying notices, hints, or definitions to your readers.
{{% /callout %}}

{{% callout warning %}}
Here's some important information...
{{% /callout %}}

{{< audio src="markvard.mp3" >}}

I : heart : Wowchemy : smile :

{{< icon name="terminal" pack="fas" >}} Terminal  
{{< icon name="python" pack="fab" >}} Python  
{{< icon name="r-project" pack="fab" >}} R

{{< cta cta_text="Do something" cta_link="/" cta_new_tab="false" >}}

{{< cite page="/publication/preprint" view="4" >}}

{{< spoiler text="Click to view the spoiler" >}}
You found me!
{{< /spoiler >}}

{{% staticref "uploads/cv.pdf" "newtab" %}}Download my CV{{% /staticref %}}
 


