# Function: <code>validate_xmit_skb_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171cc00)
Location: net/core/dev.c:2813
Inline: False
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff8171cc00-ffffffff8171cc54: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81785380)
Location: net/core/dev.c:3012
Inline: False
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81785380-ffffffff817853e1: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b27a0)
Location: net/core/dev.c:3009
Inline: False
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff817b27a0-ffffffff817b2801: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cff90)
Location: net/core/dev.c:3089
Inline: False
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff817cff90-ffffffff817cfff1: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818498e0)
Location: net/core/dev.c:3116
Inline: False
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818498e0-ffffffff81849941: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893940)
Location: net/core/dev.c:3143
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81893940-ffffffff818939ab: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b4360)
Location: net/core/dev.c:3387
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff818b4360-ffffffff818b43cb: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81900c80)
Location: net/core/dev.c:3389
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81900c80-ffffffff81900ced: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932fb0)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81932fb0-ffffffff8193301d: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07de0)
Location: net/core/dev.c:3665
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81a07de0-ffffffff81a07e4d: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a094c0)
Location: net/core/dev.c:3695
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81a094c0-ffffffff81a0952d: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819efe30)
Location: net/core/dev.c:3774
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff819efe30-ffffffff819efe9d: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa1260)
Location: net/core/dev.c:3704
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81aa1260-ffffffff81aa12cd: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c191fb)
Location: net/core/dev.c:3710
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81c19130-ffffffff81c191a9: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dca1fb)
Location: net/core/dev.c:3697
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81dca120-ffffffff81dca199: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3ad7b)
Location: net/core/dev.c:3657
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81e3aca0-ffffffff81e3ad19: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef9111)
Location: net/core/dev.c:3667
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
Direct callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81ef9030-ffffffff81ef90a9: validate_xmit_skb_list (STB_GLOBAL)
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
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0fa0)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffff800010bd0fa0-ffff800010bd1020: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cebc04)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
c0cebc04-c0cebc80: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caf170)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
c000000000caf170-c000000000caf258: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b5b2)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffe00075b5b2-ffffffe00075b61a: validate_xmit_skb_list (STB_GLOBAL)
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
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d2fb0)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff818d2fb0-ffffffff818d301d: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ce40)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff8188ce40-ffffffff8188cead: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923fb0)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81923fb0-ffffffff8192401d: validate_xmit_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb_list(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81945420)
Location: net/core/dev.c:3307
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
**Symbols:**

```
ffffffff81945420-ffffffff8194548d: validate_xmit_skb_list (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *again</code>
</li>
</ul>
</details>
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
