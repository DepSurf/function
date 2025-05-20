# Function: <code>__skb_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705c80)
Location: net/core/skbuff.c:887
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:skb_clone
```
**Symbols:**

```
ffffffff81705c80-ffffffff81705dba: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c950)
Location: net/core/skbuff.c:892
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff8176c950-ffffffff8176ca8a: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799b20)
Location: net/core/skbuff.c:892
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81799b20-ffffffff81799c5a: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8fa0)
Location: net/core/skbuff.c:894
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff817b8fa0-ffffffff817b90da: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818319a0)
Location: net/core/skbuff.c:846
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff818319a0-ffffffff81831ada: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187be80)
Location: net/core/skbuff.c:846
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff8187be80-ffffffff8187bfcf: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c0e0)
Location: net/core/skbuff.c:848
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff8189c0e0-ffffffff8189c1ff: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6960)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff818e6960-ffffffff818e6a7c: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81918ab0)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81918ab0-ffffffff81918bcc: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819edb6a)
Location: net/core/skbuff.c:980
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_morph
Direct callers:
  - net/core/skbuff.c:skb_clone
```
**Symbols:**

```
ffffffff819ec9c0-ffffffff819ecadc: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed82a)
Location: net/core/skbuff.c:991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_morph
Direct callers:
  - net/core/skbuff.c:skb_clone
```
**Symbols:**

```
ffffffff819ec680-ffffffff819ec79c: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d538a)
Location: net/core/skbuff.c:1034
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_morph
Direct callers:
  - net/core/skbuff.c:skb_clone
```
**Symbols:**

```
ffffffff819d2b70-ffffffff819d2c8c: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a82760)
Location: net/core/skbuff.c:1054
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81a82760-ffffffff81a8288d: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf71b0)
Location: net/core/skbuff.c:1056
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81bf71b0-ffffffff81bf72ea: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da61d0)
Location: net/core/skbuff.c:1237
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81da61d0-ffffffff81da630a: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e152c0)
Location: net/core/skbuff.c:1377
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81e152c0-ffffffff81e153fa: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed2660)
Location: net/core/skbuff.c:1465
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81ed2660-ffffffff81ed279a: __skb_clone (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb71f8)
Location: net/core/skbuff.c:981
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd06ac)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
c0cd06ac-c0cd07b8: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87b50)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
c000000000c87b50-c000000000c87c98: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000746d70)
Location: net/core/skbuff.c:981
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8ab0)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff818b8ab0-ffffffff818b8bcc: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81872a00)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81872a00-ffffffff81872b1c: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81909ab0)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff81909ab0-ffffffff81909bcc: __skb_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__skb_clone(struct sk_buff *n, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192abb0)
Location: net/core/skbuff.c:981
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
```
**Symbols:**

```
ffffffff8192abb0-ffffffff8192accc: __skb_clone (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
