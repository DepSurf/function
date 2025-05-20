# Function: <code>ip6_frag_queue</code>

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
In net/ipv6/reassembly.c (ffffffff817ede2e)
Location: net/ipv6/reassembly.c:209
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
In net/ipv6/reassembly.c (ffffffff8185c669)
Location: net/ipv6/reassembly.c:209
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
In net/ipv6/reassembly.c (ffffffff8188e579)
Location: net/ipv6/reassembly.c:209
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
In net/ipv6/reassembly.c (ffffffff818b4bc2)
Location: net/ipv6/reassembly.c:209
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
In net/ipv6/reassembly.c (ffffffff81937932)
Location: net/ipv6/reassembly.c:210
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
In net/ipv6/reassembly.c (ffffffff8199079b)
Location: net/ipv6/reassembly.c:165
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
In net/ipv6/reassembly.c (ffffffff819c6ee8)
Location: net/ipv6/reassembly.c:110
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff81a361ad)
Location: net/ipv6/reassembly.c:104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff81a6cccd)
Location: net/ipv6/reassembly.c:104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_frag_queue(struct frag_queue *fq, struct sk_buff *skb, struct frag_hdr *fhdr, int nhoff, u32 *prob_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81b65c20)
Location: net/ipv6/reassembly.c:104
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81b65c20-ffffffff81b660ac: ip6_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_frag_queue(struct frag_queue *fq, struct sk_buff *skb, struct frag_hdr *fhdr, int nhoff, u32 *prob_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81b74390)
Location: net/ipv6/reassembly.c:106
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81b74390-ffffffff81b74818: ip6_frag_queue (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81b62df0)
Location: net/ipv6/reassembly.c:106
Inline: True
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81b62df0-ffffffff81b63273: ip6_frag_queue.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81c2a8a0)
Location: net/ipv6/reassembly.c:106
Inline: True
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81c2a8a0-ffffffff81c2ad23: ip6_frag_queue.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81dc7d80)
Location: net/ipv6/reassembly.c:106
Inline: True
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81dc7d80-ffffffff81dc8218: ip6_frag_queue.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81f98b00)
Location: net/ipv6/reassembly.c:106
Inline: True
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81f98b00-ffffffff81f98f97: ip6_frag_queue.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81ff94e0)
Location: net/ipv6/reassembly.c:106
Inline: True
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81ff94e0-ffffffff81ff996d: ip6_frag_queue.constprop.0 (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff820c7150)
Location: net/ipv6/reassembly.c:106
Inline: True
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff820c7150-ffffffff820c75dd: ip6_frag_queue.constprop.0 (STB_LOCAL)
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
int ip6_frag_queue(struct frag_queue *fq, struct sk_buff *skb, struct frag_hdr *fhdr, int nhoff, u32 *prob_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffff800010d35430)
Location: net/ipv6/reassembly.c:104
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffff800010d35430-ffff800010d35838: ip6_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_frag_queue(struct frag_queue *fq, struct sk_buff *skb, struct frag_hdr *fhdr, int nhoff, u32 *prob_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (c0e374f0)
Location: net/ipv6/reassembly.c:104
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
c0e374f0-c0e37a3c: ip6_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_frag_queue(struct frag_queue *fq, struct sk_buff *skb, struct frag_hdr *fhdr, int nhoff, u32 *prob_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (c000000000e673c0)
Location: net/ipv6/reassembly.c:104
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
c000000000e673c0-c000000000e678f8: ip6_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_frag_queue(struct frag_queue *fq, struct sk_buff *skb, struct frag_hdr *fhdr, int nhoff, u32 *prob_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffe000872796)
Location: net/ipv6/reassembly.c:104
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffe000872796-ffffffe000872b3e: ip6_frag_queue (STB_LOCAL)
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
In net/ipv6/reassembly.c (ffffffff81a0c35d)
Location: net/ipv6/reassembly.c:104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff819c911d)
Location: net/ipv6/reassembly.c:104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff81a76ddd)
Location: net/ipv6/reassembly.c:104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff81a833fd)
Location: net/ipv6/reassembly.c:104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
</ul>
<b>Arch</b>
<ul>
</ul>
