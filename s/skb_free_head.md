# Function: <code>skb_free_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705f7f)
Location: net/core/skbuff.c:572
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:pskb_expand_head
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c100)
Location: net/core/skbuff.c:573
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff8176c100-ffffffff8176c12a: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817992e0)
Location: net/core/skbuff.c:573
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff817992e0-ffffffff8179930a: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7a60)
Location: net/core/skbuff.c:572
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff817b7a60-ffffffff817b7a8a: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830180)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81830180-ffffffff818301aa: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a660)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff8187a660-ffffffff8187a68a: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b240)
Location: net/core/skbuff.c:550
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff8189b240-ffffffff8189b267: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5ac0)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff818e5ac0-ffffffff818e5ae7: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917c10)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81917c10-ffffffff81917c37: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef6b2)
Location: net/core/skbuff.c:583
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef362)
Location: net/core/skbuff.c:597
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d513e)
Location: net/core/skbuff.c:644
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7fa50)
Location: net/core/skbuff.c:646
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81a7fa50-ffffffff81a7fac7: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3f10)
Location: net/core/skbuff.c:646
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81bf3f10-ffffffff81bf3f9a: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1c50)
Location: net/core/skbuff.c:813
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81da1c50-ffffffff81da1cda: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb, bool napi_safe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e118e0)
Location: net/core/skbuff.c:903
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81e118e0-ffffffff81e119a6: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb, bool napi_safe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed13c0)
Location: net/core/skbuff.c:989
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81ed13c0-ffffffff81ed1486: skb_free_head (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0f30)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffff800010bb0f30-ffff800010bb0f74: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce38c)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
c0cce38c-c0cce3c0: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87450)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
c000000000c87450-c000000000c874b8: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074207c)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffe00074207c-ffffffe0007420c2: skb_free_head (STB_LOCAL)
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
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7c10)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff818b7c10-ffffffff818b7c37: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871b60)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81871b60-ffffffff81871b87: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908c10)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81908c10-ffffffff81908c37: skb_free_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929cc0)
Location: net/core/skbuff.c:584
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
```
**Symbols:**

```
ffffffff81929cc0-ffffffff81929ce7: skb_free_head (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool napi_safe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
