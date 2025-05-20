# Function: <code>nf_checksum</code>

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
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u_int8_t protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff818e1c50)
Location: net/netfilter/utils.c:7
Inline: True
```
**Symbols:**

```
ffffffff818e1c50-ffffffff818e1c8f: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff8190e9e0)
Location: net/netfilter/utils.c:122
Inline: False
```
**Symbols:**

```
ffffffff8190e9e0-ffffffff8190ea0d: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819705a0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff819705a0-ffffffff819705cd: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819a6f90)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff819a6f90-ffffffff819a6fbd: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a902f0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81a902f0-ffffffff81a9031d: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a9a1c0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81a9a1c0-ffffffff81a9a1ed: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a854b0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81a854b0-ffffffff81a854dd: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81b3fba0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81b3fba0-ffffffff81b3fbcd: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81ccc3a0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81ccc3a0-ffffffff81ccc3eb: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81e8c290)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81e8c290-ffffffff81e8c2db: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81eea310)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81eea310-ffffffff81eea35b: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81fae0c0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81fae0c0-ffffffff81fae10b: nf_checksum (STB_GLOBAL)
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
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffff800010c56980)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffff800010c56980-ffff800010c56a1c: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c0d6619c)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
c0d6619c-c0d661dc: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c000000000d575c0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
c000000000d575c0-c000000000d57604: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffe0007c09cc)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffe0007c09cc-ffffffe0007c0a38: nf_checksum (STB_GLOBAL)
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
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81946e00)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff81946e00-ffffffff81946e2d: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819008f0)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff819008f0-ffffffff8190091d: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81997f90)
Location: net/netfilter/utils.c:123
Inline: False
Direct callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
**Symbols:**

```
ffffffff81997f90-ffffffff81997fbd: nf_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819bac70)
Location: net/netfilter/utils.c:123
Inline: False
```
**Symbols:**

```
ffffffff819bac70-ffffffff819bac9d: nf_checksum (STB_GLOBAL)
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
