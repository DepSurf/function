# Function: <code>ip_encap</code>

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
In net/ipv4/ipmr.c (ffffffff817a96ef)
Location: net/ipv4/ipmr.c:1647
Inline: True
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
In net/ipv4/ipmr.c (ffffffff81816f2f)
Location: net/ipv4/ipmr.c:1633
Inline: True
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
In net/ipv4/ipmr.c (ffffffff8184874b)
Location: net/ipv4/ipmr.c:1638
Inline: True
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
In net/ipv4/ipmr.c (ffffffff81869db7)
Location: net/ipv4/ipmr.c:1686
Inline: True
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
In net/ipv4/ipmr.c (ffffffff818ea4f5)
Location: net/ipv4/ipmr.c:1821
Inline: True
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
In net/ipv4/ipmr.c (ffffffff81940b81)
Location: net/ipv4/ipmr.c:1750
Inline: True
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
In net/ipv4/ipmr.c (ffffffff81970b05)
Location: net/ipv4/ipmr.c:1761
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819da33b)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a111d9)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_encap(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b01500)
Location: net/ipv4/ipmr.c:1741
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff81b01500-ffffffff81b0163a: ip_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_encap(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0f5e0)
Location: net/ipv4/ipmr.c:1748
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff81b0f5e0-ffffffff81b0f71a: ip_encap (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffffffff81afe98d)
Location: net/ipv4/ipmr.c:1748
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bc01d2)
Location: net/ipv4/ipmr.c:1750
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_encap(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d52f40)
Location: net/ipv4/ipmr.c:1744
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff81d52f40-ffffffff81d530a1: ip_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_encap(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1d8e0)
Location: net/ipv4/ipmr.c:1759
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff81f1d8e0-ffffffff81f1da41: ip_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_encap(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7d3d0)
Location: net/ipv4/ipmr.c:1774
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff81f7d3d0-ffffffff81f7d531: ip_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_encap(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82043ad0)
Location: net/ipv4/ipmr.c:1773
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff82043ad0-ffffffff82043c31: ip_encap (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffff800010ccce7c)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd7690)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de8bb8)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/ipmr.c (ffffffe00081eeba)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b0b69)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196d199)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1b409)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a262e9)
Location: net/ipv4/ipmr.c:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
