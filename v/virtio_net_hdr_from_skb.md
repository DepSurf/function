# Function: <code>virtio_net_hdr_from_skb</code>

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
In drivers/net/tun.c (ffffffff8164e8ee)
Location: include/linux/virtio_net.h:57
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651d03)
Location: include/linux/virtio_net.h:57
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/packet/af_packet.c (ffffffff81878695)
Location: include/linux/virtio_net.h:57
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff816805f0)
Location: include/linux/virtio_net.h:57
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818acee7)
Location: include/linux/virtio_net.h:57
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81695bfe)
Location: include/linux/virtio_net.h:57
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d5418)
Location: include/linux/virtio_net.h:57
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8170074b)
Location: include/linux/virtio_net.h:58
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81959ec8)
Location: include/linux/virtio_net.h:58
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8173fd8f)
Location: include/linux/virtio_net.h:58
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff819af172)
Location: include/linux/virtio_net.h:58
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81763dad)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff819e5b3c)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817a1b38)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff81a5556b)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817c2808)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff81a8c63b)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8188aa70)
Location: include/linux/virtio_net.h:128
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b879e8)
Location: include/linux/virtio_net.h:128
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81898c70)
Location: include/linux/virtio_net.h:133
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b974c8)
Location: include/linux/virtio_net.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8187b3a4)
Location: include/linux/virtio_net.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b864c7)
Location: include/linux/virtio_net.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8190c754)
Location: include/linux/virtio_net.h:165
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52887)
Location: include/linux/virtio_net.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81a60360)
Location: include/linux/virtio_net.h:165
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df5893)
Location: include/linux/virtio_net.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81bebb2d)
Location: include/linux/virtio_net.h:172
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc9708)
Location: include/linux/virtio_net.h:172
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81c43fce)
Location: include/linux/virtio_net.h:176
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c50ba1)
Location: include/linux/virtio_net.h:176
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In net/packet/af_packet.c (ffffffff8202bcf5)
Location: include/linux/virtio_net.h:176
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81cf988e)
Location: include/linux/virtio_net.h:194
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d06be1)
Location: include/linux/virtio_net.h:194
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In net/packet/af_packet.c (ffffffff820fb7a6)
Location: include/linux/virtio_net.h:194
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffff8000109dd300)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffff800010d57e00)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (c0ac5ab4)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (c0e59d78)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (c000000000aa397c)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (c000000000e92f20)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffe00062852a)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffe00088faa2)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817872d8)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff81a2bccb)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81766c28)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff819e8ebb)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817b7688)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff81a9787b)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817d1cee)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/packet/af_packet.c (ffffffff81aa419b)
Location: include/linux/virtio_net.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
</details>
</li>
</ul>

## Differences
