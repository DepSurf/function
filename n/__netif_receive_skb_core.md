# Function: <code>__netif_receive_skb_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171a0b0)
Location: net/core/dev.c:3811
Inline: False
```
**Symbols:**

```
ffffffff8171a0b0-ffffffff8171ab0c: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81782590)
Location: net/core/dev.c:4080
Inline: False
```
**Symbols:**

```
ffffffff81782590-ffffffff81783012: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817afe80)
Location: net/core/dev.c:4080
Inline: False
```
**Symbols:**

```
ffffffff817afe80-ffffffff817b08bc: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce6c0)
Location: net/core/dev.c:4167
Inline: False
```
**Symbols:**

```
ffffffff817ce6c0-ffffffff817cf157: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847f40)
Location: net/core/dev.c:4368
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_core
```
**Symbols:**

```
ffffffff81847f40-ffffffff81848a80: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891f90)
Location: net/core/dev.c:4497
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_core
```
**Symbols:**

```
ffffffff81891f90-ffffffff81892add: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b5df0)
Location: net/core/dev.c:4816
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff818b5df0-ffffffff818b6a3e: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81901d90)
Location: net/core/dev.c:4811
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81901d90-ffffffff819029fc: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81933fd0)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81933fd0-ffffffff81934c3c: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff **pskb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a089c0)
Location: net/core/dev.c:5074
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81a089c0-ffffffff81a098d8: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff **pskb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09f70)
Location: net/core/dev.c:5123
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81a09f70-ffffffff81a0ae64: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819f0900)
Location: net/core/dev.c:5248
Inline: True
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff819f0900-ffffffff819f1825: __netif_receive_skb_core.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81aa2260)
Location: net/core/dev.c:5238
Inline: True
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81aa2260-ffffffff81aa3149: __netif_receive_skb_core.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81c1a580)
Location: net/core/dev.c:5273
Inline: True
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81c1a580-ffffffff81c1b427: __netif_receive_skb_core.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5264
Inline: True
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81dcb620-ffffffff81dcc387: __netif_receive_skb_core.constprop.0 (STB_LOCAL)
ffffffff820ab65b-ffffffff820ab674: __netif_receive_skb_core.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5240
Inline: True
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81e3c1b0-ffffffff81e3ceef: __netif_receive_skb_core.constprop.0 (STB_LOCAL)
ffffffff8212cdda-ffffffff8212cdf3: __netif_receive_skb_core.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81efa6d0)
Location: net/core/dev.c:5322
Inline: True
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81efa6d0-ffffffff81efb78a: __netif_receive_skb_core.constprop.0 (STB_LOCAL)
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
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd2340)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffff800010bd2340-ffff800010bd2e38: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cecedc)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
c0cecedc-c0cedb4c: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb0930)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
c000000000cb0930-c000000000cb17c8: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075c828)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffe00075c828-ffffffe00075d238: __netif_receive_skb_core (STB_LOCAL)
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
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d3fd0)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff818d3fd0-ffffffff818d4c3c: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188de60)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff8188de60-ffffffff8188eacc: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81924fd0)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff81924fd0-ffffffff81925c3c: __netif_receive_skb_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __netif_receive_skb_core(struct sk_buff *skb, bool pfmemalloc, struct packet_type **ppt_prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819464b0)
Location: net/core/dev.c:4713
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_one_core
```
**Symbols:**

```
ffffffff819464b0-ffffffff8194716f: __netif_receive_skb_core (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct packet_type **ppt_prev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff **pskb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sk_buff *skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
