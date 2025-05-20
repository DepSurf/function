# Function: <code>skb_store_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817074f0)
Location: net/core/skbuff.c:2032
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff817074f0-ffffffff817077d4: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176d040)
Location: net/core/skbuff.c:2030
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8176d040-ffffffff8176d316: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a920)
Location: net/core/skbuff.c:2006
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8179a920-ffffffff8179abf0: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b82f0)
Location: net/core/skbuff.c:2020
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff817b82f0-ffffffff817b854f: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830d20)
Location: net/core/skbuff.c:2376
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81830d20-ffffffff81830f7d: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187b1f0)
Location: net/core/skbuff.c:2392
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff8187b1f0-ffffffff8187b444: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189bd40)
Location: net/core/skbuff.c:2388
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff8189bd40-ffffffff8189bf8b: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2548
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff818eec3d-ffffffff818eec7b: skb_store_bits.cold (STB_LOCAL)
ffffffff818e6630-ffffffff818e683a: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81918770)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81918770-ffffffff8191898d: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eae30)
Location: net/core/skbuff.c:2549
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819eae30-ffffffff819eb04b: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eab50)
Location: net/core/skbuff.c:2566
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819eab50-ffffffff819ead6b: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1110)
Location: net/core/skbuff.c:2649
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819d1110-ffffffff819d1321: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80b50)
Location: net/core/skbuff.c:2721
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81a80b50-ffffffff81a80d61: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf5650)
Location: net/core/skbuff.c:2770
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81bf5650-ffffffff81bf5889: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2ed0)
Location: net/core/skbuff.c:2976
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff81da2ed0-ffffffff81da30f3: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e11a90)
Location: net/core/skbuff.c:3146
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff81e11a90-ffffffff81e11cce: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecec50)
Location: net/core/skbuff.c:3234
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/xdp/xsk.c:xsk_build_skb
```
**Symbols:**

```
ffffffff81ecec50-ffffffff81ecee8e: skb_store_bits (STB_GLOBAL)
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
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1ae0)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffff800010bb1ae0-ffff800010bb1d08: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce670)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
c0cce670-c0cce968: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89150)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
c000000000c89150-c000000000c89470: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007427ee)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffe0007427ee-ffffffe0007429e4: skb_store_bits (STB_GLOBAL)
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
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8770)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff818b8770-ffffffff818b898d: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818726c0)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff818726c0-ffffffff818728dd: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81909770)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81909770-ffffffff8190998d: skb_store_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_store_bits(struct sk_buff *skb, int offset, const void *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192a860)
Location: net/core/skbuff.c:2550
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_store_bits
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8192a860-ffffffff8192aa90: skb_store_bits (STB_GLOBAL)
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
