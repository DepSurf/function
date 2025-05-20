# Function: <code>inet_frag_reasm_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff819cff75-ffffffff819cff88: inet_frag_reasm_prepare.cold (STB_LOCAL)
ffffffff819cf290-ffffffff819cf4fb: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a05e30)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81a05e30-ffffffff81a06085: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af5540)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81af5540-ffffffff81af579b: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b02300)
Location: net/ipv4/inet_fragment.c:439
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81b02300-ffffffff81b0255b: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aedc10)
Location: net/ipv4/inet_fragment.c:439
Inline: False
```
**Symbols:**

```
ffffffff81aedc10-ffffffff81aede65: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81badfc0)
Location: net/ipv4/inet_fragment.c:441
Inline: False
```
**Symbols:**

```
ffffffff81badfc0-ffffffff81bae215: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81d41100)
Location: net/ipv4/inet_fragment.c:441
Inline: False
```
**Symbols:**

```
ffffffff81d41100-ffffffff81d41381: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f09eb0)
Location: net/ipv4/inet_fragment.c:447
Inline: False
```
**Symbols:**

```
ffffffff81f09eb0-ffffffff81f0a131: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f699c0)
Location: net/ipv4/inet_fragment.c:447
Inline: False
```
**Symbols:**

```
ffffffff81f699c0-ffffffff81f69c6a: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff82030040)
Location: net/ipv4/inet_fragment.c:447
Inline: False
```
**Symbols:**

```
ffffffff82030040-ffffffff820302ea: inet_frag_reasm_prepare (STB_GLOBAL)
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
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbedb0)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffff800010cbedb0-ffff800010cbf058: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dca544)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
c0dca544-c0dca784: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dd9570)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
c000000000dd9570-c000000000dd9898: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe000814ba6)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffe000814ba6-ffffffe000814d8c: inet_frag_reasm_prepare (STB_GLOBAL)
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
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a5bd0)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff819a5bd0-ffffffff819a5e25: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8195f690)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff8195f690-ffffffff8195f8e5: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a10470)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
**Symbols:**

```
ffffffff81a10470-ffffffff81a106c5: inet_frag_reasm_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *inet_frag_reasm_prepare(struct inet_frag_queue *q, struct sk_buff *skb, struct sk_buff *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1acc0)
Location: net/ipv4/inet_fragment.c:408
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81a1acc0-ffffffff81a1af15: inet_frag_reasm_prepare (STB_GLOBAL)
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
