# Function: <code>inet_csk_listen_poll</code>

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
In net/ipv4/tcp.c (ffffffff81768d75)
Location: include/net/inet_connection_sock.h:311
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff817d56c9)
Location: include/net/inet_connection_sock.h:311
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff818056a4)
Location: include/net/inet_connection_sock.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff8182512f)
Location: include/net/inet_connection_sock.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff818a3aa5)
Location: include/net/inet_connection_sock.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff818f898f)
Location: include/net/inet_connection_sock.h:298
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff81926415)
Location: include/net/inet_connection_sock.h:300
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81987575)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bdd3c)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa96d1)
Location: include/net/inet_connection_sock.h:303
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff81ab3a42)
Location: include/net/inet_connection_sock.h:303
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbe4c4)
Location: include/net/inet_connection_sock.h:303
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
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
In net/ipv4/tcp.c (ffffffff81a9ea86)
Location: include/net/inet_connection_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81badc54)
Location: include/net/inet_connection_sock.h:301
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
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
In net/ipv4/tcp.c (ffffffff81b5a796)
Location: include/net/inet_connection_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81c7a691)
Location: include/net/inet_connection_sock.h:301
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
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
In net/ipv4/tcp.c (ffffffff81ce8bf4)
Location: include/net/inet_connection_sock.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1d1b1)
Location: include/net/inet_connection_sock.h:307
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
In net/ipv4/tcp.c (ffffffff81ead284)
Location: include/net/inet_connection_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff46c9)
Location: include/net/inet_connection_sock.h:310
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
In net/ipv4/tcp.c (ffffffff81f0b991)
Location: include/net/inet_connection_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff82070fcb)
Location: include/net/inet_connection_sock.h:310
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
In net/ipv4/tcp.c (ffffffff81fcfa46)
Location: include/net/inet_connection_sock.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff821455f2)
Location: include/net/inet_connection_sock.h:313
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c707b0)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7ec2c)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d76b30)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d4c5e)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195dbac)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191769c)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c837c)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d1ecc)
Location: include/net/inet_connection_sock.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
</ul>

## Differences
