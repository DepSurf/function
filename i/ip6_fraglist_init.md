# Function: <code>ip6_fraglist_init</code>

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
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a020a0)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a020a0-ffffffff81a0221f: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a380b0)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a380b0-ffffffff81a3822f: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2d030)
Location: net/ipv6/ip6_output.c:600
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b2d030-ffffffff81b2d1b4: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3ba40)
Location: net/ipv6/ip6_output.c:637
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b3ba40-ffffffff81b3bbc4: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b29370)
Location: net/ipv6/ip6_output.c:668
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b29370-ffffffff81b294f7: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81beeda0)
Location: net/ipv6/ip6_output.c:649
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81beeda0-ffffffff81beef20: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d87460)
Location: net/ipv6/ip6_output.c:671
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81d87460-ffffffff81d875f0: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f550a0)
Location: net/ipv6/ip6_output.c:684
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81f550a0-ffffffff81f55230: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb4ab0)
Location: net/ipv6/ip6_output.c:685
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81fb4ab0-ffffffff81fb4c7c: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82082150)
Location: net/ipv6/ip6_output.c:695
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff82082150-ffffffff8208231c: ip6_fraglist_init (STB_GLOBAL)
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
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf8228)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffff800010cf8228-ffff800010cf83a4: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e01548)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c0e01548-c0e016ac: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e20170)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c000000000e20170-c000000000e20370: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe000844ad2)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffe000844ad2-ffffffe000844c24: ip6_fraglist_init (STB_GLOBAL)
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
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d7740)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff819d7740-ffffffff819d78bf: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994500)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81994500-ffffffff8199467f: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a421c0)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a421c0-ffffffff81a4233f: ip6_fraglist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_fraglist_init(struct sk_buff *skb, unsigned int hlen, u8 *prevhdr, u8 nexthdr, __be32 frag_id, struct ip6_fraglist_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4de50)
Location: net/ipv6/ip6_output.c:599
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a4de50-ffffffff81a4dfcf: ip6_fraglist_init (STB_GLOBAL)
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
