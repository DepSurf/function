# Function: <code>__skb_get_hash_symmetric</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8177a330)
Location: net/core/flow_dissector.c:656
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8177a330-ffffffff8177a5f7: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817a78e0)
Location: net/core/flow_dissector.c:761
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff817a78e0-ffffffff817a7bc4: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c5f10)
Location: net/core/flow_dissector.c:956
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff817c5f10-ffffffff817c61e5: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183fb10)
Location: net/core/flow_dissector.c:1155
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8183fb10-ffffffff8183fde8: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81889d90)
Location: net/core/flow_dissector.c:1210
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81889d90-ffffffff8188a049: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818aacd0)
Location: net/core/flow_dissector.c:1386
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff818aacd0-ffffffff818aaf77: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f6670)
Location: net/core/flow_dissector.c:1499
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff818f6670-ffffffff818f68f5: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81928670)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81928670-ffffffff81928820: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fc8a0)
Location: net/core/flow_dissector.c:1555
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff819fc8a0-ffffffff819fc967: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fc4e0)
Location: net/core/flow_dissector.c:1578
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff819fc4e0-ffffffff819fc5a7: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e2d60)
Location: net/core/flow_dissector.c:1604
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff819e2d60-ffffffff819e2e29: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a931c0)
Location: net/core/flow_dissector.c:1609
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81a931c0-ffffffff81a933a7: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c09340)
Location: net/core/flow_dissector.c:1663
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81c09340-ffffffff81c0956a: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db90d0)
Location: net/core/flow_dissector.c:1735
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81db90d0-ffffffff81db92dd: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e296e0)
Location: net/core/flow_dissector.c:1775
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81e296e0-ffffffff81e29924: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee7750)
Location: net/core/flow_dissector.c:1826
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81ee7750-ffffffff81ee7994: __skb_get_hash_symmetric (STB_GLOBAL)
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
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc48c0)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffff800010bc48c0-ffff800010bc4ab4: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0cdfef8)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
c0cdfef8-c0ce00e0: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9eed0)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
c000000000c9eed0-c000000000c9f1ac: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe000751442)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffe000751442-ffffffe0007515e2: __skb_get_hash_symmetric (STB_GLOBAL)
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
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c8670)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff818c8670-ffffffff818c8820: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818825b0)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff818825b0-ffffffff81882760: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81919670)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81919670-ffffffff81919820: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8193a8b0)
Location: net/core/flow_dissector.c:1536
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8193a8b0-ffffffff8193aa60: __skb_get_hash_symmetric (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
</li>
</ul>
</details>
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
