# Function: <code>skb_flow_dissect_flow_keys_basic</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173f1a3)
Location: include/linux/skbuff.h:1210
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff8188a6a3)
Location: include/linux/skbuff.h:1210
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff818cb162)
Location: include/linux/skbuff.h:1210
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff819b085c)
Location: include/linux/skbuff.h:1210
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817639c5)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff818ab683)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff818f6302)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff819e8233)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817a1753)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff818f6f07)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81955965)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81a54d74)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c6713)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff81928c87)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff8198be05)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81a8b964)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188dffb)
Location: include/linux/skbuff.h:1315
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff819fcc07)
Location: include/linux/skbuff.h:1315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81a63895)
Location: include/linux/skbuff.h:1315
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81b85da3)
Location: include/linux/skbuff.h:1315
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189c517)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff819fc847)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81a6b9f5)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81b96373)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187ea7b)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff819e30b7)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81a54185)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81b852d3)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81910266)
Location: include/linux/skbuff.h:1352
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff81a93877)
Location: include/linux/skbuff.h:1352
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81b0ce95)
Location: include/linux/skbuff.h:1352
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81c515e3)
Location: include/linux/skbuff.h:1352
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a63d3d)
Location: include/linux/skbuff.h:1659
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff81c09ac6)
Location: include/linux/skbuff.h:1659
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81c937af)
Location: include/linux/skbuff.h:1659
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81df36ed)
Location: include/linux/skbuff.h:1659
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bf2eb9)
Location: include/linux/skbuff.h:1503
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff81db9836)
Location: include/linux/skbuff.h:1503
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81e4eecf)
Location: include/linux/skbuff.h:1503
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81fc84bd)
Location: include/linux/skbuff.h:1503
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c4a0a4)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4e0ec)
Location: include/linux/skbuff.h:1522
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81e29ee6)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81eaa56f)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff82028fdd)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cffa30)
Location: include/linux/skbuff.h:1529
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d04151)
Location: include/linux/skbuff.h:1529
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81ee7f56)
Location: include/linux/skbuff.h:1529
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff81f6d01f)
Location: include/linux/skbuff.h:1529
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff820f8a1d)
Location: include/linux/skbuff.h:1529
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109e16a0)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffff800010bc4ff4)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffff800010c36eb0)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffff800010d5a3b8)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac6954)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (c0ce0660)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (c0d4981c)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (c0e58ec8)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa35f0)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (c000000000c9f930)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (c000000000d2ef44)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (c000000000e947c0)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe00062b1bc)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffe0007519f4)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffe0007a8814)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffe000890218)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8178b1f3)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff818c8c87)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff8192bc75)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81a2aff4)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8176ab43)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff81882bc7)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff818e5a25)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff819e81e4)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817bb593)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff81919c87)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff8197ce05)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81a96ba4)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d45ce)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/flow_dissector.c (ffffffff8193aec7)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/ethernet/eth.c (ffffffff8199f375)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/packet/af_packet.c (ffffffff81aa381e)
Location: include/linux/skbuff.h:1309
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
