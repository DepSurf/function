# Function: <code>tcp_snd_cwnd</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c661ce)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp.c (ffffffff81cf02b3)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81cf8d2f)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81d0416b)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07f76)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f655)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_undo_cwnd
  - net/ipv4/tcp_cong.c:tcp_reno_ssthresh
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d12072)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_rate.c (ffffffff81d13a09)
Location: include/net/tcp.h:1212
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81d5b7fe)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:cubictcp_recalc_ssthresh
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8be9)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/core/net-traces.c (ffffffff81e1cf2b)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp.c (ffffffff81eb35e3)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81ebd832)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81ec90bb)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecca36)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed51d5)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_undo_cwnd
  - net/ipv4/tcp_cong.c:tcp_reno_ssthresh
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7e52)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed99e9)
Location: include/net/tcp.h:1225
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f25cbe)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:cubictcp_recalc_ssthresh
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f998e9)
Location: include/net/tcp.h:1225
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/core/net-traces.c (ffffffff81e9182b)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp.c (ffffffff81f11d03)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81f1bcdd)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81f27bdb)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b716)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_cong.c (ffffffff81f33eb5)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_undo_cwnd
  - net/ipv4/tcp_cong.c:tcp_reno_ssthresh
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_slow_start
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36ef4)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38ac9)
Location: include/net/tcp.h:1223
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f85cad)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:cubictcp_recalc_ssthresh
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa2b9)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/core/net-traces.c (ffffffff81f53beb)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/tcp.c (ffffffff81fd5fa3)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81fe04ce)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81fec66b)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0445)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa035)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_undo_cwnd
  - net/ipv4/tcp_cong.c:tcp_reno_ssthresh
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_slow_start
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcfe4)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffeba9)
Location: include/net/tcp.h:1260
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff8204c37d)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:cubictcp_recalc_ssthresh
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c7f25)
Location: include/net/tcp.h:1260
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
