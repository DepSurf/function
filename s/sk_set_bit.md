# Function: <code>sk_set_bit</code>

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
In net/core/sock.c (ffffffff817023ce)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8170c9a4)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff8170e472)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81768dc6)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff817be2bd)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
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
In net/core/sock.c (ffffffff8176960e)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817753fd)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81775bb7)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff817d571a)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8182b23a)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff81796519)
Location: include/net/sock.h:2047
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817a26ed)
Location: include/net/sock.h:2047
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff817a2d90)
Location: include/net/sock.h:2047
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818056fb)
Location: include/net/sock.h:2047
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8185cc6a)
Location: include/net/sock.h:2047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff817b46d9)
Location: include/net/sock.h:2071
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817c01f4)
Location: include/net/sock.h:2071
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff817c0e20)
Location: include/net/sock.h:2071
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818251f9)
Location: include/net/sock.h:2071
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81881394)
Location: include/net/sock.h:2071
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff8182c939)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81839c0a)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff8183a833)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818a3b6f)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8190252a)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/bpf/sockmap.c (ffffffff811cec17)
Location: include/net/sock.h:2088
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
```
```
In net/core/sock.c (ffffffff81877809)
Location: include/net/sock.h:2088
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81884355)
Location: include/net/sock.h:2088
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81884fac)
Location: include/net/sock.h:2088
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818f8917)
Location: include/net/sock.h:2088
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81959ed5)
Location: include/net/sock.h:2088
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff81898929)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818a47c7)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818a55ae)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8192639b)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977e96)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198f02a)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff818e2ec5)
Location: include/net/sock.h:2184
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818eff39)
Location: include/net/sock.h:2184
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818f08de)
Location: include/net/sock.h:2184
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81987503)
Location: include/net/sock.h:2184
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e190b)
Location: include/net/sock.h:2184
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fa79d)
Location: include/net/sock.h:2184
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff819150a5)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81921f62)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81922830)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819bdcbc)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1891b)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a31427)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff819e8415)
Location: include/net/sock.h:2243
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819f51b7)
Location: include/net/sock.h:2243
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819f63d2)
Location: include/net/sock.h:2243
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81aa975e)
Location: include/net/sock.h:2243
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b08703)
Location: include/net/sock.h:2243
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b253e3)
Location: include/net/sock.h:2243
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/mptcp/protocol.c (ffffffff81babcfe)
Location: include/net/sock.h:2243
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
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
In net/core/sock.c (ffffffff819e80b5)
Location: include/net/sock.h:2264
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819f4be7)
Location: include/net/sock.h:2264
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819f6024)
Location: include/net/sock.h:2264
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81ab3ae1)
Location: include/net/sock.h:2264
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b168a3)
Location: include/net/sock.h:2264
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b33f53)
Location: include/net/sock.h:2264
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/mptcp/protocol.c (ffffffff81bbc38e)
Location: include/net/sock.h:2264
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
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
In net/core/sock.c (ffffffff819ce1e5)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819dad77)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819dc090)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/skmsg.c (ffffffff81a4cd83)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/ipv4/tcp.c (ffffffff81a9eb21)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b21903)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/mptcp/protocol.c (ffffffff81bab13e)
Location: include/net/sock.h:2300
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
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
In net/core/sock.c (ffffffff81a7da95)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81a8b3f7)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81a8c2d0)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81b5a831)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6f53)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8873)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81be6c7d)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81beb613)
Location: include/net/sock.h:2351
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_msg_wait_data
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
In net/core/sock.c (ffffffff81bf1135)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81c006aa)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81c01b6e)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81ce8c9d)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c09d)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e0aa)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7d67b)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81d83a83)
Location: include/net/sock.h:2476
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In net/core/sock.c (ffffffff81d9d8f5)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81dafeaa)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81db0f2e)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81ead32d)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f266bd)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f285ff)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81f4ae8b)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81f51283)
Location: include/net/sock.h:2524
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In net/core/sock.c (ffffffff81e0c165)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81e20115)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81e2141e)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81f0ba3c)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8637d)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f8816f)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81faab37)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81fb0be3)
Location: include/net/sock.h:2512
Inline: True
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
In net/core/sock.c (ffffffff81ec8b07)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81eddff5)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81edf1b6)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81fcfaf1)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d95d)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f88f)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff82077f27)
Location: include/net/sock.h:2502
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff8207e283)
Location: include/net/sock.h:2502
Inline: True
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
In net/core/sock.c (ffff800010badf34)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffff800010bbc624)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffff800010bbd598)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffff800010c70770)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4408)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf1dd0)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (c0ccb9d8)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c0cd8934)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (c0cd95c4)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (c0d7ebac)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (c0dde5d4)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c0df7bcc)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (c000000000c8391c)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c000000000c946bc)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (c000000000c966f0)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (c000000000d76a70)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (c000000000df2454)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e15a20)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffe00073ff40)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffe00074a75a)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffe00074b9e6)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffe0007d4cb8)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffe000825382)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083db2e)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff818b50a5)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818c1f62)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818c2830)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8195db2c)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7fab)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d0ab7)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff8186eff5)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8187bea2)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff8187c770)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8191761c)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974d9b)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198d877)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff819060a5)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81912f62)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81913830)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819c82fc)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22a2b)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3b537)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/core/sock.c (ffffffff819270d5)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819340e2)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819349b3)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819d1e4c)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2de1e)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a461c0)
Location: include/net/sock.h:2194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
</ul>

## Differences
