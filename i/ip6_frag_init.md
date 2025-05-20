# Function: <code>ip6_frag_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_frag_init(struct inet_frag_queue *q, const void *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff817ed900)
Location: net/ipv6/reassembly.c:118
Inline: False
```
**Symbols:**

```
ffffffff817ed900-ffffffff817ed958: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_frag_init(struct inet_frag_queue *q, const void *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8185c140)
Location: net/ipv6/reassembly.c:118
Inline: False
```
**Symbols:**

```
ffffffff8185c140-ffffffff8185c198: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_frag_init(struct inet_frag_queue *q, const void *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8188e050)
Location: net/ipv6/reassembly.c:118
Inline: False
```
**Symbols:**

```
ffffffff8188e050-ffffffff8188e0a8: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_frag_init(struct inet_frag_queue *q, const void *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff818b46f0)
Location: net/ipv6/reassembly.c:118
Inline: False
```
**Symbols:**

```
ffffffff818b46f0-ffffffff818b474c: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_frag_init(struct inet_frag_queue *q, const void *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81937460)
Location: net/ipv6/reassembly.c:118
Inline: False
```
**Symbols:**

```
ffffffff81937460-ffffffff819374bc: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_frag_init(struct inet_frag_queue *q, const void *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81990220)
Location: net/ipv6/reassembly.c:75
Inline: False
```
**Symbols:**

```
ffffffff81990220-ffffffff8199025f: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a03e15)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a004e0-ffffffff81a00524: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3a9f8)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a370b0-ffffffff81a370f4: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2ffb7)
Location: net/ipv6/ip6_output.c:666
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b2c330-ffffffff81b2c374: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3ea57)
Location: net/ipv6/ip6_output.c:703
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b3ad50-ffffffff81b3ad94: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2b81c)
Location: net/ipv6/ip6_output.c:734
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b28a10-ffffffff81b28a54: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bf18c2)
Location: net/ipv6/ip6_output.c:715
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81beea10-ffffffff81beea54: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d8a2d4)
Location: net/ipv6/ip6_output.c:737
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81d86fa0-ffffffff81d86ff8: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f58264)
Location: net/ipv6/ip6_output.c:750
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81f54bb0-ffffffff81f54c08: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb7e4f)
Location: net/ipv6/ip6_output.c:751
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81fb45c0-ffffffff81fb4618: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82085489)
Location: net/ipv6/ip6_output.c:761
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff82081e70-ffffffff82081ec8: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfbb44)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffff800010cf80c8-ffff800010cf8150: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e02b6c)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c0dfe41c-c0dfe478: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e231e0)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c000000000e1e9d0-c000000000e1ea14: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe00084643c)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffe0008430c4-ffffffe000843144: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819da088)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff819d6740-ffffffff819d6784: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81996e48)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81993500-ffffffff81993544: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a44b08)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a411c0-ffffffff81a41204: ip6_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ip6_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int mtu, short unsigned int needed_tailroom, int hdr_room, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a507c8)
Location: net/ipv6/ip6_output.c:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a4cdb0-ffffffff81a4cdf4: ip6_frag_init (STB_GLOBAL)
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
