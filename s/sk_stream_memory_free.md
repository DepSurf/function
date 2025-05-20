# Function: <code>sk_stream_memory_free</code>

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
In net/core/stream.c (ffffffff8170e29d)
Location: include/net/sock.h:1117
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81768dbe)
Location: include/net/sock.h:1117
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/core/stream.c (ffffffff81775b29)
Location: include/net/sock.h:1102
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff817d662c)
Location: include/net/sock.h:1102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/core/stream.c (ffffffff817a2cf9)
Location: include/net/sock.h:1137
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff8180657b)
Location: include/net/sock.h:1137
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/core/stream.c (ffffffff817c0eec)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff8182673a)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
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
In net/core/stream.c (ffffffff8183a907)
Location: include/net/sock.h:1163
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818a485d)
Location: include/net/sock.h:1163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
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
In kernel/bpf/sockmap.c (ffffffff811cfaae)
Location: include/net/sock.h:1177
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
```
In net/core/stream.c (ffffffff81885080)
Location: include/net/sock.h:1177
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/ipv4/tcp.c (ffffffff818fa64e)
Location: include/net/sock.h:1177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
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
In net/core/stream.c (ffffffff818a5688)
Location: include/net/sock.h:1214
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81928587)
Location: include/net/sock.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977a04)
Location: include/net/sock.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff818f09ae)
Location: include/net/sock.h:1217
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8198b4f7)
Location: include/net/sock.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1502)
Location: include/net/sock.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff81922902)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819c1d4b)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a182c2)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff819f64a4)
Location: include/net/sock.h:1275
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81aad50d)
Location: include/net/sock.h:1275
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09675)
Location: include/net/sock.h:1275
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bad03d)
Location: include/net/sock.h:1275
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
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
In net/core/stream.c (ffffffff819f5f3d)
Location: include/net/sock.h:1291
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81ab48dd)
Location: include/net/sock.h:1291
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b178d1)
Location: include/net/sock.h:1291
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bbf967)
Location: include/net/sock.h:1291
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff81bc5237)
Location: include/net/sock.h:1291
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/core/stream.c (ffffffff819dc185)
Location: include/net/sock.h:1303
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81a9fa5b)
Location: include/net/sock.h:1303
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b054b2)
Location: include/net/sock.h:1303
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81baf542)
Location: include/net/sock.h:1303
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff81bb5a62)
Location: include/net/sock.h:1303
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/core/stream.c (ffffffff81a8c3c5)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81b5b814)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc7db9)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7d272)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff81c8477c)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/core/stream.c (ffffffff81c01c64)
Location: include/net/sock.h:1369
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81ceaafa)
Location: include/net/sock.h:1369
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d37b)
Location: include/net/sock.h:1369
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81e228a5)
Location: include/net/sock.h:1369
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff81e2aa1d)
Location: include/net/sock.h:1369
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/core/stream.c (ffffffff81db1024)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81eae91f)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2817b)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81ffb5a3)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff82002bad)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/core/stream.c (ffffffff81e21518)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81f0c993)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f875ff)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff8207792c)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff8207ed87)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/core/stream.c (ffffffff81edf2af)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81fd0a78)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ec7f)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff8214c959)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__subflow_push_pending
  - net/mptcp/protocol.c:__subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/options.c (ffffffff82154277)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/sched.c (ffffffff82161fb3)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_sched_get_send
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
In net/core/stream.c (ffff800010bbd670)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffff800010c74ac0)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4190)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (c0cd96a8)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (c0d83194)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c0dde098)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (c000000000c967f4)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (c000000000d7bff0)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c000000000df358c)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffe00074ba8a)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffe0007d7f46)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824e9c)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff818c2902)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff81961bbb)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7952)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff8187c842)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff8191b6ab)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974742)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff81913902)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819cc38b)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a223d2)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/core/stream.c (ffffffff81934a85)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/tcp.c (ffffffff819d5f1b)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d7a6)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
</ul>

## Differences
