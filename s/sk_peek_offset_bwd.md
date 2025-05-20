# Function: <code>sk_peek_offset_bwd</code>

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
In net/unix/af_unix.c (ffffffff817bedac)
Location: include/net/sock.h:486
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774650)
Location: include/net/sock.h:480
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/unix/af_unix.c (ffffffff8182c69f)
Location: include/net/sock.h:480
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff817a1950)
Location: include/net/sock.h:501
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/ipv4/udp.c (ffffffff81824f06)
Location: include/net/sock.h:501
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff8185e156)
Location: include/net/sock.h:501
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff817bfe96)
Location: include/net/sock.h:516
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8184707f)
Location: include/net/sock.h:516
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81883642)
Location: include/net/sock.h:516
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81839a46)
Location: include/net/sock.h:520
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c6adf)
Location: include/net/sock.h:520
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81903d44)
Location: include/net/sock.h:520
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff8188418f)
Location: include/net/sock.h:527
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191c500)
Location: include/net/sock.h:527
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8195be70)
Location: include/net/sock.h:527
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff818a460f)
Location: include/net/sock.h:547
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194aad0)
Location: include/net/sock.h:547
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81990687)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff818efd87)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819af113)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fbd76)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81921da7)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e5e23)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a32a06)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff819f4e30)
Location: include/net/sock.h:591
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad3871)
Location: include/net/sock.h:591
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81b274ce)
Location: include/net/sock.h:591
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff819f4760)
Location: include/net/sock.h:598
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81adec31)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81b35da6)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff819daa07)
Location: include/net/sock.h:598
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ac9c21)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81b2399d)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81a8b087)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b884b1)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81be7e6c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81c007fc)
Location: include/net/sock.h:649
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1bc1a)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81d7f79a)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81dafb28)
Location: include/net/sock.h:680
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee2afa)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81f4d48a)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81e1fd98)
Location: include/net/sock.h:682
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f81a)
Location: include/net/sock.h:682
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81faced9)
Location: include/net/sock.h:682
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81edd448)
Location: include/net/sock.h:665
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82007e75)
Location: include/net/sock.h:665
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8207b326)
Location: include/net/sock.h:665
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
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
In net/core/datagram.c (ffff800010bbc460)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c995bc)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cf2148)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (c0cd89bc)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (c0da8300)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (c0dfa0ac)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (c000000000c94818)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/ipv4/udp.c (c000000000dab230)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (c000000000e18554)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffe00074b15c)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f71ac)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffe00083f2bc)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff818c1da7)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81985c93)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d2096)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff8187bce7)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8193f753)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198ee56)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81912da7)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f0463)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3cb16)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81933f27)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fade3)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a480d7)
Location: include/net/sock.h:549
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
</details>
</li>
</ul>

## Differences
