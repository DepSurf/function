# Function: <code>tcp_clock_us</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182c2e4)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818373a6)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81838617)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c4d0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff818ab175)
Location: include/net/tcp.h:701
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b6a56)
Location: include/net/tcp.h:701
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6da6)
Location: include/net/tcp.h:701
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbbfb)
Location: include/net/tcp.h:701
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff819005cc)
Location: include/net/tcp.h:711
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8190c295)
Location: include/net/tcp.h:711
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c626)
Location: include/net/tcp.h:711
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911656)
Location: include/net/tcp.h:711
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff8192e724)
Location: include/net/tcp.h:738
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff81993bc0)
Location: include/net/tcp.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff819ca710)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff81ab76df)
Location: include/net/tcp.h:765
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff81ac298f)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aadb1f)
Location: include/net/tcp.h:776
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6a60f)
Location: include/net/tcp.h:769
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf9793)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebe283)
Location: include/net/tcp.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1c723)
Location: include/net/tcp.h:791
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp.c (ffffffff81fd6e3f)
Location: include/net/tcp.h:806
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81fe0f03)
Location: include/net/tcp.h:806
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4024)
Location: include/net/tcp.h:806
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8c7c)
Location: include/net/tcp.h:806
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cac46)
Location: include/net/tcp.h:806
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
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
In net/ipv4/tcp_input.c (ffff800010c7d40c)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (c0d8ce98)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (c000000000d87f7c)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffe0007e0368)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff8196a580)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff81924070)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff819d4d50)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff819de930)
Location: include/net/tcp.h:760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
</ul>

## Differences
