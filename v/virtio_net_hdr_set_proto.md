# Function: <code>virtio_net_hdr_set_proto</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8176394b)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff819e81be)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817a16ce)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a54d02)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817c668e)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a8b8f2)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8188afab)
Location: include/linux/virtio_net.h:10
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8741f)
Location: include/linux/virtio_net.h:10
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff818990fc)
Location: include/linux/virtio_net.h:10
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b96f71)
Location: include/linux/virtio_net.h:10
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8187c832)
Location: include/linux/virtio_net.h:10
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b85f76)
Location: include/linux/virtio_net.h:10
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8190de38)
Location: include/linux/virtio_net.h:25
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52318)
Location: include/linux/virtio_net.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff81a638a2)
Location: include/linux/virtio_net.h:25
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df44fc)
Location: include/linux/virtio_net.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff81beedee)
Location: include/linux/virtio_net.h:26
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc92e0)
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c47b43)
Location: include/linux/virtio_net.h:26
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4e3e3)
Location: include/linux/virtio_net.h:26
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82029b61)
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfd4ed)
Location: include/linux/virtio_net.h:28
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d044ed)
Location: include/linux/virtio_net.h:28
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f9642)
Location: include/linux/virtio_net.h:28
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffff8000109e17e0)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffff800010d5a358)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (c0ac68f0)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (c0e58e78)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (c000000000aa3514)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (c000000000e94750)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffe00062b290)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffe0008901f6)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8178b16e)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a2af82)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8176aabe)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff819e8172)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817bb50e)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81a96b32)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817d4549)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/packet/af_packet.c (ffffffff81aa37ac)
Location: include/linux/virtio_net.h:8
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
