# Function: <code>mptcp_subflow_ctx</code>

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
In net/mptcp/protocol.c (ffffffff81baca66)
Location: net/mptcp/protocol.h:310
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_socket_create
```
```
In net/mptcp/subflow.c (ffffffff81badfb5)
Location: net/mptcp/protocol.h:310
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_init_req
  - net/mptcp/subflow.c:subflow_rebuild_header
```
```
In net/mptcp/options.c (ffffffff81bb121e)
Location: net/mptcp/protocol.h:310
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81bb1b15)
Location: net/mptcp/protocol.h:310
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
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
In net/mptcp/protocol.c (ffffffff81bbe32a)
Location: net/mptcp/protocol.h:423
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bc0f95)
Location: net/mptcp/protocol.h:423
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bc5859)
Location: net/mptcp/protocol.h:423
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81bc5dd5)
Location: net/mptcp/protocol.h:423
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
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
In net/mptcp/protocol.c (ffffffff81badaa3)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bb0f45)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bb624a)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81bb6935)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff81bb78d5)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbbac7)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff81bbcb25)
Location: net/mptcp/protocol.h:441
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
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
In net/mptcp/protocol.c (ffffffff81c7a4e0)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81c7f025)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81c850e8)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81c85965)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff81c86fc5)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_chk_stale
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b707)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
```
In net/mptcp/sockopt.c (ffffffff81c8c985)
Location: net/mptcp/protocol.h:471
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
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
In net/mptcp/protocol.c (ffffffff81e1ebd7)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81e248f5)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81e2af50)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81e2bbd5)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff81e2d6c5)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_chk_stale
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32ca5)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
```
In net/mptcp/sockopt.c (ffffffff81e350b5)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35fae)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
```
In net/mptcp/bpf.c (ffffffff81e365a9)
Location: net/mptcp/protocol.h:504
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
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
In net/mptcp/protocol.c (ffffffff81ff5567)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81ffc475)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_v6_send_synack
  - net/mptcp/subflow.c:subflow_v4_send_synack
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff82003100)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff82003dd5)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff82005b45)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_chk_stale
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b705)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8200dd35)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ecbd)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
```
In net/mptcp/bpf.c (ffffffff8200f5a9)
Location: net/mptcp/protocol.h:522
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
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
In net/mptcp/protocol.c (ffffffff82076416)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff820787c5)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_v6_send_synack
  - net/mptcp/subflow.c:subflow_v4_send_synack
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff8207f290)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_established_options_dss
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff8207ff25)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff82081ec5)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_chk_stale
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82087c1b)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8208a725)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b854)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
```
In net/mptcp/bpf.c (ffffffff8208c191)
Location: net/mptcp/protocol.h:527
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
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
In net/mptcp/protocol.c (ffffffff8214ac73)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff8214db75)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
  - net/mptcp/subflow.c:subflow_ulp_clone
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcpv6_handle_mapped
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:__mptcp_sync_state
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_v6_send_synack
  - net/mptcp/subflow.c:subflow_v4_send_synack
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff82154780)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_established_options_dss
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff82155415)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff821574b5)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_chk_stale
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d453)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff821600f5)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff82161655)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
```
```
In net/mptcp/sched.c (ffffffff821621b9)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_sched_get_retrans
  - net/mptcp/sched.c:mptcp_sched_get_send
  - net/mptcp/sched.c:mptcp_sched_get_send
```
```
In net/mptcp/bpf.c (ffffffff82162651)
Location: net/mptcp/protocol.h:539
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
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
