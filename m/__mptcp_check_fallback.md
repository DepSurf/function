# Function: <code>__mptcp_check_fallback</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bc0a4d)
Location: net/mptcp/protocol.h:631
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_getsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81bc30fd)
Location: net/mptcp/protocol.h:631
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bc50f1)
Location: net/mptcp/protocol.h:631
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
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
In net/mptcp/protocol.c (ffffffff81bab8ae)
Location: net/mptcp/protocol.h:786
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81bb3822)
Location: net/mptcp/protocol.h:786
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bb5899)
Location: net/mptcp/protocol.h:786
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/sockopt.c (ffffffff81bbca24)
Location: net/mptcp/protocol.h:786
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
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
In net/mptcp/protocol.c (ffffffff81c79e0f)
Location: net/mptcp/protocol.h:840
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81c81f64)
Location: net/mptcp/protocol.h:840
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81c845c9)
Location: net/mptcp/protocol.h:840
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/sockopt.c (ffffffff81c8c891)
Location: net/mptcp/protocol.h:840
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
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
In net/mptcp/protocol.c (ffffffff81e23da0)
Location: net/mptcp/protocol.h:920
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81e27c6b)
Location: net/mptcp/protocol.h:920
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81e2a873)
Location: net/mptcp/protocol.h:920
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/sockopt.c (ffffffff81e34d93)
Location: net/mptcp/protocol.h:920
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
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
In net/mptcp/protocol.c (ffffffff81ffad61)
Location: net/mptcp/protocol.h:952
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81fffb9b)
Location: net/mptcp/protocol.h:952
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff82002a03)
Location: net/mptcp/protocol.h:952
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/sockopt.c (ffffffff8200da03)
Location: net/mptcp/protocol.h:952
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
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
In net/mptcp/protocol.c (ffffffff82072da7)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff8207bb3e)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff8207ebdb)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/sockopt.c (ffffffff8208a3d3)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
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
In net/mptcp/protocol.c (ffffffff82146ef5)
Location: net/mptcp/protocol.h:1068
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_error_report
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff82150f5b)
Location: net/mptcp/protocol.h:1068
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff821540cb)
Location: net/mptcp/protocol.h:1068
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/sockopt.c (ffffffff8215fdf3)
Location: net/mptcp/protocol.h:1068
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
```
In net/mptcp/sched.c (ffffffff82162117)
Location: net/mptcp/protocol.h:1068
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_sched_get_retrans
  - net/mptcp/sched.c:mptcp_sched_get_send
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
