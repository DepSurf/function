# Function: <code>pskb_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned char *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817059f0)
Location: net/core/skbuff.c:1406
Inline: False
```
**Symbols:**

```
ffffffff817059f0-ffffffff81705a19: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned char *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c6c0)
Location: net/core/skbuff.c:1411
Inline: False
```
**Symbols:**

```
ffffffff8176c6c0-ffffffff8176c6e9: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned char *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799890)
Location: net/core/skbuff.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81799890-ffffffff817998b9: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8870)
Location: net/core/skbuff.c:1424
Inline: False
```
**Symbols:**

```
ffffffff817b8870-ffffffff817b8899: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81831230)
Location: net/core/skbuff.c:1669
Inline: False
```
**Symbols:**

```
ffffffff81831230-ffffffff81831259: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187b6e0)
Location: net/core/skbuff.c:1671
Inline: False
```
**Symbols:**

```
ffffffff8187b6e0-ffffffff8187b709: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c510)
Location: net/core/skbuff.c:1681
Inline: False
```
**Symbols:**

```
ffffffff8189c510-ffffffff8189c533: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6d90)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffff818e6d90-ffffffff818e6db3: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919170)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffff81919170-ffffffff81919193: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1839
Inline: False
```
**Symbols:**

```
ffffffff819f4a44-ffffffff819f4a54: pskb_put.cold (STB_LOCAL)
ffffffff819ec770-ffffffff819ec7c1: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1850
Inline: False
```
**Symbols:**

```
ffffffff81c309bd-ffffffff81c309cd: pskb_put.cold (STB_LOCAL)
ffffffff819ec430-ffffffff819ec481: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1892
Inline: False
```
**Symbols:**

```
ffffffff81c22ca4-ffffffff81c22cbb: pskb_put.cold (STB_LOCAL)
ffffffff819d2930-ffffffff819d297b: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1964
Inline: False
```
**Symbols:**

```
ffffffff81d35184-ffffffff81d3519b: pskb_put.cold (STB_LOCAL)
ffffffff81a82580-ffffffff81a825cb: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1989
Inline: False
```
**Symbols:**

```
ffffffff81f016e1-ffffffff81f016f8: pskb_put.cold (STB_LOCAL)
ffffffff81bf6db0-ffffffff81bf6e17: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da5940)
Location: net/core/skbuff.c:2192
Inline: False
```
**Symbols:**

```
ffffffff81da5940-ffffffff81da59ba: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13f90)
Location: net/core/skbuff.c:2356
Inline: False
```
**Symbols:**

```
ffffffff81e13f90-ffffffff81e13ffd: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed1030)
Location: net/core/skbuff.c:2444
Inline: False
```
**Symbols:**

```
ffffffff81ed1030-ffffffff81ed109d: pskb_put (STB_GLOBAL)
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
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb21f0)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffff800010bb21f0-ffff800010bb2248: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf9bc)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
c0ccf9bc-c0ccfa04: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87e90)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
c000000000c87e90-c000000000c87ed0: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074392a)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffe00074392a-ffffffe00074397c: pskb_put (STB_GLOBAL)
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
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9170)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffff818b9170-ffffffff818b9193: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818730c0)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffff818730c0-ffffffff818730e3: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190a170)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffff8190a170-ffffffff8190a193: pskb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *pskb_put(struct sk_buff *skb, struct sk_buff *tail, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192b270)
Location: net/core/skbuff.c:1840
Inline: False
```
**Symbols:**

```
ffffffff8192b270-ffffffff8192b293: pskb_put (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
