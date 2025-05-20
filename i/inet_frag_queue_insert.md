# Function: <code>inet_frag_queue_insert</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819cf5a0)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff819cf5a0-ffffffff819cf70c: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a06130)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a06130-ffffffff81a0629c: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af5880)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffffffff81af5880-ffffffff81af59ed: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b026e0)
Location: net/ipv4/inet_fragment.c:375
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffffffff81b026e0-ffffffff81b0284d: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aedff0)
Location: net/ipv4/inet_fragment.c:375
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81aedff0-ffffffff81aee157: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81bae3a0)
Location: net/ipv4/inet_fragment.c:377
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81bae3a0-ffffffff81bae507: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81d41570)
Location: net/ipv4/inet_fragment.c:377
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81d41570-ffffffff81d416f9: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f0a360)
Location: net/ipv4/inet_fragment.c:383
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81f0a360-ffffffff81f0a4e9: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f69e90)
Location: net/ipv4/inet_fragment.c:383
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81f69e90-ffffffff81f6a019: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff82030540)
Location: net/ipv4/inet_fragment.c:383
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff82030540-ffffffff820306c9: inet_frag_queue_insert (STB_GLOBAL)
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
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbe7f0)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffff800010cbe7f0-ffff800010cbe960: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dca784)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
c0dca784-c0dca900: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dd99a0)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
c000000000dd99a0-c000000000dd9bac: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe000814e1a)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
**Symbols:**

```
ffffffe000814e1a-ffffffe000814f48: inet_frag_queue_insert (STB_GLOBAL)
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
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a5ed0)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff819a5ed0-ffffffff819a603c: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8195f990)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8195f990-ffffffff8195fafc: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a10770)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
**Symbols:**

```
ffffffff81a10770-ffffffff81a108dc: inet_frag_queue_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_frag_queue_insert(struct inet_frag_queue *q, struct sk_buff *skb, int offset, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1afc0)
Location: net/ipv4/inet_fragment.c:344
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a1afc0-ffffffff81a1b12c: inet_frag_queue_insert (STB_GLOBAL)
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
