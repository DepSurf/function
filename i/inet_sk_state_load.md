# Function: <code>inet_sk_state_load</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f5027)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff818f87b2)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e1de)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991887)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff81923257)
Location: include/net/inet_sock.h:318
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81926234)
Location: include/net/inet_sock.h:318
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c5ce)
Location: include/net/inet_sock.h:318
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c80c7)
Location: include/net/inet_sock.h:318
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff81985c07)
Location: include/net/inet_sock.h:314
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff819873b0)
Location: include/net/inet_sock.h:314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0a0e)
Location: include/net/inet_sock.h:314
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36b59)
Location: include/net/inet_sock.h:314
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff819bc0a7)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff819bdb50)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d75d9)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d709)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff81aa6c1d)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81aa95b1)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4595)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d43)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff81ba9fdd)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
```
```
In net/mptcp/subflow.c (ffffffff81bae3ba)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
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
In net/ipv4/inet_connection_sock.c (ffffffff81ab127d)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81ab38d1)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acfed5)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b752a3)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff81bbc143)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_reset_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bc317b)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7993)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/ipv4/inet_connection_sock.c (ffffffff81a9c5ed)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81a9e921)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abaf35)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63b53)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff81bab213)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_reset_timer
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/subflow.c (ffffffff81bb3efe)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8d03)
Location: include/net/inet_sock.h:309
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/ipv4/inet_connection_sock.c (ffffffff81b581c4)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81b5a631)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78285)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b613)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff81c77b13)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:mptcp_subflow_send_ack
```
```
In net/mptcp/subflow.c (ffffffff81c82638)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88453)
Location: include/net/inet_sock.h:308
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/ipv4/inet_connection_sock.c (ffffffff81ce62e8)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81ce76de)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07f1b)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8b8f)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff81e1cfd4)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_subflow_send_ack
```
```
In net/mptcp/subflow.c (ffffffff81e2838c)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2eb73)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/ipv4/inet_connection_sock.c (ffffffff81ea9538)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81eb21a5)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecc9db)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9988f)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff81ff4514)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
```
```
In net/mptcp/subflow.c (ffffffff820002fc)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff82006d13)
Location: include/net/inet_sock.h:326
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/ipv4/inet_connection_sock.c (ffffffff81f07dc8)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81f10855)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b6bb)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa25f)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff82070ec4)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/subflow.c (ffffffff8207c4cc)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff820830b3)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/sockopt.c (ffffffff82088778)
Location: include/net/inet_sock.h:328
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
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
In net/ipv4/inet_connection_sock.c (ffffffff81fcc128)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81fd4a35)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff03eb)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c7ecf)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/mptcp/protocol.c (ffffffff821454e4)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_subflow_get_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_error_report
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/subflow.c (ffffffff8214db25)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_abort_override
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/diag.c (ffffffff82157805)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82158743)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/sockopt.c (ffffffff8215e370)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
```
In net/mptcp/sched.c (ffffffff82161f86)
Location: include/net/inet_sock.h:360
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
In net/ipv4/inet_connection_sock.c (ffff800010c6d604)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffff800010c7061c)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a494)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d35fd4)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (c0d7c6ac)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (c0d7ea54)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (c0d9a5d8)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (c0e38ea8)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (c000000000d7383c)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (c000000000d7688c)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98c00)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (c000000000e683c0)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffe0007d3204)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffe0007d4b80)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb7f6)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873642)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff8195bf17)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff8195d9c0)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977449)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cd99)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff81915a07)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff819174b0)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930f09)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9b59)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff819c66e7)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff819c8190)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1c19)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77819)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff819d0237)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff819d1ce0)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb969)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83f89)
Location: include/net/inet_sock.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
</ul>

## Differences
