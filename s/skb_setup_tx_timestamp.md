# Function: <code>skb_setup_tx_timestamp</code>

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
In net/ipv4/raw.c (ffffffff819480aa)
Location: include/net/sock.h:2418
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819be5f2)
Location: include/net/sock.h:2418
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e7c45)
Location: include/net/sock.h:2418
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ac377)
Location: include/net/sock.h:2424
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2d041)
Location: include/net/sock.h:2424
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a547d7)
Location: include/net/sock.h:2424
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff819e2e0f)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a63b82)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a8b3c7)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81ad06f8)
Location: include/net/sock.h:2497
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81b5c61a)
Location: include/net/sock.h:2497
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b871e7)
Location: include/net/sock.h:2497
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81adc708)
Location: include/net/sock.h:2518
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81b6ae5a)
Location: include/net/sock.h:2518
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b96d40)
Location: include/net/sock.h:2518
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81ac7753)
Location: include/net/sock.h:2554
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81b59160)
Location: include/net/sock.h:2554
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b85d43)
Location: include/net/sock.h:2554
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81b85f9c)
Location: include/net/sock.h:2613
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81c20752)
Location: include/net/sock.h:2613
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c520e9)
Location: include/net/sock.h:2613
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81d168e5)
Location: include/net/sock.h:2737
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81dbd4d7)
Location: include/net/sock.h:2737
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df4125)
Location: include/net/sock.h:2737
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81edd094)
Location: include/net/sock.h:2783
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81f8da16)
Location: include/net/sock.h:2783
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc8f53)
Location: include/net/sock.h:2783
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81f3c2e4)
Location: include/net/sock.h:2771
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff81fee1f2)
Location: include/net/sock.h:2771
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820298eb)
Location: include/net/sock.h:2771
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff8200240e)
Location: include/net/sock.h:2762
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (ffffffff820bbdbb)
Location: include/net/sock.h:2762
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f93b5)
Location: include/net/sock.h:2762
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffff800010c97bf0)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d29c38)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffff800010d59ef4)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (c0da59ec)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/raw.c (c0e2d9d0)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c0e58970)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (c000000000da8b50)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5aa50)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c000000000e94168)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffe0007f603a)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086a442)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffe00088fdf0)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff81982c7f)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a03212)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a2aa57)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff8193c73f)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bffd2)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff819e7c47)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff819ed44f)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6dc92)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a96607)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/ipv4/raw.c (ffffffff819f732f)
Location: include/net/sock.h:2445
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7a2b2)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81aa3281)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
</ul>

## Differences
