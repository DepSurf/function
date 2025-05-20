# Function: <code>__skb_checksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817077e0)
Location: net/core/skbuff.c:2105
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_segment
```
**Symbols:**

```
ffffffff817077e0-ffffffff81707aa8: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176db80)
Location: net/core/skbuff.c:2103
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff8176db80-ffffffff8176de47: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179afe0)
Location: net/core/skbuff.c:2079
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff8179afe0-ffffffff8179b282: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7af0)
Location: net/core/skbuff.c:2093
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff817b7af0-ffffffff817b7dad: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830210)
Location: net/core/skbuff.c:2454
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81830210-ffffffff81830507: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a700)
Location: net/core/skbuff.c:2470
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff8187a700-ffffffff8187a9d3: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b310)
Location: net/core/skbuff.c:2466
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff8189b310-ffffffff8189b5da: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2626
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff818eeb85-ffffffff818eebdf: __skb_checksum.cold (STB_LOCAL)
ffffffff818e5e10-ffffffff818e60fc: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917f70)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff81917f70-ffffffff81918269: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb0e0)
Location: net/core/skbuff.c:2627
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff819eb0e0-ffffffff819eb3d9: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eae00)
Location: net/core/skbuff.c:2644
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff819eae00-ffffffff819eb0f9: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1330)
Location: net/core/skbuff.c:2727
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff819d1330-ffffffff819d160d: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80df0)
Location: net/core/skbuff.c:2799
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff81a80df0-ffffffff81a810cd: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf5890)
Location: net/core/skbuff.c:2848
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/dev.c:skb_crc32c_csum_help
```
**Symbols:**

```
ffffffff81bf5890-ffffffff81bf5ba3: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3ac0)
Location: net/core/skbuff.c:3054
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/dev.c:skb_crc32c_csum_help
```
**Symbols:**

```
ffffffff81da3ac0-ffffffff81da3dd3: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e12710)
Location: net/core/skbuff.c:3224
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/dev.c:skb_crc32c_csum_help
```
**Symbols:**

```
ffffffff81e12710-ffffffff81e12a47: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecf8d0)
Location: net/core/skbuff.c:3312
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/dev.c:skb_crc32c_csum_help
```
**Symbols:**

```
ffffffff81ecf8d0-ffffffff81ecfc07: __skb_checksum (STB_GLOBAL)
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
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0fe8)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffff800010bb0fe8-ffff800010bb1298: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccea34)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
c0ccea34-c0cced98: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c883a0)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
c000000000c883a0-c000000000c88790: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000742abc)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffe000742abc-ffffffe000742ce6: __skb_checksum (STB_GLOBAL)
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
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7f70)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff818b7f70-ffffffff818b8269: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871ec0)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff81871ec0-ffffffff818721b9: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908f70)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
**Symbols:**

```
ffffffff81908f70-ffffffff81909269: __skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__wsum __skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum, const struct skb_checksum_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192a020)
Location: net/core/skbuff.c:2628
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
**Symbols:**

```
ffffffff8192a020-ffffffff8192a337: __skb_checksum (STB_GLOBAL)
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
