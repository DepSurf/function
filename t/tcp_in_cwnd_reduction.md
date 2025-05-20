# Function: <code>tcp_in_cwnd_reduction</code>

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
In net/ipv4/tcp_input.c (ffffffff8176b386)
Location: include/net/tcp.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81775266)
Location: include/net/tcp.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
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
In net/ipv4/tcp_input.c (ffffffff817dde46)
Location: include/net/tcp.h:1033
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff817e5fc1)
Location: include/net/tcp.h:1033
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/ipv4/tcp_input.c (ffffffff8180e306)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81813f36)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/ipv4/tcp_input.c (ffffffff8182e876)
Location: include/net/tcp.h:1123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff8183419b)
Location: include/net/tcp.h:1123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/ipv4/tcp_input.c (ffffffff818ad84a)
Location: include/net/tcp.h:1114
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff818b35ae)
Location: include/net/tcp.h:1114
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff818c407b)
Location: include/net/tcp.h:1131
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81902dc1)
Location: include/net/tcp.h:1131
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81908d1c)
Location: include/net/tcp.h:1131
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff818ed108)
Location: include/net/tcp.h:1171
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81930e6d)
Location: include/net/tcp.h:1171
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81936f64)
Location: include/net/tcp.h:1171
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff8193d6bc)
Location: include/net/tcp.h:1173
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819944e0)
Location: include/net/tcp.h:1173
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff8199c57c)
Location: include/net/tcp.h:1173
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff8197054c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819cb02e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff819d302e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81a44392)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81ab7eb9)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81abf94e)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81a48102)
Location: include/net/tcp.h:1219
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81ac317c)
Location: include/net/tcp.h:1219
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81acb403)
Location: include/net/tcp.h:1219
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81a2d05d)
Location: include/net/tcp.h:1211
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81aae4b5)
Location: include/net/tcp.h:1211
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6b81)
Location: include/net/tcp.h:1211
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81ae262e)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81b6af9f)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81b73d58)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81c661ef)
Location: include/net/tcp.h:1233
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81cfa145)
Location: include/net/tcp.h:1233
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81d03496)
Location: include/net/tcp.h:1233
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81e1cf4c)
Location: include/net/tcp.h:1246
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81ebec52)
Location: include/net/tcp.h:1246
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7cd1)
Location: include/net/tcp.h:1246
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81e9184c)
Location: include/net/tcp.h:1244
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81f1d0e5)
Location: include/net/tcp.h:1244
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81f2659e)
Location: include/net/tcp.h:1244
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff81f53c0c)
Location: include/net/tcp.h:1281
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff81fe161a)
Location: include/net/tcp.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81feaf7e)
Location: include/net/tcp.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffff800010c193bc)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffff800010c7dc2c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffff800010c85bcc)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (c0d2e9d4)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (c0d8cb5c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (c0d94e2c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (c000000000d058b0)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (c000000000d87b2c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (c000000000d91e28)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffe000792452)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffe0007e011a)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7364)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff8191051c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8196ae9e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81972e9e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff818ca2dc)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff8192498e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff8192c96e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff8196154c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819d566e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff819dd66e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
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
In net/core/net-traces.c (ffffffff819837bc)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp_input.c (ffffffff819df24e)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff819e72ee)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
</details>
</li>
</ul>

## Differences
