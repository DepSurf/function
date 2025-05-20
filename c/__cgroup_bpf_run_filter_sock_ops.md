# Function: <code>__cgroup_bpf_run_filter_sock_ops</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119f200)
Location: kernel/bpf/cgroup.c:256
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff8119f200-ffffffff8119f24f: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b21f0)
Location: kernel/bpf/cgroup.c:513
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
**Symbols:**

```
ffffffff811b21f0-ffffffff811b2272: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1780)
Location: kernel/bpf/cgroup.c:611
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
**Symbols:**

```
ffffffff811d1780-ffffffff811d1802: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e1320)
Location: kernel/bpf/cgroup.c:668
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff811e1320-ffffffff811e13c4: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7590)
Location: kernel/bpf/cgroup.c:741
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff811f7590-ffffffff811f768c: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204530)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff81204530-ffffffff8120462c: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c260)
Location: kernel/bpf/cgroup.c:1088
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff8122c260-ffffffff8122c35f: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234660)
Location: kernel/bpf/cgroup.c:1112
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81234660-ffffffff81234766: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812390d0)
Location: kernel/bpf/cgroup.c:1116
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff812390d0-ffffffff8123926a: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81273200)
Location: kernel/bpf/cgroup.c:1146
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81273200-ffffffff81273354: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c2ca0)
Location: kernel/bpf/cgroup.c:1295
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff812c2ca0-ffffffff812c2e07: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813272d0)
Location: kernel/bpf/cgroup.c:1509
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff813272d0-ffffffff81327437: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357790)
Location: kernel/bpf/cgroup.c:1509
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81357790-ffffffff813578f7: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81380140)
Location: kernel/bpf/cgroup.c:1524
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
  - net/ipv4/af_inet.c:__inet_listen_sk
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81380140-ffffffff813802a7: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028da38)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffff80001028da38-ffff80001028db8c: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bc4e0)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
c04bc4e0-c04bc6a4: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033a3f0)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
c00000000033a3f0-c00000000033a5d0: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c08b2)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffe0001c08b2-ffffffe0001c0a08: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fcb50)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff811fcb50-ffffffff811fcc4c: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811ef8a0)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff811ef8a0-ffffffff811ef99c: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fa920)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff811fa920-ffffffff811faa1c: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock *sk, struct bpf_sock_ops_kern *sock_ops, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209740)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/af_inet.c:inet_listen
```
**Symbols:**

```
ffffffff81209740-ffffffff81209854: __cgroup_bpf_run_filter_sock_ops (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
