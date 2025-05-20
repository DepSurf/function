# Function: <code>reqsk_queue_empty</code>

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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:184
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:184
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:183
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:183
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:183
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:183
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:182
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:182
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:184
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:184
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:184
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:184
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:184
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:184
Inline: True
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
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/request_sock.h:186
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/request_sock.h:186
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff819bc443)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819bdd3c)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (ffffffff81aa6eef)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81aa96d1)
Location: include/net/request_sock.h:186
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
In net/ipv4/inet_connection_sock.c (ffffffff81ab157f)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81ab3a42)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbe4c4)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
```
```
In net/mptcp/subflow.c (ffffffff81bc3259)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffffffff81a9c001)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81a9ea86)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81badc54)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
```
```
In net/mptcp/subflow.c (ffffffff81bb39df)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffffffff81b578a1)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b5a796)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81c7a691)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
```
```
In net/mptcp/subflow.c (ffffffff81c82125)
Location: include/net/request_sock.h:193
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffffffff81ce588c)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ce8bf4)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1d1b1)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
```
In net/mptcp/subflow.c (ffffffff81e27b45)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffffffff81ea8a8c)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ead284)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff46c9)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
```
In net/mptcp/subflow.c (ffffffff81fffa21)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffffffff81f0730c)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0b991)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff82070fcb)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
```
In net/mptcp/subflow.c (ffffffff8207bdf3)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffffffff81fcb651)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fcfa46)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff821455f2)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
```
In net/mptcp/subflow.c (ffffffff82151203)
Location: include/net/request_sock.h:195
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
In net/ipv4/inet_connection_sock.c (ffff800010c6ddf0)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffff800010c707b0)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (c0d7ca10)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d7ec2c)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (c000000000d74580)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d76b30)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (ffffffe0007d3510)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d4c5e)
Location: include/net/request_sock.h:186
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195c2b3)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8195dbac)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (ffffffff81915da3)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8191769c)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (ffffffff819c6a83)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819c837c)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/inet_connection_sock.c (ffffffff819d05d3)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819d1ecc)
Location: include/net/request_sock.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
</ul>

## Differences
