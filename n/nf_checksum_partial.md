# Function: <code>nf_checksum_partial</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff818e1c90)
Location: net/netfilter/utils.c:29
Inline: True
```
**Symbols:**

```
ffffffff818e1c90-ffffffff818e1cd1: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff8190ea10)
Location: net/netfilter/utils.c:141
Inline: False
```
**Symbols:**

```
ffffffff8190ea10-ffffffff8190eb76: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819705d0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff819705d0-ffffffff81970746: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819a6fc0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff819a6fc0-ffffffff819a7136: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a90320)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81a90320-ffffffff81a90496: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a9a1f0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81a9a1f0-ffffffff81a9a366: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a854e0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81a854e0-ffffffff81a8565e: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81b3fbd0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81b3fbd0-ffffffff81b3fd4e: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81ccc3f0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81ccc3f0-ffffffff81ccc59f: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81e8c2f0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81e8c2f0-ffffffff81e8c49f: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81eea370)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81eea370-ffffffff81eea527: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81fae120)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81fae120-ffffffff81fae2d7: nf_checksum_partial (STB_GLOBAL)
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
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffff800010c56a20)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffff800010c56a20-ffff800010c56bd8: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c0d661dc)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
c0d661dc-c0d66354: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c000000000d57610)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
c000000000d57610-c000000000d57838: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffe0007c0a38)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffe0007c0a38-ffffffe0007c0b80: nf_checksum_partial (STB_GLOBAL)
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
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81946e30)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81946e30-ffffffff81946fa6: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81900920)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff81900920-ffffffff81900a96: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81997fc0)
Location: net/netfilter/utils.c:142
Inline: False
Direct callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
**Symbols:**

```
ffffffff81997fc0-ffffffff81998136: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__sum16 nf_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819baca0)
Location: net/netfilter/utils.c:142
Inline: False
```
**Symbols:**

```
ffffffff819baca0-ffffffff819bae16: nf_checksum_partial (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u_int8_t protocol</code> ➡️ <code>u8 protocol</code>
</li>
</ul>
</details>
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
