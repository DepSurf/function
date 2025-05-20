# Function: <code>skb_set_hash</code>

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
In net/ipv4/tcp_output.c (ffffffff81774bcb)
Location: include/linux/skbuff.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff817e1b4c)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff8181204c)
Location: include/linux/skbuff.h:1084
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff818323a2)
Location: include/linux/skbuff.h:1077
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff818b14de)
Location: include/linux/skbuff.h:1151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81906d1a)
Location: include/linux/skbuff.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81934ece)
Location: include/linux/skbuff.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff81998e86)
Location: include/linux/skbuff.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37bee)
Location: include/linux/skbuff.h:1228
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff819cf9a6)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e726)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff81abc2f2)
Location: include/linux/skbuff.h:1256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b68324)
Location: include/linux/skbuff.h:1256
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff81ac7b65)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76b60)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff81ab2bc5)
Location: include/linux/skbuff.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65598)
Location: include/linux/skbuff.h:1281
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff81b6fab9)
Location: include/linux/skbuff.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d7f4)
Location: include/linux/skbuff.h:1294
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff81cff145)
Location: include/linux/skbuff.h:1601
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcabed)
Location: include/linux/skbuff.h:1601
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff81ec41a5)
Location: include/linux/skbuff.h:1445
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b89c)
Location: include/linux/skbuff.h:1445
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In drivers/net/virtio_net.c (ffffffff81c56121)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_buf
```
```
In net/ipv4/ip_output.c (ffffffff81efca20)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_output.c (ffffffff81f224aa)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbc5d)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In drivers/net/virtio_net.c (ffffffff81d0c748)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_buf
```
```
In net/ipv4/ip_output.c (ffffffff81fc0958)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_output.c (ffffffff81fe70b6)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca36d)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffff800010c82b98)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37fa8)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (c0d91594)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (c0e38984)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (c000000000d8d9ec)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6962c)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffe0007e43a4)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087439e)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff8196f816)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ddb6)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff819292e6)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab76)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff819d9fe6)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78836)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/tcp_output.c (ffffffff819e3c5b)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84fc6)
Location: include/linux/skbuff.h:1224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
</details>
</li>
</ul>

## Differences
