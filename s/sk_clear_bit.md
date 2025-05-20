# Function: <code>sk_clear_bit</code>

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
In net/core/sock.c (ffffffff8170241e)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff8170e4ca)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81769127)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff817bfb1a)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff8176966c)
Location: include/net/sock.h:1990
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81775c23)
Location: include/net/sock.h:1990
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff817d60b2)
Location: include/net/sock.h:1990
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8182ca4b)
Location: include/net/sock.h:1990
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff81796577)
Location: include/net/sock.h:2056
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff817a2de2)
Location: include/net/sock.h:2056
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818060ca)
Location: include/net/sock.h:2056
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8185e515)
Location: include/net/sock.h:2056
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff817b4737)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff817c0e72)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81826560)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/unix/af_unix.c (ffffffff818838d8)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff8182c997)
Location: include/net/sock.h:2094
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff8183a88a)
Location: include/net/sock.h:2094
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818a466e)
Location: include/net/sock.h:2094
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/unix/af_unix.c (ffffffff81903fe1)
Location: include/net/sock.h:2094
Inline: True
Inline callers:
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
In kernel/bpf/sockmap.c (ffffffff811cec80)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
```
```
In net/core/sock.c (ffffffff81877873)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81885003)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff818fa3ca)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/unix/af_unix.c (ffffffff8195c110)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff81898993)
Location: include/net/sock.h:2187
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff818a5605)
Location: include/net/sock.h:2187
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8192830a)
Location: include/net/sock.h:2187
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977ee2)
Location: include/net/sock.h:2187
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8199091f)
Location: include/net/sock.h:2187
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff818e2f2f)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff818f092f)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8198b257)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1966)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fc002)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff8191510f)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81922881)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819c1ada)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18973)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a32c92)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff819e847f)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/stream.c (ffffffff819f6423)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81aad325)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b08751)
Location: include/net/sock.h:2252
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b2487c)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/mptcp/protocol.c (ffffffff81babd3d)
Location: include/net/sock.h:2252
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
In net/core/sock.c (ffffffff819e811f)
Location: include/net/sock.h:2273
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/stream.c (ffffffff819f6084)
Location: include/net/sock.h:2273
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81ab46f5)
Location: include/net/sock.h:2273
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b168f1)
Location: include/net/sock.h:2273
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b332ec)
Location: include/net/sock.h:2273
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/mptcp/protocol.c (ffffffff81bbc3cd)
Location: include/net/sock.h:2273
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
In net/core/sock.c (ffffffff819ce24c)
Location: include/net/sock.h:2309
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff819dc0f3)
Location: include/net/sock.h:2309
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/skmsg.c (ffffffff81a4cdd4)
Location: include/net/sock.h:2309
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/ipv4/tcp.c (ffffffff81a9f855)
Location: include/net/sock.h:2309
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/unix/af_unix.c (ffffffff81b21024)
Location: include/net/sock.h:2309
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/mptcp/protocol.c (ffffffff81bab180)
Location: include/net/sock.h:2309
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
In net/core/sock.c (ffffffff81a7db26)
Location: include/net/sock.h:2360
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81a8c333)
Location: include/net/sock.h:2360
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81b5b60e)
Location: include/net/sock.h:2360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6fa4)
Location: include/net/sock.h:2360
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc88a3)
Location: include/net/sock.h:2360
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81be60e4)
Location: include/net/sock.h:2360
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81beb640)
Location: include/net/sock.h:2360
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
In net/core/sock.c (ffffffff81bf11ca)
Location: include/net/sock.h:2485
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81c01bd2)
Location: include/net/sock.h:2485
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81cea7ad)
Location: include/net/sock.h:2485
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c0ee)
Location: include/net/sock.h:2485
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e0df)
Location: include/net/sock.h:2485
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7d2db)
Location: include/net/sock.h:2485
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81d83ab8)
Location: include/net/sock.h:2485
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
In net/core/sock.c (ffffffff81d9d986)
Location: include/net/sock.h:2533
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81db0f92)
Location: include/net/sock.h:2533
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81eae6a3)
Location: include/net/sock.h:2533
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2670e)
Location: include/net/sock.h:2533
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f2862f)
Location: include/net/sock.h:2533
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81f4a610)
Location: include/net/sock.h:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (0)
Location: include/net/sock.h:2533
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
In net/core/sock.c (ffffffff81e0c204)
Location: include/net/sock.h:2521
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81e2147f)
Location: include/net/sock.h:2521
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81f0c73c)
Location: include/net/sock.h:2521
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f863dc)
Location: include/net/sock.h:2521
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f8819f)
Location: include/net/sock.h:2521
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81faa2b0)
Location: include/net/sock.h:2521
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (0)
Location: include/net/sock.h:2521
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
In net/core/sock.c (ffffffff81ec8bac)
Location: include/net/sock.h:2511
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81edf217)
Location: include/net/sock.h:2511
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81fd0821)
Location: include/net/sock.h:2511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d9b8)
Location: include/net/sock.h:2511
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f8bf)
Location: include/net/sock.h:2511
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff820776d0)
Location: include/net/sock.h:2511
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (0)
Location: include/net/sock.h:2511
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
In net/core/sock.c (ffff800010badf9c)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffff800010bbd5dc)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffff800010c74928)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4464)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf2428)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (c0ccba38)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (c0cd9618)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (c0d82fa8)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c0dde620)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c0dfa380)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (c000000000c839a0)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (c000000000c96744)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (c000000000d7bc30)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c000000000df24ac)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e188a0)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffe00073ff82)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffe00074b9e8)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffe0007d7d42)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffe0008253c2)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083f42a)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff818b510f)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff818c2881)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8196194a)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b8003)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d2322)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff8186f05f)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff8187c7c1)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8191b43a)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974df3)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198f0e2)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff8190610f)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81913881)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819cc11a)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22a83)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3cda2)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff8192713f)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/stream.c (ffffffff81934a04)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819d5caa)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2de79)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a48355)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
</ul>

## Differences
