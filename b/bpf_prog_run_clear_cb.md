# Function: <code>bpf_prog_run_clear_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818049e8)
Location: include/linux/filter.h:376
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81877513)
Location: include/linux/filter.h:426
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818aad23)
Location: include/linux/filter.h:496
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d4489)
Location: include/linux/filter.h:549
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81958ee2)
Location: include/linux/filter.h:554
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff8173d576)
Location: include/linux/filter.h:594
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/packet/af_packet.c (ffffffff819b281f)
Location: include/linux/filter.h:594
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81761034)
Location: include/linux/filter.h:625
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/packet/af_packet.c (ffffffff819e978c)
Location: include/linux/filter.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff8179ecaf)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81a57ca5)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff817c33f7)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81a9027f)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff8188e746)
Location: include/linux/filter.h:710
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81b8b83d)
Location: include/linux/filter.h:710
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff8189d0a6)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81b9aca9)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff8187f8d6)
Location: include/linux/filter.h:762
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81b8a6b1)
Location: include/linux/filter.h:762
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81910a58)
Location: include/linux/filter.h:774
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81c567c1)
Location: include/linux/filter.h:774
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81a6082f)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81df5b47)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81becdee)
Location: include/linux/filter.h:749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81fca0c7)
Location: include/linux/filter.h:749
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81c452ef)
Location: include/linux/filter.h:749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff8202adca)
Location: include/linux/filter.h:749
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81cfac22)
Location: include/linux/filter.h:800
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff820fa8c6)
Location: include/linux/filter.h:800
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffff8000109dee68)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffff800010d5dab4)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (c0ac2a50)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (c0e5c5e4)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (c000000000aa0798)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (c000000000e9668c)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffe0006280ca)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffe000893870)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81787ec7)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81a2f90f)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff81767817)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff819ecaff)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff817b8277)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81a9b4bf)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff817d0561)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/packet/af_packet.c (ffffffff81aa5cae)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
</ul>

## Differences
