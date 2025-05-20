# Function: <code>dst_metric_raw</code>

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
In net/ipv4/route.c (ffffffff81753085)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff8175a85d)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175ca96)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8176cb12)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_cwnd
```
```
In net/ipv4/tcp_output.c (ffffffff81774b35)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ccb8)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177fc5e)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781964)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/syncookies.c (ffffffff817ab232)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0f39)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff817c5858)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/route.c (ffffffff817d30e5)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_mtu
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_mtu_change_route
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0a7e)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd0dc)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff817ff6a0)
Location: include/net/dst.h:175
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff818005a5)
Location: include/net/dst.h:175
Inline: True
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
In net/ipv4/route.c (ffffffff817bf205)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff817c6c1b)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817cb48b)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff817dc6e8)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_init_cwnd
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff817e4a18)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eac38)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed1fa)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef69c)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/syncookies.c (ffffffff818192c6)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181de89)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff8183297a)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff818428f0)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185fd01)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ca0c)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff8186f00a)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81871cb5)
Location: include/net/dst.h:172
Inline: True
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
In net/ipv4/route.c (ffffffff817eeb55)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff817f671c)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817fb0eb)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff8180c7bf)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_init_cwnd
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81814e68)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b588)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181db10)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181feec)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/syncookies.c (ffffffff8184ab44)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f709)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff81864402)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81874660)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891c61)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f7fc)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff818a1f75)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff818a6215)
Location: include/net/dst.h:172
Inline: True
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
In net/ipv4/route.c (ffffffff8180ec15)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81816dec)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181b6b4)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff8182c8de)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_init_cwnd
```
```
In net/ipv4/tcp_output.c (ffffffff8183505c)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183be06)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d3a7)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184070d)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/syncookies.c (ffffffff8186e53f)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff818725fc)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873205)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_mtu
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff81889a03)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff818989ff)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8165)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5da1)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff818c8593)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff818ccc65)
Location: include/net/dst.h:176
Inline: True
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
In net/ipv4/route.c (ffffffff8188e1d5)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81895fb4)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8189a5ea)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff818ab828)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_init_cwnd
```
```
In net/ipv4/tcp_output.c (ffffffff818b44f0)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b9875)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bda1a)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfe81)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c044a)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/syncookies.c (ffffffff818eeee4)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2ff8)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3c15)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_mtu
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff8190a011)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff8191a48b)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193afeb)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81949133)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff8194bb4f)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81951a45)
Location: include/net/dst.h:178
Inline: True
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
In net/ipv4/route.c (ffffffff818e1ef5)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff818ea0a6)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ee8ca)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81900cad)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_init_cwnd
```
```
In net/ipv4/tcp_output.c (ffffffff81909b06)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910121)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913893)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915a46)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915f9c)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/syncookies.c (ffffffff819457f7)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949929)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a513)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff819613ba)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81972b79)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993a6b)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a21dd)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff819a4e05)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff819aafd5)
Location: include/net/dst.h:161
Inline: True
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
In net/ipv4/route.c (ffffffff8190ed95)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819174db)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191c062)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff8192ecc8)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_init_cwnd
```
```
In net/ipv4/tcp_output.c (ffffffff81937db2)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e5a1)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81942043)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff819441f6)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194473c)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bb88)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81975b89)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b5ea)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c4d3)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/ip6_output.c (ffffffff81995c94)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819a8519)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca17f)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8e3a)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff819db8fc)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff819e1af5)
Location: include/net/dst.h:161
Inline: True
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
In net/ipv4/route.c (ffffffff819708a5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81979423)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197e385)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819923c2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8199b82d)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a29f5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6642)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a87b9)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8d2c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d28c9)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff819df6e6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4b21)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e57e3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff819f651c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a019da)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a14907)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38d9f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a476b6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81a4a592)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81a508b5)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (ffffffff819a72a5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819afc82)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4d35)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819c8b4d)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d21ca)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d95da)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc4c2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df469)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0229)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a09200)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81a1671e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bb0a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c813)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d19c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3859b)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a4b4f7)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f90f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e236)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81a81154)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81a874d5)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (ffffffff81a905f5)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a99c63)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9ef2c)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81ab3b77)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81abe9cd)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac64a6)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca570)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc9d9)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accc6c)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8d5b)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81b076fd)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0dbd3)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f3b0)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e433)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b48b39)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b697f7)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78f15)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b7bdfe)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81b82ae5)
Location: include/net/dst.h:149
Inline: True
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
In net/core/dst.c (ffffffff81a10b35)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81a9d097)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3bb3)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa8e6c)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81abe4e7)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81aca32d)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad37ca)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad64d0)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad89b2)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8c6c)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05b2b)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81b15b41)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bde3)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2dc80)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ce83)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b57749)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78261)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87e95)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b8aeba)
Location: include/net/dst.h:149
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81b92155)
Location: include/net/dst.h:149
Inline: True
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
In net/core/dst.c (ffffffff819f79a5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81a86310)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_mtu
  - net/ipv4/route.c:ipv4_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ee86)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a93f5d)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81aab09f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ab58d1)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe865)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac154a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac38d1)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3cdc)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af13ae)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81b03953)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b09ad3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b58e)
Location: include/net/dst.h:150
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a2e3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b45333)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b671aa)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76b42)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b79d1d)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81b81425)
Location: include/net/dst.h:150
Inline: True
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
In net/core/dst.c (ffffffff81aa9595)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81b42643)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49da8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4f62e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81b67118)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81b72911)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c395)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e5ca)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81ddd)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82a81)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb151e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81bc5b8f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bccaa3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81be00bb)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81befebe)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81c0c473)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2eda3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c415ba)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81c44976)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81c4d445)
Location: include/net/dst.h:150
Inline: True
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
In net/core/dst.c (ffffffff81c21935)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81ccf59d)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd72e1)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cdcfcb)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81cf61a0)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81d01ef5)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c2c1)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e56b)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1222e)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d13687)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44bd8)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81d5ae81)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d627c3)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81d76e41)
Location: include/net/dst.h:151
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81d87f55)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81da735b)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc18c)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfcf3)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81de397d)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81ded9a5)
Location: include/net/dst.h:151
Inline: True
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
In net/core/dst.c (ffffffff81dd3b55)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81e8f78d)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81e97902)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9da3b)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81ebabb0)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ec711c)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1d01)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed402b)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed801e)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9627)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0de78)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81f252f1)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d2f3)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81f436a1)
Location: include/net/dst.h:151
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f55cf1)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81f7697b)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d29e)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb2013)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81fb5ffd)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81fc1775)
Location: include/net/dst.h:151
Inline: True
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
In net/core/dst.c (ffffffff81e44915)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81eede8d)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6142)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81efc1bc)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81f19042)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81f259cd)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2ac08)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f309d6)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f3304b)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f370e0)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38707)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6db28)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81f84e82)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cdf3)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa2e81)
Location: include/net/dst.h:165
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb56c9)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81fd69ab)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdd70)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff8201272d)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff82016716)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff820226f5)
Location: include/net/dst.h:165
Inline: True
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
In net/core/dst.c (ffffffff81f03575)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_blackhole_mtu
```
```
In net/ipv4/route.c (ffffffff81fb1fed)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81fba0de)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fc011c)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd766)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fed9bc)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_delack_max
  - net/ipv4/tcp_output.c:tcp_delack_max
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef827)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff68e6)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff919b)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd1dd)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe7c7)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034278)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff8204b5f8)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a783)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff820704b2)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff820869b1)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff820a432b)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccbfc)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/syncookies.c (ffffffff820e5742)
Location: include/net/dst.h:165
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff820f1815)
Location: include/net/dst.h:165
Inline: True
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
In net/ipv4/route.c (ffff800010c57020)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffff800010c60330)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c65648)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffff800010c7a77c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c84db4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cbc0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f62c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92d38)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93e28)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2518)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffff800010cd23c0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7da4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8a24)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffff800010cebdc8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cf8b10)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffff800010d11a5c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d382f0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49644)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffff800010d4c8f0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffff800010d53dc0)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (c0d666dc)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (c0d6fe0c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d75100)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (c0d88614)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d9405c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9cce4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (c0d9f404)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (c0da1764)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (c0da1d74)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdf0c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (c0ddc294)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (c0de18a8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c0de269c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (c0df3d20)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0e006a8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (c0e14e8c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (c0e3b5f0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (c0e4aa34)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (c0e4dc00)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (c0e5457c)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (c000000000d57d48)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (c000000000d63250)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69a48)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (c000000000d85614)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d90d00)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9ba94)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e4a0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (c000000000da2f74)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4414)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddc44)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (c000000000df0874)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (c000000000df7e3c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c000000000df9274)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (c000000000e0fe2c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e21cfc)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (c000000000e3b584)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6ba6c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ec30)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (c000000000e8308c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (c000000000e8c6f8)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (ffffffe0007c0ec6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffe0007c85c8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cce56)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffe0007de4b8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e66e4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebfb8)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef894)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f24d6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f33e0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817986)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffe00082375e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082837e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828fa6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffe00083967e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe000844830)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffe000856436)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008754e6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882ad4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffe00088567e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffe00088b938)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (ffffffff81947115)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff8194faf2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81954ba5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819689bd)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8197203a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197944a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c332)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f2d9)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81980099)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8fa0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff819b5dae)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb19a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbea3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc82c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819d7c2b)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819eab87)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ef9f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d8c6)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81a207e4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81a26b65)
Location: include/net/dst.h:150
Inline: True
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
In drivers/net/vxlan.c (ffffffff81772193)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/ipv4/route.c (ffffffff81900c05)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819095e2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190e695)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819224ad)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8192bb0a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932f0a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935df2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938d99)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939b59)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a60)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967a78)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81972b9e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977f8a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978c93)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff8198961c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819949eb)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a7947)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbd5f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da686)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff819dd5a4)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff819e3925)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (ffffffff819b18e5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819ba2c2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bf375)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819d318d)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819dc80a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3c1a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6b02)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9aa9)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea869)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13840)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81a2064e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25c1a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26923)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81a372ac)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a426ab)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a55607)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79a1f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a88346)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81a8b264)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81a92715)
Location: include/net/dst.h:150
Inline: True
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
In net/ipv4/route.c (ffffffff819baf85)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819c3bb2)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8cf5)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819dcd33)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e648a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edd3a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f07cc)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3855)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f46d9)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e210)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81a2bb4e)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a310ba)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31dd3)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42c3c)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e33b)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a61607)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_blackhole_mtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86212)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94f96)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81a97e86)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81a9e7e5)
Location: include/net/dst.h:150
Inline: True
```
</details>
</li>
</ul>

## Differences
