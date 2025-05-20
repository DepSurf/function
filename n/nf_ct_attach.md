# Function: <code>nf_ct_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81750f30)
Location: net/netfilter/core.c:365
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81750f30-ffffffff81750f51: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bcf60)
Location: net/netfilter/core.c:365
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff817bcf60-ffffffff817bcf81: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ec7f0)
Location: net/netfilter/core.c:374
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff817ec7f0-ffffffff817ec811: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180d0b0)
Location: net/netfilter/core.c:303
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8180d0b0-ffffffff8180d0d2: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c010)
Location: net/netfilter/core.c:530
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8188c010-ffffffff8188c035: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818dfde0)
Location: net/netfilter/core.c:580
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff818dfde0-ffffffff818dfe04: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c950)
Location: net/netfilter/core.c:580
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8190c950-ffffffff8190c974: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e490)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8196e490-ffffffff8196e4b5: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4ed0)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff819a4ed0-ffffffff819a4ef5: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8def0)
Location: net/netfilter/core.c:579
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81a8def0-ffffffff81a8df15: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97f00)
Location: net/netfilter/core.c:656
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81a97f00-ffffffff81a97f29: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a83250)
Location: net/netfilter/core.c:656
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81a83250-ffffffff81a83279: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3cf10)
Location: net/netfilter/core.c:657
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81b3cf10-ffffffff81b3cf39: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9400)
Location: net/netfilter/core.c:685
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81cc9400-ffffffff81cc9458: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e88fc0)
Location: net/netfilter/core.c:682
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81e88fc0-ffffffff81e89018: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee6f50)
Location: net/netfilter/core.c:694
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81ee6f50-ffffffff81ee6fa8: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faad60)
Location: net/netfilter/core.c:700
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81faad60-ffffffff81faadb8: nf_ct_attach (STB_GLOBAL)
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
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c54340)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffff800010c54340-ffff800010c5438c: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d6407c)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
c0d6407c-c0d640b8: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d54030)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
c000000000d54030-c000000000d54094: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007bea5e)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffe0007bea5e-ffffffe0007bea98: nf_ct_attach (STB_GLOBAL)
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
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944d40)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81944d40-ffffffff81944d65: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe830)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff818fe830-ffffffff818fe855: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995ed0)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81995ed0-ffffffff81995ef5: nf_ct_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_attach(struct sk_buff *new, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b9010)
Location: net/netfilter/core.c:559
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff819b9010-ffffffff819b9052: nf_ct_attach (STB_GLOBAL)
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
