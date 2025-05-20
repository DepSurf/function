# Function: <code>sk_to_full_sk</code>

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
In security/selinux/hooks.c (ffffffff813492f3)
Location: include/net/inet_sock.h:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/netlabel.c (ffffffff8135d58d)
Location: include/net/inet_sock.h:220
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8136616d)
Location: include/net/inet_sock.h:220
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b63a2)
Location: include/net/inet_sock.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In security/selinux/hooks.c (ffffffff8137e5bc)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8139356b)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8139c24d)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
```
```
In net/core/filter.c (ffffffff8179cce1)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182339b)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/calipso.c (ffffffff8186fee2)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff8139504c)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff813aa18b)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff813b2dfd)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
```
```
In net/core/filter.c (ffffffff817c9604)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff817f8095)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854ceb)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff8186679e)
Location: include/net/inet_sock.h:240
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818a2e52)
Location: include/net/inet_sock.h:240
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff813ab0e6)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff813c0b6b)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff813c978d)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/filter.c (ffffffff817ea119)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff818184a4)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp_input.c (ffffffff8182cb26)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_output.c (ffffffff8183563e)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183db0e)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81841214)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/netfilter.c (ffffffff8186e7dd)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878834)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff8188aee9)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/calipso.c (ffffffff818c941c)
Location: include/net/inet_sock.h:244
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff813d1146)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff813e6d3b)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff813efc1d)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81849cd8)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818657a9)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff81897604)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff818a3cca)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff818aba1d)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b4bf3)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdbd1)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/netfilter.c (ffffffff818ef19d)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f9184)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff8190c074)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81949d10)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff8194cabc)
Location: include/net/inet_sock.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff813fe3b0)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81417b3d)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81420a4a)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81893ed4)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b3c79)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff818eb8e4)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff818f647e)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff81900edd)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8190a229)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d305)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913a66)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/netfilter.c (ffffffff81945b41)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fbfe)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff819634f4)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff819a2d1f)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff819a5ec5)
Location: include/net/inet_sock.h:249
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff8141a240)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8143406d)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8143d09a)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff818b48c4)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818d8ddd)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff81918e04)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81924067)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff8192f095)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819384d1)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b6e4)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81942216)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819598ea)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81975e61)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983267)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff819984b4)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff819d99bf)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff819dc575)
Location: include/net/inet_sock.h:265
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff81447cc9)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81461b21)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8146ac9a)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff819011f7)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81927115)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff8194314c)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff8197aeac)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81986f1f)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819925d7)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff8199b705)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8199fa4c)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6839)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819be3af)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff819df9f0)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ece7b)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81a043d8)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81a4822e)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a4c265)
Location: include/net/inet_sock.h:261
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff81461859)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8147b8d1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81484a7a)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81933527)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff819597b5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff819780ff)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff819b181c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff819bd6af)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819c8c41)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819d212d)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6619)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcc41)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819f4fdf)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81a16a20)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23e8b)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81a3afc8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81a7edde)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a82e35)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff814b4dea)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814d0e4f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814dab6a)
Location: include/net/inet_sock.h:262
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff815000ff)
Location: include/net/inet_sock.h:262
Inline: True
```
```
In net/core/dev.c (ffffffff81a08390)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a2d315)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81a4cc1d)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81a9b80c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81aa87fc)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81ab45a4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81abef70)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2732)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca776)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81ae316f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81b07a60)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15ea3)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81b30588)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81b79a2e)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81b7cc95)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff814d2a7b)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814ee35f)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814f7fea)
Location: include/net/inet_sock.h:263
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff8151d2af)
Location: include/net/inet_sock.h:263
Inline: True
```
```
In net/core/dev.c (ffffffff81a0991f)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a2e7f5)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81a528dd)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81aa566c)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81ab2d7e)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81abee7c)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81aca8d3)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace196)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad416a)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad66d9)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81af004e)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81b15e43)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2431d)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f193)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b774cf)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff81b8897d)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81b8bd45)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff814d8fdb)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814f50cf)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814fed4a)
Location: include/net/inet_sock.h:263
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81523abf)
Location: include/net/inet_sock.h:263
Inline: True
```
```
In net/core/dev.c (ffffffff819f0296)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a15315)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81a3805a)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81a9072c)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81a9dfce)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81aab3e8)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ab57e0)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab932c)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf207)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac1748)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81adb78e)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81b03c45)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11f4d)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81b2bf90)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65fd7)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff81b776b1)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81b7abb4)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff815320d7)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8154facf)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81559d9a)
Location: include/net/inet_sock.h:262
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81581d4f)
Location: include/net/inet_sock.h:262
Inline: True
```
```
In net/core/dev.c (ffffffff81aa16c6)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81ac68c5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81aede9a)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81b4b896)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81b5ab9a)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81b677af)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81b727fb)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81b766f1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7cd4f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f1ab)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81b9b712)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81bc5ef5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5b13)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2107)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e06e)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff81c42182)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81c45874)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff815c94c4)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff815e8e80)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff815f4a8a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff81620b43)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81c19703)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81c379a5)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81c70cc4)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81cd8f13)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81ce9370)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81cf6868)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81d01e4c)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05fe1)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cc85)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0eb5a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81d2d3b2)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81d5b20c)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c3a1)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a90a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb959)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff81de0b31)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81de497c)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff816766b4)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81698750)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff816a552a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff816d4273)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81dca743)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81df8725)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81e28d44)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81e9955d)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81eac03f)
Location: include/net/inet_sock.h:280
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ebb278)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7143)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb332)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed26c5)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed463a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8a88)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/af_inet.c (ffffffff81ef4812)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81f2569c)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f37714)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81f588ba)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9ca59)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff81fb2f71)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81fb70ec)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff816ae9d4)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff816d0bd1)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff816ddf0a)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff8170d203)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81e3b2c3)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81e6a3c5)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81e9e375)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81ef7e69)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81f0a8bf)
Location: include/net/inet_sock.h:285
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f19775)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81f259f4)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29e70)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f313a5)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f3363c)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37b98)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/af_inet.c (ffffffff81f540f9)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81f8522c)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f97109)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81fb861e)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd4a9)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff82013661)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff8201782c)
Location: include/net/inet_sock.h:285
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff816eba15)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8170d22e)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8171aafa)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff8174b6b5)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81ef967d)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f29355)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81f60af1)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff81fbbd1f)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff81fce93f)
Location: include/net/inet_sock.h:317
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fddf8c)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fea2d9)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee9e6)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7335)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff97a9)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdc68)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/af_inet.c (ffffffff8201b8a9)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_listen_sk
```
```
In net/ipv4/netfilter.c (ffffffff8204b8dc)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8206446e)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff82085bec)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cb21d)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/netfilter.c (ffffffff820e27c4)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff820e67fc)
Location: include/net/inet_sock.h:317
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffff80001054efc8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffff80001056c384)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffff800010576ec4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffff800010bd162c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffff800010bf43e8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffff800010c1e98c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffff800010c61d08)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffff800010c71968)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffff800010c7a990)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffff800010c84d18)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffff800010c8956c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f800)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffff800010caae4c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffff800010cd2678)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce1100)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffff800010cfc0e0)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffff800010d4a6dc)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffff800010d4d52c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (c0708998)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (c071fbd8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (c0729cbc)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (c0cec268)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c0d0cb5c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (c0d369cc)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (c0d71784)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (c0d7e3e8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (c0d88764)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d9408c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (c0d989f0)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (c0d9f5cc)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (c0db77c4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (c0ddc580)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c0dea444)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (c0e03444)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (c0e4b5ec)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (c0e4f940)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (c0000000006b0274)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (c0000000006d055c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (c0000000006e0384)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (c000000000caf9c8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c000000000cd9518)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (c000000000d10ae4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (c000000000d65444)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (c000000000d75e08)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (c000000000d859a0)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (c000000000d90b88)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (c000000000d96898)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ed18)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (c000000000dc11c8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (c000000000df0c50)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c000000000e0361c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (c000000000e23ac4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (c000000000e7ff8c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (c000000000e85cf0)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffe0003a8f48)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffe0003c0e98)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffe0003c9446)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffe00075baf4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffe000775844)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffe0007985be)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffe0007c9e0c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffe0007d45b8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffe0007de522)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6728)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea548)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efebc)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffe000805ac4)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffe0008239c2)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fc70)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffe000846a12)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffe000883584)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffe000886322)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff81459e39)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81473eb1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8147d05a)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff818d3527)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818f9785)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff81917f6f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff8195168c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff8195d51f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81968ab1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81971f9d)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81976489)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197cab1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81994d7f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff819b60b0)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c351b)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff819da658)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81a1e46e)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a224c5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff8144a869)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814648d1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8146da7a)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff8188d3b7)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b35b5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff818d1d1f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff8190b17c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff8191700f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819225a1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff8192ba6d)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8192ff49)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936571)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff8194e83f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81972ea0)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198030b)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81997418)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff819db22e)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff819df285)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff81455ed9)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8146ff51)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814790fa)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81924527)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8194a7b5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff819690ff)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff819bbe5c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff819c7cef)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819d3281)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819dc76d)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0c59)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7281)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819ff61f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81a20950)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2df9b)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81a450d8)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81a88eee)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a8cf45)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
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
In security/selinux/hooks.c (ffffffff814711c9)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814877c1)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81490baa)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff819459b7)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8196c0c5)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/lwt_bpf.c (ffffffff8198b4df)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff819c576c)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp.c (ffffffff819d183f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819dce27)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819e63ed)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea919)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0f51)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81a0971f)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/netfilter.c (ffffffff81a2be70)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39793)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/ip6_output.c (ffffffff81a50d98)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/netfilter.c (ffffffff81a95b4e)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a99c05)
Location: include/net/inet_sock.h:262
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
```
</details>
</li>
</ul>

## Differences
