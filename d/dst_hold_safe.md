# Function: <code>dst_hold_safe</code>

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
In net/core/sock.c (ffffffff81703bb7)
Location: include/net/dst.h:332
Inline: True
Inline callers:
  - net/core/sock.c:sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cbd3)
Location: include/net/dst.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f305)
Location: include/net/dst.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8178998e)
Location: include/net/dst.h:332
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff817e42e4)
Location: include/net/dst.h:332
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f05e6)
Location: include/net/dst.h:332
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff8176a656)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec135)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec809)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff817f7099)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81852621)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860cb4)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
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
In net/core/sock.c (ffffffff8179774d)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b42b)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d0f9)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f4a3)
Location: include/net/dst.h:329
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
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
In net/core/sock.c (ffffffff817b5374)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/route.c (ffffffff81812ac7)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff81817646)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bf15)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d915)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81846fc5)
Location: include/net/dst.h:335
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8184dd9b)
Location: include/net/dst.h:335
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8188ee71)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffffffff8189d542)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5a25)
Location: include/net/dst.h:335
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
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
In drivers/net/loopback.c (ffffffff816f7432)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8182d7f0)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831c30)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff8184a0ba)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81855da9)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8188d8d5)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81892107)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff81896884)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b999a)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd02b)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff818c6a25)
Location: include/net/dst.h:323
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cda86)
Location: include/net/dst.h:323
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8fba)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff449)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffde8)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/addrconf.c (ffffffff819104c1)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819201cc)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938791)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff8194fbba)
Location: include/net/dst.h:323
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff817345c7)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81877b80)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187c0e0)
Location: include/net/dst.h:306
Inline: True
```
```
In net/core/dev.c (ffffffff8189429c)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818a12cb)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff818e14e3)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e61b0)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff818eab5c)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191023a)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e84)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8191c3f5)
Location: include/net/dst.h:306
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81923ea2)
Location: include/net/dst.h:306
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa36)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f7f)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81956936)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff8197440e)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991600)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a5e)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff8175771f)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8189806d)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189c940)
Location: include/net/dst.h:306
Inline: True
```
```
In net/core/dev.c (ffffffff818b4cba)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818c3c2b)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8190e08f)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819130c8)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff819178de)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f659)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941641)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8194a9c5)
Location: include/net/dst.h:306
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81952c7e)
Location: include/net/dst.h:306
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983053)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a9a2)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b5e7)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff819a9018)
Location: include/net/dst.h:306
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c7e70)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff819df58c)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff81793ed7)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818e25de)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e7949)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffff81901640)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8191353e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8196fbf4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819756b7)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff81979f60)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39d7)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c42)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819af835)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b74ca)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eccc2)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5647)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6b10)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff81a15103)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36965)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e133)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff817b7a07)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819147b0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81919d2b)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffff8193396e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81945b9e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819a6573)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819ac0d3)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff819b08c0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6d9)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dca02)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819e64c5)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ee1ca)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23cd2)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c2f7)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d778)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff81a4bcde)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d485)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d84)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff8187eb47)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e66d9)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb716)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81a08615)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a1621f)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f908)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a93f44)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81a9a750)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5d55)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ae1)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ad28d5)
Location: include/net/dst.h:294
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adbf8e)
Location: include/net/dst.h:294
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15cf2)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e76f)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ff71)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81b40e10)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67085)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81b80119)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff8188d0c7)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e5fc9)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb436)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81a09bc3)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a16e80)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a998f8)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a9de80)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81aa46a8)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1be5)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a31)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ade985)
Location: include/net/dst.h:294
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae8aea)
Location: include/net/dst.h:294
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24162)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d0b1)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e881)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81b4f8c6)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75660)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f29c)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff8186fa07)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819ccc09)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1946)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff819f0554)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff819fdb28)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c08)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a88da4)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81a8f79d)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcbf5)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a90)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ac9885)
Location: include/net/dst.h:297
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad3da5)
Location: include/net/dst.h:297
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d92)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1acf6)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c5df)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81b3d5f6)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64090)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec5c)
Location: include/net/dst.h:297
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff818fffa7)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81a7c349)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81516)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81aa1982)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf0f5)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f132)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81b43514)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9dd)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79985)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e454)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81b880f5)
Location: include/net/dst.h:298
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b92a65)
Location: include/net/dst.h:298
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5910)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf263)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0f1d)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81c05686)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bb50)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3c1)
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In drivers/net/loopback.c (ffffffff81a51a6a)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81bf00c9)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf525a)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81c19ab5)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e70)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb879)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81ccffd3)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81cd7841)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09717)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e442)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81d19345)
Location: include/net/dst.h:299
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d2407d)
Location: include/net/dst.h:299
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c16a)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75fcd)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c6c)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81d9fc84)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc90cf)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81de9ab5)
Location: include/net/dst.h:299
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In drivers/net/loopback.c (ffffffff81bdacaa)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81d9c2e5)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da377a)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81dcaa6a)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa50)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6c9)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81e901b7)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81e97ebf)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece9e7)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3ef2)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81edfaf5)
Location: include/net/dst.h:293
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb70d)
Location: include/net/dst.h:293
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f374ca)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4270d)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f445ef)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81f6ed24)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99f0f)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd1f5)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In drivers/net/loopback.c (ffffffff81c31761)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81e0ab84)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e12373)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81e3b67e)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81e4b918)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9719)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81eee92a)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81ef671c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d9a1)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32eef)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81f3ef35)
Location: include/net/dst.h:307
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4b040)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96e19)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1f19)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3dd5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff81fcebb0)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa8e5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff8201dfa5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In drivers/net/loopback.c (ffffffff81ce45e1)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81ec7574)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf533)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81ef9a39)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81f0a638)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81fad623)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81fb2a8a)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
```
```
In net/ipv4/ip_options.c (ffffffff81fba6ac)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2631)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff903f)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff82005295)
Location: include/net/dst.h:300
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8201114a)
Location: include/net/dst.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820641b4)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f147)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82071102)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffff8209c410)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c85d5)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff820ecf85)
Location: include/net/dst.h:300
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In drivers/net/loopback.c (ffff8000109d0264)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffff800010bad5c4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb407c)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffff800010bd1ac4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffff800010be7610)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffff800010c55df4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5bf8c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffff800010c60ee4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb24)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f96c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffff800010c9996c)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3d38)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f54)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffff800010ceb0d4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec07c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffff800010d111f8)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d371ac)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffff800010d50e14)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (c0ab8480)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c0ccb1c4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd0c3c)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (c0cec6a4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c0cfd73c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (c0d657f4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c0d6b86c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (c0d7088c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (c0d9c258)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea2c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (c0da9d84)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (c0db09d0)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0dea29c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c0df2e9c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df41dc)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (c0e1557c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (c0e39de0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (c0e51990)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (c000000000a8f1f0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c000000000c82e44)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c86764)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (c000000000caff70)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c000000000cc5b84)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (c000000000d56554)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c000000000d5e308)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (c000000000d641b8)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97314)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e994)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (c000000000dabfc0)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db7744)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000e03398)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c000000000e0ec80)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e103d8)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (c000000000e38530)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (c000000000e67ea4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (c000000000e88cdc)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffe00061ccf0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffe00073f7de)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe0007440da)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffe00075bec2)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffe0007698ba)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0130)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffe0007c5210)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffe0007c909e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee07a)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efcac)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffe0007f84da)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0007ffbbe)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fb04)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffe00083890a)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839ad0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/route.c (ffffffe000854ef8)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087323c)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffe000889120)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff8177c4df)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818b47b0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b9d2b)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffff818d396e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818e5b6e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819463e3)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff8194bf43)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff81950730)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a549)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c872)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81986335)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198df6a)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3362)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb987)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cce08)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff819eb36e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cb15)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81a24414)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff8175c28f)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8186e700)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81873c7b)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffff8188d7fe)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8189f9ae)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff818ffed3)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81905a33)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff8190a220)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934009)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936332)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8193fdf5)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81947a2a)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980152)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81988777)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989bf8)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff819a812e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c98d5)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff819e11d4)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff817ac887)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819057b0)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190ad2b)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffff8192496e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81936b9e)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81997573)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819b6713)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff819baf00)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d19)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7042)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819f0b05)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f880a)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dde2)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36407)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37888)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff81a55dee)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77595)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee94)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In drivers/net/loopback.c (ffffffff817c6817)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819267be)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192be2b)
Location: include/net/dst.h:295
Inline: True
```
```
In net/core/dev.c (ffffffff81945e0a)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81958354)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819ba253)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819bff45)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_options.c (ffffffff819c480d)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee079)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0d10)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819fc355)
Location: include/net/dst.h:295
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02b78)
Location: include/net/dst.h:295
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a395c2)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41d58)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a43236)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/route.c (ffffffff81a61e1a)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83de1)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bc18)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
</details>
</li>
</ul>

## Differences
