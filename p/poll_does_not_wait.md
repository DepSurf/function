# Function: <code>poll_does_not_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170c8d6)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81768c5e)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff817be186)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff81775326)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff817d55be)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8182b106)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff817a2616)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81805538)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8185cb36)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff817c0126)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81825018)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff818812b6)
Location: include/linux/poll.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff81839b36)
Location: include/linux/poll.h:54
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff818a3988)
Location: include/linux/poll.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81902446)
Location: include/linux/poll.h:54
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff81884290)
Location: include/linux/poll.h:55
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff818f8795)
Location: include/linux/poll.h:55
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81959db7)
Location: include/linux/poll.h:55
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff818a46fe)
Location: include/linux/poll.h:55
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81926213)
Location: include/linux/poll.h:55
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8198ef05)
Location: include/linux/poll.h:55
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff818efe7e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81987393)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff819fa685)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff81921e9e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819bdb33)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81a31305)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff819f50de)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81aa9594)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b252c5)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff81baac95)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff819f4b0e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81ab38b4)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b33e35)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff81bb77ce)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbc126)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff819dac9e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81a9e904)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b217e5)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff81ba694e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81bab1f6)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff81a8b31e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81b5a614)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81be6b35)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff81c74952)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81c77af6)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff81c005ce)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81ce8a26)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81d7d515)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff81e184a2)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1cfb6)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff81dafdce)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81ead0b6)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81f4ad25)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff81fef804)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff44f6)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff81e2003e)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81f0b7d8)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81faa9d5)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff8206b7c4)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff82070ea6)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffffffff81eddf1e)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81fcf888)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff82077dc5)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/xdp/xsk.c (ffffffff8213f554)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff821454c6)
Location: include/linux/poll.h:57
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
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
In net/core/datagram.c (ffff800010bbc560)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffff800010c70604)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffff800010cf1c48)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (c0cd8884)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (c0d7ea38)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (c0df7ab4)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (c000000000c945f0)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (c000000000d76854)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (c000000000e15858)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffe00074a6d2)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffe0007d4b66)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffe00083d9f6)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff818c1e9e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff8195d9a3)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff819d0995)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff8187bdde)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81917493)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8198d755)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff81912e9e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819c8173)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81a3b415)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/datagram.c (ffffffff8193401e)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819d1cc3)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81a46095)
Location: include/linux/poll.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
</details>
</li>
</ul>

## Differences
