# Function: <code>pskb_trim_rcsum_slow</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81882370)
Location: net/core/skbuff.c:1843
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff81882370-ffffffff81882433: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a2e40)
Location: net/core/skbuff.c:1853
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff818a2e40-ffffffff818a2f06: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818edac0)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff818edac0-ffffffff818edb86: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191fbc0)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff8191fbc0-ffffffff8191fc90: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f3170)
Location: net/core/skbuff.c:2011
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff819f3170-ffffffff819f3234: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f3150)
Location: net/core/skbuff.c:2022
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff819f3150-ffffffff819f3262: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d9390)
Location: net/core/skbuff.c:2064
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff819d9390-ffffffff819d94a2: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a89350)
Location: net/core/skbuff.c:2136
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff81a89350-ffffffff81a89462: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfe670)
Location: net/core/skbuff.c:2185
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81bfe670-ffffffff81bfe795: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dad070)
Location: net/core/skbuff.c:2388
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81dad070-ffffffff81dad195: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1cf70)
Location: net/core/skbuff.c:2552
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81e1cf70-ffffffff81e1d09f: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eda660)
Location: net/core/skbuff.c:2640
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81eda660-ffffffff81eda78f: pskb_trim_rcsum_slow (STB_GLOBAL)
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
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bba5e8)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffff800010bba5e8-ffff800010bba6d4: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd6dbc)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
c0cd6dbc-c0cd6ea8: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c93120)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
c000000000c93120-c000000000c93270: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074989e)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffe00074989e-ffffffe000749972: pskb_trim_rcsum_slow (STB_GLOBAL)
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
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bfbc0)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff818bfbc0-ffffffff818bfc90: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879b00)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff81879b00-ffffffff81879bd0: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81910bc0)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
**Symbols:**

```
ffffffff81910bc0-ffffffff81910c90: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81931d20)
Location: net/core/skbuff.c:2012
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff81931d20-ffffffff81931df0: pskb_trim_rcsum_slow (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
