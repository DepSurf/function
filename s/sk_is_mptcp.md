# Function: <code>sk_is_mptcp</code>

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
In net/ipv4/tcp_input.c (ffffffff81aba853)
Location: include/net/mptcp.h:64
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abddf1)
Location: include/net/mptcp.h:64
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69b17)
Location: include/net/mptcp.h:64
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff81bac89c)
Location: include/net/mptcp.h:64
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_tcp_fallback
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
In net/ipv4/tcp_input.c (ffffffff81ac5c9b)
Location: include/net/mptcp.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_output.c (ffffffff81ac96d1)
Location: include/net/mptcp.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff81b15525)
Location: include/net/mptcp.h:67
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b785e9)
Location: include/net/mptcp.h:67
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff81bbd798)
Location: include/net/mptcp.h:67
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
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
In net/ipv4/tcp.c (ffffffff81aa19b1)
Location: include/net/mptcp.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0ea7)
Location: include/net/mptcp.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4581)
Location: include/net/mptcp.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff81b03335)
Location: include/net/mptcp.h:81
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67531)
Location: include/net/mptcp.h:81
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff81bad934)
Location: include/net/mptcp.h:81
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
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
In net/ipv4/tcp.c (ffffffff81b5d94d)
Location: include/net/mptcp.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81b6dceb)
Location: include/net/mptcp.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81b71525)
Location: include/net/mptcp.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff81bc5595)
Location: include/net/mptcp.h:100
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f14a)
Location: include/net/mptcp.h:100
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff81c7a34f)
Location: include/net/mptcp.h:100
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
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
In net/ipv4/tcp.c (ffffffff81cec300)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81cfd18b)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81d00bdd)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff81d5a765)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc56b)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff81e1e8b7)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
```
```
In net/mptcp/subflow.c (ffffffff81e2877a)
Location: include/net/mptcp.h:103
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
```
In net/mptcp/bpf.c (ffffffff81e36591)
Location: include/net/mptcp.h:103
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
In net/ipv4/tcp.c (ffffffff81eb01fc)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1d4b)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ec5d2d)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff81f24ba5)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d682)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff81ff5427)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
```
```
In net/mptcp/subflow.c (ffffffff820006fe)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
```
In net/mptcp/bpf.c (ffffffff8200f591)
Location: include/net/mptcp.h:102
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
In net/ipv4/tcp.c (ffffffff81f0e65c)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81f20275)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81f242e1)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff81f84735)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe103)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff820700b4)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
```
```
In net/mptcp/subflow.c (ffffffff8207c913)
Location: include/net/mptcp.h:102
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
```
In net/mptcp/bpf.c (ffffffff8208c179)
Location: include/net/mptcp.h:102
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
In net/ipv4/tcp.c (ffffffff81fd27c8)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4921)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8b16)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/syncookies.c (ffffffff8204aaf5)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccf1e)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/mptcp/protocol.c (ffffffff8214ad19)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
```
```
In net/mptcp/subflow.c (ffffffff82151e13)
Location: include/net/mptcp.h:123
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
```
In net/mptcp/bpf.c (ffffffff82162639)
Location: include/net/mptcp.h:123
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
