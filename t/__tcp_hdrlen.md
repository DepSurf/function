# Function: <code>__tcp_hdrlen</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176bf78)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff817855d0)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff8179fd1c)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff817dc531)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebbfb)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec788)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efc2e)
Location: include/linux/tcp.h:32
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860733)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81799158)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff817b2be0)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff817ce6ec)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8180c5ff)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c570)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d078)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8182063e)
Location: include/linux/tcp.h:33
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818926ea)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff817b772e)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff817c54af)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817d03ef)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff817edb9c)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8182c53b)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cde9)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d894)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b4e)
Location: include/linux/tcp.h:33
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8d21)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8182fdee)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff8183f172)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81849db9)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff81869ddc)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff818ab40e)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc515)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bcfa4)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c02be)
Location: include/linux/tcp.h:33
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bbe8)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8187a462)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81889827)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81893fbf)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff818b9aa9)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818c4028)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8190085e)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911f00)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912dfe)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e1c)
Location: include/linux/tcp.h:33
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994e51)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8189b072)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff818aa6e7)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b49a9)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff818e0869)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818ed0b8)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8192ed24)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819406c9)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819415be)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819445c9)
Location: include/linux/tcp.h:33
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb734)
Location: include/linux/tcp.h:33
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff818e5752)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff818f602f)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819012e9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff8192eef9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff8193d665)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8198deeb)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4c06)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5bb8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8bb9)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a1c1)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819178a2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81927fb2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81933619)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff81961169)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff819704f5)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819c4abb)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db906)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc978)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df859)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70d62)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819e9ee2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff819fc599)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a00da5)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/tso.c (ffffffff81a3467c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a4433d)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81aaff77)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac89da)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a48)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acccfb)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a56a)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819e9c82)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff819fbe49)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a011b5)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a2c6ea)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81a36a49)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/net-traces.c (ffffffff81a480ad)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81abafc1)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ac75a3)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad497a)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5998)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8cfb)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7903f)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819cfdc4)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff819e244f)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819e79f2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a13c9a)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81a1dbc4)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/net-traces.c (ffffffff81a2d008)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5f81)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ab25c2)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfa30)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09f7)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3d6a)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67b89)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81a7f7f4)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81a92860)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a98112)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81ac575a)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81ad1664)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/net-traces.c (ffffffff81ae25d8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81b62361)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f462)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d59c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e3b7)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b823fa)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f7d9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81bf3c43)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81c08b1f)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c0fde1)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81c4128f)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81c4ef69)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/net-traces.c (ffffffff81c661a0)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81cf15f1)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81cfeb12)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d500)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e335)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d128fa)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccbc2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81da19a3)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81db885f)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dbf821)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81df69ef)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81e04019)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/net-traces.c (ffffffff81e1cefd)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5df1)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3a42)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2f3a)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3de5)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed873a)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dcd9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/flow_dissector.c (ffffffff81e28b93)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e2f4be)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81e6869f)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81e768b8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/gso.c (ffffffff81e7d463)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/core/net-traces.c (ffffffff81e917fd)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81f14211)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81f21c82)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31c3b)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32dd9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f3784a)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe80c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/flow_dissector.c (ffffffff81ee6abd)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef9726)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f2786f)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/core/tso.c (ffffffff81f3687b)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/gso.c (ffffffff81f3e3e3)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/core/net-traces.c (ffffffff81f53bbd)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81fd86f1)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5c22)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7c89)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8f29)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd91a)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd56e)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb5ec)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (ffff800010bb0c44)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffff800010bc4410)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bd1708)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffff800010c04a3c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffff800010c19380)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffff800010c7abb4)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec98)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8dc)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c933d4)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39228)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In drivers/net/ethernet/freescale/fec_main.c (c0acd8e8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (c0ccdfcc)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (c0cdf904)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c0cec338)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (c0d1dea0)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (c0d2e998)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (c0d88234)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c0d9dbe0)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (c0d9e99c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c0da1bcc)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e3bd70)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (c000000000c86e58)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (c000000000c9e784)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c000000000cafab8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (c000000000cee9e8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (c000000000d05874)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (c000000000d7f930)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d7f8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8f4)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3610)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c7f8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffe000741df6)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffe000750d34)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe00075bb8e)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffe000783626)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffe00079241c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffe0007de5b2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eef46)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc04)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2918)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876574)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff818b78a2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff818c7fb2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818d3619)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff81901139)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff819104c5)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8196492b)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b776)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7e8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f6c9)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a103f2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff818717f2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81881ef2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8188d4a9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff818baf69)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818ca285)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8191e41b)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81935236)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819362a8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939189)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd1b2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819088a2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff81918fb2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81924619)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff81952169)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff819614f5)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819cf0fb)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5f46)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6fb8)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9e99)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ae72)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81929952)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/flow_dissector.c (ffffffff8193a18c)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81945aa9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff81973ba9)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81983765)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c8b)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efc06)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c88)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3cc9)
Location: include/linux/tcp.h:29
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a876b2)
Location: include/linux/tcp.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
</details>
</li>
</ul>

## Differences
