# Function: <code>ipmr_queue_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a9340)
Location: net/ipv4/ipmr.c:1692
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff817a9340-ffffffff817a9862: ipmr_queue_xmit.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81816b80)
Location: net/ipv4/ipmr.c:1676
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81816b80-ffffffff8181709e: ipmr_queue_xmit.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81848320)
Location: net/ipv4/ipmr.c:1681
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81848320-ffffffff818488ba: ipmr_queue_xmit.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81869a30)
Location: net/ipv4/ipmr.c:1729
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81869a30-ffffffff81869f88: ipmr_queue_xmit.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ea0c0)
Location: net/ipv4/ipmr.c:1886
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff818ea0c0-ffffffff818ea6ea: ipmr_queue_xmit.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81940760)
Location: net/ipv4/ipmr.c:1815
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81940760-ffffffff81940d72: ipmr_queue_xmit.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819705e0)
Location: net/ipv4/ipmr.c:1826
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff819705e0-ffffffff81970d6e: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819d9e70)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff819d9e70-ffffffff819da515: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a10d60)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81a10d60-ffffffff81a1139f: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b025a0)
Location: net/ipv4/ipmr.c:1806
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81b025a0-ffffffff81b02a46: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b10960)
Location: net/ipv4/ipmr.c:1813
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81b10960-ffffffff81b10e24: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afe570)
Location: net/ipv4/ipmr.c:1813
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81afe570-ffffffff81afebb9: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbfd60)
Location: net/ipv4/ipmr.c:1815
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81bbfd60-ffffffff81bc0484: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d54710)
Location: net/ipv4/ipmr.c:1809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81d54710-ffffffff81d54d27: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1e920)
Location: net/ipv4/ipmr.c:1824
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81f1e920-ffffffff81f1efd4: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7e420)
Location: net/ipv4/ipmr.c:1839
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81f7e420-ffffffff81f7ead4: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82044ae0)
Location: net/ipv4/ipmr.c:1837
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff82044ae0-ffffffff8204515b: ipmr_queue_xmit (STB_LOCAL)
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
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cccaf0)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffff800010cccaf0-ffff800010ccd004: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd70f4)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
c0dd70f4-c0dd781c: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de86f0)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
c000000000de86f0-c000000000de8d70: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081ebb0)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffe00081ebb0-ffffffe00081f034: ipmr_queue_xmit (STB_LOCAL)
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
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b06f0)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff819b06f0-ffffffff819b0d2f: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196cd20)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff8196cd20-ffffffff8196d35f: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1af90)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81a1af90-ffffffff81a1b5cf: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipmr_queue_xmit(struct net *net, struct mr_table *mrt, int in_vifi, struct sk_buff *skb, int vifi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a25e70)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff81a25e70-ffffffff81a264af: ipmr_queue_xmit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
