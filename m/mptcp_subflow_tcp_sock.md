# Function: <code>mptcp_subflow_tcp_sock</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baca3c)
Location: net/mptcp/protocol.h:319
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81baf821)
Location: net/mptcp/protocol.h:319
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb39bf)
Location: net/mptcp/protocol.h:319
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:lookup_subflow_by_saddr
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
In net/mptcp/protocol.c (ffffffff81bbae7d)
Location: net/mptcp/protocol.h:432
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp6_release
  - net/mptcp/protocol.c:mptcp_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_check_fastclose
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bc3a29)
Location: net/mptcp/protocol.h:432
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc905e)
Location: net/mptcp/protocol.h:432
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received
  - net/mptcp/pm_netlink.c:lookup_subflow_by_saddr
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
In net/mptcp/protocol.c (ffffffff81bb0a8d)
Location: net/mptcp/protocol.h:450
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_flush_join_list
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/subflow.c (ffffffff81bb4097)
Location: net/mptcp/protocol.h:450
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9eea)
Location: net/mptcp/protocol.h:450
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
```
```
In net/mptcp/sockopt.c (ffffffff81bbcc11)
Location: net/mptcp/protocol.h:450
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/mptcp/protocol.c (ffffffff81c7eb4d)
Location: net/mptcp/protocol.h:480
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/subflow.c (ffffffff81c827f4)
Location: net/mptcp/protocol.h:480
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81c83dca)
Location: net/mptcp/protocol.h:480
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8981c)
Location: net/mptcp/protocol.h:480
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
```
```
In net/mptcp/sockopt.c (ffffffff81c8ca71)
Location: net/mptcp/protocol.h:480
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/mptcp/protocol.c (ffffffff81e242fa)
Location: net/mptcp/protocol.h:513
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/subflow.c (ffffffff81e28667)
Location: net/mptcp/protocol.h:513
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29f58)
Location: net/mptcp/protocol.h:513
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32375)
Location: net/mptcp/protocol.h:513
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff81e33931)
Location: net/mptcp/protocol.h:513
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35e96)
Location: net/mptcp/protocol.h:513
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In net/mptcp/protocol.c (ffffffff81ffbdda)
Location: net/mptcp/protocol.h:531
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/subflow.c (ffffffff820005e2)
Location: net/mptcp/protocol.h:531
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82002068)
Location: net/mptcp/protocol.h:531
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a6b5)
Location: net/mptcp/protocol.h:531
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff8200ba51)
Location: net/mptcp/protocol.h:531
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8200eb40)
Location: net/mptcp/protocol.h:531
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In net/mptcp/protocol.c (ffffffff820781aa)
Location: net/mptcp/protocol.h:536
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/subflow.c (ffffffff8207c7ca)
Location: net/mptcp/protocol.h:536
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207dc78)
Location: net/mptcp/protocol.h:536
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff82086815)
Location: net/mptcp/protocol.h:536
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff82088d8e)
Location: net/mptcp/protocol.h:536
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b6c8)
Location: net/mptcp/protocol.h:536
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In net/mptcp/protocol.c (ffffffff8214d400)
Location: net/mptcp/protocol.h:548
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_subflow_get_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_error_report
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/subflow.c (ffffffff82151c9d)
Location: net/mptcp/protocol.h:548
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:__mptcp_sync_state
```
```
In net/mptcp/options.c (ffffffff82152f51)
Location: net/mptcp/protocol.h:548
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b995)
Location: net/mptcp/protocol.h:548
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
```
```
In net/mptcp/sockopt.c (ffffffff82160254)
Location: net/mptcp/protocol.h:548
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff821613ff)
Location: net/mptcp/protocol.h:548
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
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
