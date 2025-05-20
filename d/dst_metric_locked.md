# Function: <code>dst_metric_locked</code>

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
In net/ipv4/route.c (ffffffff81755113)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff8175a85d)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175ca96)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8176cfc8)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81777f9f)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ccb8)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177fcd9)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781964)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff817c6ae4)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff817d49f0)
Location: include/net/dst.h:241
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
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
In net/ipv4/route.c (ffffffff817c1293)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff817c6c1b)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817cb48b)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff817dad71)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff817e4fc0)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e7d68)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed1fa)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef69c)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv6/ip6_output.c (ffffffff81833bb5)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff818428f0)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
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
In net/ipv4/route.c (ffffffff817f0893)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff817f671c)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817fb0eb)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff8180a8b1)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff8181544a)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81819938)
Location: include/net/dst.h:238
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181db10)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181feec)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv6/ip6_output.c (ffffffff8186562f)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff818770a1)
Location: include/net/dst.h:238
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
In net/ipv4/route.c (ffffffff81810ce3)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81816dec)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181b6b4)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff8182a993)
Location: include/net/dst.h:242
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81835877)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839ba1)
Location: include/net/dst.h:242
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d3a7)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184070d)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/xfrm4_output.c (ffffffff818725fc)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81889e43)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff8189c66f)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff818902c3)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81895fb4)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8189a5ea)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff818aa537)
Location: include/net/dst.h:244
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b4da2)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bae1d)
Location: include/net/dst.h:244
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bda1a)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfe81)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2ff8)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff8190b035)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff8191a48b)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
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
In net/ipv4/route.c (ffffffff818e3a67)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff818ea0a6)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818eea60)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff818ff853)
Location: include/net/dst.h:227
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8190a3b3)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f891)
Location: include/net/dst.h:227
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913893)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915a46)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949929)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff819624f5)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819749e5)
Location: include/net/dst.h:227
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
In net/ipv4/route.c (ffffffff8191091e)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819174db)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191c1f7)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff8192d5e8)
Location: include/net/dst.h:227
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8193865b)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193dcb1)
Location: include/net/dst.h:227
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81942043)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff819441f6)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bb88)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b5ea)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81997502)
Location: include/net/dst.h:227
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819aa605)
Location: include/net/dst.h:227
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
In net/ipv4/route.c (ffffffff81972b6e)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81979423)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197e523)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81990f15)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819998c2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a20ce)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6642)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a87b9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d28c9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4b21)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a034e9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a17953)
Location: include/net/dst.h:216
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
In net/ipv4/route.c (ffffffff819a94bc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819afc82)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4ecf)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819c7af5)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d02b9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7afe)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc4c2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df469)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a09200)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bb0a)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a0b9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a4e8d7)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81a93216)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a99c63)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9f0cb)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81ab48c2)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81abc7a8)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac51be)
Location: include/net/dst.h:215
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca570)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc9d9)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8d5b)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fa91)
Location: include/net/dst.h:215
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f808)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/route.c (ffffffff81a9d097)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3bb3)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa900b)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81abf976)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7f08)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0b4e)
Location: include/net/dst.h:215
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad64d0)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad89b2)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05b2b)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e377)
Location: include/net/dst.h:215
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e25c)
Location: include/net/dst.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/route.c (ffffffff81a86361)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ee86)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a94181)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81aa9c86)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ab37a0)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abd076)
Location: include/net/dst.h:218
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac154a)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac38d1)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af13ae)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bdc2)
Location: include/net/dst.h:218
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ca92)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/route.c (ffffffff81b4269e)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49da8)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4f5ea)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81b6600b)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81b705ae)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79f15)
Location: include/net/dst.h:218
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e5ca)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81ddd)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb151e)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0132)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2be7)
Location: include/net/dst.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (0)
Location: include/net/dst.h:218
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
In net/ipv4/route.c (ffffffff81ccf60e)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd72e1)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cdcf85)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81cf42c9)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81cffb3c)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a1e8)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e56b)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1222e)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44bd8)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81d774df)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b730)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (0)
Location: include/net/dst.h:219
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
In net/ipv4/route.c (ffffffff81e8f7fe)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81e97902)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9d9f5)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8c89)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ec4bdc)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf648)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed402b)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed801e)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0de78)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43d6f)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f5975c)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (0)
Location: include/net/dst.h:219
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
In net/ipv4/route.c (ffffffff81eedf04)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6142)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81efc169)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81f17129)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81f23535)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2ac08)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e304)
Location: include/net/dst.h:233
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f3304b)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f370e0)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6db28)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa354d)
Location: include/net/dst.h:233
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb940d)
Location: include/net/dst.h:233
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (0)
Location: include/net/dst.h:233
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
In net/ipv4/route.c (ffffffff81fb2061)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81fba0de)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fc00c9)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81fdc5e4)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fed99c)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_delack_max
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef827)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3163)
Location: include/net/dst.h:226
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff919b)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd1dd)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034278)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff82070537)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff820869b1)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (0)
Location: include/net/dst.h:226
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
In net/ipv4/route.c (ffff800010c58ebc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffff800010c60330)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c65624)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffff800010c79164)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c828ac)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a9fc)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f62c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92d38)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2518)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7da4)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffff800010cfb07c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffff800010d12740)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (c0d68c30)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (c0d6fe0c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d75294)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (c0d891dc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d91ecc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (c0d9bad8)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (c0d9f404)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (c0da1764)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdf0c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (c0de18a8)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (c0e01adc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (c0e180d0)
Location: include/net/dst.h:216
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
In net/ipv4/route.c (c000000000d5ad10)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (c000000000d63250)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69a48)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (c000000000d83fcc)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8e518)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9922c)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e4a0)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (c000000000da2f74)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddc44)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (c000000000df7e3c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (c000000000e225a0)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (c000000000e3ebd4)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffe0007c2e98)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffe0007c85c8)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cce3c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffe0007dd6c4)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4b70)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebbd4)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef894)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f24d6)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817986)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082837e)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffe000845bbc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffe000858a6c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff8194932c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff8194faf2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81954d3f)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81967965)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81970129)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197796e)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c332)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f2d9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8fa0)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb19a)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff819d9749)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819edf67)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81902e1c)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819095e2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190e82f)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff81921455)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81929bf9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193142e)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935df2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938d99)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a60)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977f8a)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81996509)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819aad27)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff819b3afc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819ba2c2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bf50f)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819d2135)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819da8f9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e213e)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6b02)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9aa9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13840)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25c1a)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a441c9)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a589e7)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff819bd1cc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819c3bb2)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8e8f)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_input.c (ffffffff819dbcd5)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e4583)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ebe8e)
Location: include/net/dst.h:216
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f07cc)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3855)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e210)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a310ba)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fe6a)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a64ba7)
Location: include/net/dst.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
</details>
</li>
</ul>

## Differences
