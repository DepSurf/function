# Function: <code>skb_copy_and_csum_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81707b80)
Location: net/core/skbuff.c:2190
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_segment
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81707b80-ffffffff81707ea3: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176d790)
Location: net/core/skbuff.c:2188
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8176d790-ffffffff8176da97: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179abf0)
Location: net/core/skbuff.c:2164
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8179abf0-ffffffff8179aef1: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8010)
Location: net/core/skbuff.c:2178
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff817b8010-ffffffff817b82e1: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830a50)
Location: net/core/skbuff.c:2546
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81830a50-ffffffff81830d20: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187af20)
Location: net/core/skbuff.c:2562
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8187af20-ffffffff8187b1e3: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b8c0)
Location: net/core/skbuff.c:2558
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8189b8c0-ffffffff8189bb7a: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2724
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff818eebdf-ffffffff818eec3d: skb_copy_and_csum_bits.cold (STB_LOCAL)
ffffffff818e61e0-ffffffff818e6469: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81918350)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81918350-ffffffff819185a8: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eab00)
Location: net/core/skbuff.c:2725
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff819eab00-ffffffff819ead5b: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea840)
Location: net/core/skbuff.c:2742
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff819ea840-ffffffff819eaa8d: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0e10)
Location: net/core/skbuff.c:2825
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff819d0e10-ffffffff819d1043: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80850)
Location: net/core/skbuff.c:2897
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81a80850-ffffffff81a80a83: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf52e0)
Location: net/core/skbuff.c:2946
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81bf52e0-ffffffff81bf5574: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3810)
Location: net/core/skbuff.c:3152
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81da3810-ffffffff81da3aa4: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e12410)
Location: net/core/skbuff.c:3322
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81e12410-ffffffff81e126fe: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecf5d0)
Location: net/core/skbuff.c:3410
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81ecf5d0-ffffffff81ecf8be: skb_copy_and_csum_bits (STB_GLOBAL)
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
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1660)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffff800010bb1660-ffff800010bb18f4: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf0ec)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
c0ccf0ec-c0ccf47c: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c88b50)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
c000000000c88b50-c000000000c88f0c: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000742fee)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffe000742fee-ffffffe000743230: skb_copy_and_csum_bits (STB_GLOBAL)
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
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8350)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff818b8350-ffffffff818b85a8: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818722a0)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff818722a0-ffffffff818724f8: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81909350)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff81909350-ffffffff819095a8: skb_copy_and_csum_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff *skb, int offset, u8 *to, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192a420)
Location: net/core/skbuff.c:2726
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv6/icmp.c:icmpv6_getfrag
```
**Symbols:**

```
ffffffff8192a420-ffffffff8192a691: skb_copy_and_csum_bits (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__wsum csum</code>
</li>
</ul>
</details>
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
