# Function: <code>skb_partial_csum_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705a20)
Location: net/core/skbuff.c:3842
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:virtnet_receive
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81705a20-ffffffff81705ac3: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c6f0)
Location: net/core/skbuff.c:3883
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:virtnet_receive
  - net/packet/af_packet.c:packet_snd_vnet_gso
```
**Symbols:**

```
ffffffff8176c6f0-ffffffff8176c793: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817998c0)
Location: net/core/skbuff.c:3927
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff817998c0-ffffffff81799963: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8710)
Location: net/core/skbuff.c:4021
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff817b8710-ffffffff817b87b3: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818310a0)
Location: net/core/skbuff.c:4409
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff818310a0-ffffffff81831143: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4448
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8188346f-ffffffff81883494: skb_partial_csum_set.cold.85 (STB_LOCAL)
ffffffff8187b4b0-ffffffff8187b533: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c35f)
Location: net/core/skbuff.c:4468
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff818a3eb6-ffffffff818a3ee5: skb_partial_csum_set.cold.86 (STB_LOCAL)
ffffffff8189c2f0-ffffffff8189c375: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6bdd)
Location: net/core/skbuff.c:4653
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff818eecdb-ffffffff818eed0a: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff818e6b70-ffffffff818e6bf3: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81918d6d)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81920cb7-ffffffff81920ce6: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff81918d00-ffffffff81918d83: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4767
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff819f44fb-ffffffff819f452a: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff819e9df0-ffffffff819e9e73: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4834
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81c30494-ffffffff81c304c3: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff819e9b90-ffffffff819e9c13: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4922
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81c2276c-ffffffff81c2279c: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff819cfcd0-ffffffff819cfd53: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4990
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81d34bf4-ffffffff81d34c24: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff81a7f700-ffffffff81a7f783: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4904
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81f01109-ffffffff81f01137: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff81bf3b40-ffffffff81bf3bcd: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1860)
Location: net/core/skbuff.c:5106
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81da1860-ffffffff81da1914: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e100e0)
Location: net/core/skbuff.c:5304
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81e100e0-ffffffff81e1018f: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eccb90)
Location: net/core/skbuff.c:5435
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
**Symbols:**

```
ffffffff81eccb90-ffffffff81eccc3f: skb_partial_csum_set (STB_GLOBAL)
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
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1dc8)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffff800010bb1dc8-ffff800010bb1e80: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf728)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
c0ccf728-c0ccf7e8: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89680)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
c000000000c89680-c000000000c89794: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007443c0)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffe0007443c0-ffffffe000744466: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8d6d)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff818c0cb7-ffffffff818c0ce6: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff818b8d00-ffffffff818b8d83: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81872cbd)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8187abf7-ffffffff8187ac26: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff81872c50-ffffffff81872cd3: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81909d6d)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81911cb7-ffffffff81911ce6: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff81909d00-ffffffff81909d83: skb_partial_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool skb_partial_csum_set(struct sk_buff *skb, u16 start, u16 off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8192ae6d)
Location: net/core/skbuff.c:4665
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81932e17-ffffffff81932e46: skb_partial_csum_set.cold (STB_LOCAL)
ffffffff8192ae00-ffffffff8192ae83: skb_partial_csum_set (STB_GLOBAL)
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
