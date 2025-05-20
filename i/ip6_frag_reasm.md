# Function: <code>ip6_frag_reasm</code>

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
In net/ipv6/reassembly.c (ffffffff817ee39a)
Location: net/ipv6/reassembly.c:379
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8185cbd6)
Location: net/ipv6/reassembly.c:379
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8188eb17)
Location: net/ipv6/reassembly.c:383
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff818b4fcf)
Location: net/ipv6/reassembly.c:383
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81937d45)
Location: net/ipv6/reassembly.c:384
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81990c09)
Location: net/ipv6/reassembly.c:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff819c7344)
Location: net/ipv6/reassembly.c:279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81a35bd0)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a35bd0-ffffffff81a35efd: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81a6c6f0)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a6c6f0-ffffffff81a6ca1d: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81b658f0)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffffffff81b658f0-ffffffff81b65c1d: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81b74050)
Location: net/ipv6/reassembly.c:250
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffffffff81b74050-ffffffff81b7438b: ip6_frag_reasm (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81b62ab0)
Location: net/ipv6/reassembly.c:250
Inline: True
```
**Symbols:**

```
ffffffff81b62ab0-ffffffff81b62deb: ip6_frag_reasm.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81c2a540)
Location: net/ipv6/reassembly.c:250
Inline: True
```
**Symbols:**

```
ffffffff81c2a540-ffffffff81c2a894: ip6_frag_reasm.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81dc79f0)
Location: net/ipv6/reassembly.c:251
Inline: True
```
**Symbols:**

```
ffffffff81dc79f0-ffffffff81dc7d71: ip6_frag_reasm.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81f98760)
Location: net/ipv6/reassembly.c:256
Inline: True
```
**Symbols:**

```
ffffffff81f98760-ffffffff81f98ae1: ip6_frag_reasm.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81ff9140)
Location: net/ipv6/reassembly.c:256
Inline: True
```
**Symbols:**

```
ffffffff81ff9140-ffffffff81ff94c1: ip6_frag_reasm.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff820c6dc0)
Location: net/ipv6/reassembly.c:256
Inline: True
```
**Symbols:**

```
ffffffff820c6dc0-ffffffff820c713f: ip6_frag_reasm.constprop.0 (STB_LOCAL)
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
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffff800010d35118)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffff800010d35118-ffff800010d35430: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (c0e370a8)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
c0e370a8-c0e374f0: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (c000000000e66e80)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
c000000000e66e80-c000000000e672a0: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffe000872478)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffffffe000872478-ffffffe000872796: ip6_frag_reasm (STB_LOCAL)
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
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81a0bd80)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a0bd80-ffffffff81a0c0ad: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff819c8b40)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff819c8b40-ffffffff819c8e6d: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81a76800)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a76800-ffffffff81a76b2d: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_frag_reasm(struct frag_queue *fq, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81a82f30)
Location: net/ipv6/reassembly.c:248
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a82f30-ffffffff81a83275: ip6_frag_reasm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
