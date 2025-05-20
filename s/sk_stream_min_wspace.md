# Function: <code>sk_stream_min_wspace</code>

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
In net/core/stream.c (0)
Location: include/net/sock.h:804
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/sock.h:804
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
In net/core/stream.c (ffffffff817759c1)
Location: include/net/sock.h:806
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff817d5706)
Location: include/net/sock.h:806
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
In net/core/stream.c (ffffffff817a2f91)
Location: include/net/sock.h:827
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818056e7)
Location: include/net/sock.h:827
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
In net/core/stream.c (ffffffff817c10e1)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818251e5)
Location: include/net/sock.h:841
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
In net/core/stream.c (ffffffff8183ab01)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818a3b5b)
Location: include/net/sock.h:841
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
In net/core/stream.c (ffffffff8188523b)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818f88da)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
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
In net/core/stream.c (ffffffff818a596b)
Location: include/net/sock.h:876
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff8192635c)
Location: include/net/sock.h:876
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
In net/core/stream.c (ffffffff818f0c7b)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819874c7)
Location: include/net/sock.h:879
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
In net/core/stream.c (ffffffff81922be1)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819bdc78)
Location: include/net/sock.h:884
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
In net/core/stream.c (ffffffff819f6661)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81aa971a)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81baacec)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:ssk_check_wmem
  - net/mptcp/protocol.c:mptcp_data_acked
```
```
In net/mptcp/subflow.c (ffffffff81badea3)
Location: include/net/sock.h:930
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
In net/core/stream.c (ffffffff819f6231)
Location: include/net/sock.h:945
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81ab3a8e)
Location: include/net/sock.h:945
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbc19c)
Location: include/net/sock.h:945
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
Location: include/net/sock.h:949
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81a9eace)
Location: include/net/sock.h:949
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81bab26d)
Location: include/net/sock.h:949
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/subflow.c (ffffffff81bb117e)
Location: include/net/sock.h:949
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
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81b5a7de)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81c77b8d)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/subflow.c (ffffffff81c7f2be)
Location: include/net/sock.h:961
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
Location: include/net/sock.h:1001
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81ce8c43)
Location: include/net/sock.h:1001
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1d04e)
Location: include/net/sock.h:1001
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff81e24c63)
Location: include/net/sock.h:1001
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
Location: include/net/sock.h:1039
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81ead2d3)
Location: include/net/sock.h:1039
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff458b)
Location: include/net/sock.h:1039
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff81ffc7d3)
Location: include/net/sock.h:1039
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
Location: include/net/sock.h:1041
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81f0b9e2)
Location: include/net/sock.h:1041
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff82071044)
Location: include/net/sock.h:1041
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff82078b13)
Location: include/net/sock.h:1041
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
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff81fcfa97)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/mptcp/protocol.c (ffffffff82145649)
Location: include/net/sock.h:1012
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
In net/mptcp/subflow.c (ffffffff8214e3ac)
Location: include/net/sock.h:1012
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
In net/core/stream.c (ffff800010bbd860)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffff800010c7072c)
Location: include/net/sock.h:884
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
In net/core/stream.c (c0cd99b4)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (c0d7eb6c)
Location: include/net/sock.h:884
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
In net/core/stream.c (c000000000c96bd8)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (c000000000d76a08)
Location: include/net/sock.h:884
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
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffe0007d4c84)
Location: include/net/sock.h:884
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
In net/core/stream.c (ffffffff818c2be1)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff8195dae8)
Location: include/net/sock.h:884
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
In net/core/stream.c (ffffffff8187cb21)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819175d8)
Location: include/net/sock.h:884
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
In net/core/stream.c (ffffffff81913be1)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819c82b8)
Location: include/net/sock.h:884
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
In net/core/stream.c (ffffffff81934d71)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff819d1e08)
Location: include/net/sock.h:884
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
</details>
</li>
</ul>

## Differences
