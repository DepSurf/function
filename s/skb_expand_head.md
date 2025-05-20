# Function: <code>skb_expand_head</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_expand_head(struct sk_buff *skb, unsigned int headroom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1805
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81d35362-ffffffff81d35376: skb_expand_head.cold (STB_LOCAL)
ffffffff81a862b0-ffffffff81a8644e: skb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_expand_head(struct sk_buff *skb, unsigned int headroom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1830
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81f01886-ffffffff81f0189b: skb_expand_head.cold (STB_LOCAL)
ffffffff81bfb530-ffffffff81bfb6df: skb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_expand_head(struct sk_buff *skb, unsigned int headroom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2033
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff820aad56-ffffffff820aad6b: skb_expand_head.cold (STB_LOCAL)
ffffffff81daa6c0-ffffffff81daa86f: skb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_expand_head(struct sk_buff *skb, unsigned int headroom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2197
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff8212c343-ffffffff8212c358: skb_expand_head.cold (STB_LOCAL)
ffffffff81e1a110-ffffffff81e1a2bf: skb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_expand_head(struct sk_buff *skb, unsigned int headroom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2285
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff8220e019-ffffffff8220e02e: skb_expand_head.cold (STB_LOCAL)
ffffffff81ed76d0-ffffffff81ed787f: skb_expand_head (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
