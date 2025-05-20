# Function: <code>virtio_net_hdr_to_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164daf4)
Location: include/linux/virtio_net.h:7
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81652f90)
Location: include/linux/virtio_net.h:7
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167f808)
Location: include/linux/virtio_net.h:7
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff818ae5a3)
Location: include/linux/virtio_net.h:7
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81694a68)
Location: include/linux/virtio_net.h:7
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff818d4f71)
Location: include/linux/virtio_net.h:7
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816feb52)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81959a00)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173e8c4)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff819afc39)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8176376a)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff819e7181)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817a1493)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a56544)
Location: include/linux/virtio_net.h:26
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
In drivers/net/tun.c (ffffffff817c6453)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a8da24)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8188ad70)
Location: include/linux/virtio_net.h:28
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81b86cc0)
Location: include/linux/virtio_net.h:28
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8188ad70-ffffffff8188afe5: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81b86cc0-ffffffff81b86f35: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81898e90)
Location: include/linux/virtio_net.h:28
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81b967a0)
Location: include/linux/virtio_net.h:28
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81898e90-ffffffff81899184: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81b967a0-ffffffff81b96a94: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8187c510)
Location: include/linux/virtio_net.h:28
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81b856c0)
Location: include/linux/virtio_net.h:28
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8187c510-ffffffff8187c8ec: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81b856c0-ffffffff81b85a9c: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8190dab0)
Location: include/linux/virtio_net.h:46
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81c51a30)
Location: include/linux/virtio_net.h:46
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8190dab0-ffffffff8190debd: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81c51a30-ffffffff81c51e3d: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81a634d0)
Location: include/linux/virtio_net.h:46
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81df3a40)
Location: include/linux/virtio_net.h:46
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81a634d0-ffffffff81a6392f: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81df3a40-ffffffff81df3e9f: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81bee9e0)
Location: include/linux/virtio_net.h:48
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81fc87b0)
Location: include/linux/virtio_net.h:48
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81bee9e0-ffffffff81beee6c: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81fc87b0-ffffffff81fc8c3c: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81c47750)
Location: include/linux/virtio_net.h:48
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4dff0)
Location: include/linux/virtio_net.h:48
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:receive_buf
```
```
In net/packet/af_packet.c (ffffffff82029110)
Location: include/linux/virtio_net.h:48
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81c47750-ffffffff81c47bde: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81c4dff0-ffffffff81c4e47e: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff82029110-ffffffff8202959e: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfd050)
Location: include/linux/virtio_net.h:50
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d04050)
Location: include/linux/virtio_net.h:50
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:receive_buf
```
```
In net/packet/af_packet.c (ffffffff820f8b50)
Location: include/linux/virtio_net.h:50
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81cfd050-ffffffff81cfd555: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff81d04050-ffffffff81d04555: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
ffffffff820f8b50-ffffffff820f9055: virtio_net_hdr_to_skb.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109e1564)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffff800010d59374)
Location: include/linux/virtio_net.h:26
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
In drivers/net/tun.c (c0ac66e8)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (c0e5af34)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (c000000000aa329c)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (c000000000e95250)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffe00062af36)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffe00088fe8a)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8178af33)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a2d0b4)
Location: include/linux/virtio_net.h:26
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
In drivers/net/tun.c (ffffffff8176a883)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff819ea2a4)
Location: include/linux/virtio_net.h:26
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
In drivers/net/tun.c (ffffffff817bb2d3)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a98c64)
Location: include/linux/virtio_net.h:26
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
In drivers/net/tun.c (ffffffff817d430e)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81aa52fe)
Location: include/linux/virtio_net.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
