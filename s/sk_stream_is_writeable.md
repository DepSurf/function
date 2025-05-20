# Function: <code>sk_stream_is_writeable</code>

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
In net/core/stream.c (ffffffff8170e285)
Location: include/net/sock.h:1126
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81768da2)
Location: include/net/sock.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff817759b5)
Location: include/net/sock.h:1111
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff817d56f6)
Location: include/net/sock.h:1111
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff817a2f85)
Location: include/net/sock.h:1146
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818056d7)
Location: include/net/sock.h:1146
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff817c10d5)
Location: include/net/sock.h:1168
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818251d5)
Location: include/net/sock.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff8183aaf5)
Location: include/net/sock.h:1172
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818a3b4b)
Location: include/net/sock.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff81885235)
Location: include/net/sock.h:1186
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818f88d2)
Location: include/net/sock.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff81926354)
Location: include/net/sock.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff819874c1)
Location: include/net/sock.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff819bdc6c)
Location: include/net/sock.h:1238
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
In net/ipv4/tcp.c (ffffffff81aa970e)
Location: include/net/sock.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81baacec)
Location: include/net/sock.h:1286
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:ssk_check_wmem
  - net/mptcp/protocol.c:mptcp_data_acked
```
```
In net/mptcp/subflow.c (ffffffff81bade93)
Location: include/net/sock.h:1286
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbc190)
Location: include/net/sock.h:1302
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
In net/mptcp/protocol.c (ffffffff81bab261)
Location: include/net/sock.h:1314
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/subflow.c (ffffffff81bb116e)
Location: include/net/sock.h:1314
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
In net/mptcp/protocol.c (ffffffff81c77b81)
Location: include/net/sock.h:1326
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/subflow.c (ffffffff81c7f2ae)
Location: include/net/sock.h:1326
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
In net/mptcp/protocol.c (ffffffff81e1d042)
Location: include/net/sock.h:1380
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
Location: include/net/sock.h:1380
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
In net/mptcp/protocol.c (ffffffff81ff457f)
Location: include/net/sock.h:1419
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
Location: include/net/sock.h:1419
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
In net/mptcp/protocol.c (ffffffff82071034)
Location: include/net/sock.h:1404
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
Location: include/net/sock.h:1404
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
In net/mptcp/protocol.c (ffffffff82145639)
Location: include/net/sock.h:1379
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
Location: include/net/sock.h:1379
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c70724)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (c0d7eb64)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (c000000000d76a00)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffe0007d4c84)
Location: include/net/sock.h:1238
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195dadc)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff819175cc)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff819c82ac)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
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
In net/ipv4/tcp.c (ffffffff819d1dfc)
Location: include/net/sock.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
</ul>

## Differences
