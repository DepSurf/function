# Function: <code>__sk_stream_is_writeable</code>

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
In net/core/stream.c (ffffffff818a5965)
Location: include/net/sock.h:1219
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81926354)
Location: include/net/sock.h:1219
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff818f0c75)
Location: include/net/sock.h:1222
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819874c1)
Location: include/net/sock.h:1222
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff81922bd5)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819bdc6c)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff819f6655)
Location: include/net/sock.h:1280
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81aa970e)
Location: include/net/sock.h:1280
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81baacec)
Location: include/net/sock.h:1280
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:ssk_check_wmem
  - net/mptcp/protocol.c:mptcp_data_acked
```
```
In net/mptcp/subflow.c (ffffffff81bade93)
Location: include/net/sock.h:1280
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In net/core/stream.c (ffffffff819f6225)
Location: include/net/sock.h:1296
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81ab3a82)
Location: include/net/sock.h:1296
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbc190)
Location: include/net/sock.h:1296
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/stream.c (ffffffff819dc3d5)
Location: include/net/sock.h:1308
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81a9eac2)
Location: include/net/sock.h:1308
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81bab261)
Location: include/net/sock.h:1308
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/subflow.c (ffffffff81bb116e)
Location: include/net/sock.h:1308
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In net/core/stream.c (ffffffff81a8c615)
Location: include/net/sock.h:1320
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81b5a7d2)
Location: include/net/sock.h:1320
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81c77b81)
Location: include/net/sock.h:1320
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/subflow.c (ffffffff81c7f2ae)
Location: include/net/sock.h:1320
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In net/core/stream.c (ffffffff81c01e85)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81ce8c33)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1d042)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff81e24c57)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In net/core/stream.c (ffffffff81db1265)
Location: include/net/sock.h:1413
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81ead2c3)
Location: include/net/sock.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff457f)
Location: include/net/sock.h:1413
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff81ffc7c7)
Location: include/net/sock.h:1413
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In net/core/stream.c (ffffffff81e21775)
Location: include/net/sock.h:1398
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81f0b9d2)
Location: include/net/sock.h:1398
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff82071034)
Location: include/net/sock.h:1398
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff82078b07)
Location: include/net/sock.h:1398
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In net/core/stream.c (ffffffff81edf695)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81fcfa87)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff82145639)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
```
```
In net/mptcp/subflow.c (ffffffff8214e3a0)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:__mptcp_sync_state
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
In net/core/stream.c (ffff800010bbd858)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffff800010c70724)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (c0cd99ac)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (c0d7eb64)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (c000000000c96bd0)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (c000000000d76a00)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffe00074bcb0)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffe0007d4c84)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff818c2bd5)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff8195dadc)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff8187cb15)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819175cc)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff81913bd5)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819c82ac)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff81934d65)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819d1dfc)
Location: include/net/sock.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
</ul>

## Differences
