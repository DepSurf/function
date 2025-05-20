# Function: <code>skb_dst_is_noref</code>

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
In drivers/net/loopback.c (ffffffff815e9883)
Location: include/linux/skbuff.h:787
Inline: True
```
```
In net/core/sock.c (ffffffff8170225e)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_queue_rcv_skb
  - net/core/sock.c:sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817061cd)
Location: include/linux/skbuff.h:787
Inline: True
```
```
In net/core/dev.c (ffffffff817197fe)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81725b2a)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817528d1)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817574f6)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff8175b41a)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d2f3)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f2f8)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81789981)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff8178e455)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b3867)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbf74)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc25c)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/udp.c (ffffffff817e42d7)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f232a)
Location: include/linux/skbuff.h:787
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff81647fd3)
Location: include/linux/skbuff.h:875
Inline: True
```
```
In net/core/sock.c (ffffffff81769464)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176cbd1)
Location: include/linux/skbuff.h:875
Inline: True
```
```
In net/core/dev.c (ffffffff817858e7)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8178f5d8)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817be9f5)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817c37d6)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817c771f)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec12a)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec7fc)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff817f708c)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff817fba4b)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823203)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81828b99)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8182917d)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/udp.c (ffffffff81852614)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860ca9)
Location: include/linux/skbuff.h:875
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In drivers/net/loopback.c (ffffffff816790f3)
Location: include/linux/skbuff.h:889
Inline: True
```
```
In net/core/sock.c (ffffffff81796374)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81799da1)
Location: include/linux/skbuff.h:889
Inline: True
```
```
In net/core/dev.c (ffffffff817b2edb)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817bce88)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817ee2af)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817f324c)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817f720f)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdf34)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181af28)
Location: include/linux/skbuff.h:889
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d0ec)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff8182c98f)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854b53)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a579)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ab5d)
Location: include/linux/skbuff.h:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
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
In drivers/net/loopback.c (ffffffff8168d8a2)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff817b455b)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b9310)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff817d06a9)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817db5cc)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8180e3d3)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81817631)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e349)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b6c3)
Location: include/linux/skbuff.h:842
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d908)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff8184dd49)
Location: include/linux/skbuff.h:842
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187869a)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e4cc)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ed13)
Location: include/linux/skbuff.h:842
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
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
In drivers/net/loopback.c (ffffffff816f7425)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8182c7ab)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831c23)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff8184a0a6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81855d9c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8188d8c8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff818967e4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb4c6)
Location: include/linux/skbuff.h:922
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd01e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff818cd9b3)
Location: include/linux/skbuff.h:922
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8fae)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff429)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffddd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff8194fbb1)
Location: include/linux/skbuff.h:922
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
In drivers/net/loopback.c (ffffffff817345ba)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8187691a)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187c0d3)
Location: include/linux/skbuff.h:926
Inline: True
```
```
In net/core/dev.c (ffffffff81894288)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818a12be)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff818e14d6)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff818eaac4)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910f7f)
Location: include/linux/skbuff.h:926
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e77)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81923e50)
Location: include/linux/skbuff.h:926
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa23)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f77)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819568ed)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a4e)
Location: include/linux/skbuff.h:926
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
In drivers/net/loopback.c (ffffffff81757712)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818987aa)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189c933)
Location: include/linux/skbuff.h:950
Inline: True
```
```
In net/core/dev.c (ffffffff818b4ca6)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818c3c1e)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8190e082)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81917847)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f5e8)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941634)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81952c2c)
Location: include/linux/skbuff.h:950
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983043)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a770)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b54d)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff819df578)
Location: include/linux/skbuff.h:950
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
In drivers/net/loopback.c (ffffffff81793eca)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818e2d51)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e793c)
Location: include/linux/skbuff.h:970
Inline: True
```
```
In net/core/dev.c (ffffffff8190162c)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81913531)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8196fb32)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81979f50)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39ca)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c35)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff819b74b0)
Location: include/linux/skbuff.h:970
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecc53)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5376)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6a52)
Location: include/linux/skbuff.h:970
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e123)
Location: include/linux/skbuff.h:970
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
In drivers/net/loopback.c (ffffffff817b79fa)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81914f31)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81919d1e)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffffffff8193395a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81945b91)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819a656f)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff819b08b0)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6cc)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc9f5)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff819ee1b0)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23c63)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c026)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d6ba)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d74)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (ffffffff8187eb35)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e8051)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb705)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81a08601)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a1620d)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f900)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a9a73b)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7876)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ad0)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81adbf70)
Location: include/linux/skbuff.h:998
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15c6b)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e4d9)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fe6c)
Location: include/linux/skbuff.h:998
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81b80104)
Location: include/linux/skbuff.h:998
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
In drivers/net/loopback.c (ffffffff8188d0b5)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e7cc1)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb425)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81a09baf)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a16e6f)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a998f0)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81aa4694)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad324e)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a20)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81ae8acc)
Location: include/linux/skbuff.h:1005
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b240db)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cda9)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e77c)
Location: include/linux/skbuff.h:1005
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f287)
Location: include/linux/skbuff.h:1005
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
In drivers/net/loopback.c (ffffffff8186f9f5)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819cdc91)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1935)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff819f0540)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff819fdb17)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c00)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a8f789)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe2ee)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a7f)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81ad3d87)
Location: include/linux/skbuff.h:1011
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d0b)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a9ec)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c489)
Location: include/linux/skbuff.h:1011
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec47)
Location: include/linux/skbuff.h:1011
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
In drivers/net/loopback.c (ffffffff818fff95)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81a7d471)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81505)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81aa196e)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf0e4)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f12e)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9c9)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bde7)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e443)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81b92a47)
Location: include/linux/skbuff.h:1023
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd585f)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf010)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0d88)
Location: include/linux/skbuff.h:1023
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3ac)
Location: include/linux/skbuff.h:1023
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
In drivers/net/loopback.c (ffffffff81a51a07)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81bf0ad1)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf51d5)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81c19a9a)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e5a)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb86e)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81cd7824)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0bcfa)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e3c6)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81d24068)
Location: include/linux/skbuff.h:1313
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c09f)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75d74)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c4f)
Location: include/linux/skbuff.h:1313
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81de9aa0)
Location: include/linux/skbuff.h:1313
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
In drivers/net/loopback.c (ffffffff81bdac47)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81d9c2cf)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da36f5)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81dcaa4f)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa3a)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6be)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81e97ea2)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0c1c)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3e76)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81eeb6f8)
Location: include/linux/skbuff.h:1155
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f373ff)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81f424b4)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f445d2)
Location: include/linux/skbuff.h:1155
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd1e0)
Location: include/linux/skbuff.h:1155
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
In drivers/net/loopback.c (ffffffff81c316eb)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81e0ab17)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e122e9)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81e3b660)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81e4b7aa)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81ee970e)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81ef66ff)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f303dc)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32e6e)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81f4b02b)
Location: include/linux/skbuff.h:1165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96dbb)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1ce4)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3db8)
Location: include/linux/skbuff.h:1165
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff8201df90)
Location: include/linux/skbuff.h:1165
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
In drivers/net/loopback.c (ffffffff81ce456b)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81ec7507)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf4a9)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81ef9a1b)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81f0a4ca)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81fad47e)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81fba68f)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff626b)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8fbe)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff82011135)
Location: include/linux/skbuff.h:1172
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82064156)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f12a)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820710e5)
Location: include/linux/skbuff.h:1172
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff820ecf70)
Location: include/linux/skbuff.h:1172
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
In drivers/net/loopback.c (ffff8000109d01fc)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffff800010badd30)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb401c)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffff800010bd1ab8)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffff800010be7604)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffff800010c55df0)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffff800010c60ed8)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8da80)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f960)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffff800010ca3d14)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0ec4)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaad8)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec070)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffff800010d50e08)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (c0ab846c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c0ccb834)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd0c30)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (c0cec694)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c0cfd728)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (c0d657ec)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (c0d70874)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (c0d9c7a8)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea18)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (c0db09a4)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0dea1f8)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c0df2ae8)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4014)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (c0e51978)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (c000000000a8f164)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c000000000c83728)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c86758)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (c000000000caff60)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c000000000cc5b74)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (c000000000d5654c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (c000000000d641a4)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b310)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e984)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (c000000000db7724)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000e03348)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c000000000e0e770)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10134)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (c000000000e88cc8)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (ffffffe00061cc90)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffe00073fe0a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe0007440d0)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffffffe00075beb4)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffe0007698b0)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffe0007c012c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffe0007c9094)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee02e)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efca2)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffe0007ffbb4)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082facc)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffe00083864c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839954)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffe000889116)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (ffffffff8177c4d2)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818b4f31)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b9d1e)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffffffff818d395a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818e5b61)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819463df)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81950720)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a53c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c865)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff8198df50)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c32f3)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb6b6)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccd4a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a24404)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (ffffffff8175c282)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8186ee81)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81873c6e)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffffffff8188d7ea)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8189f9a1)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff818ffecf)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff8190a210)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933ffc)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936325)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81947a10)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819800e3)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819884a6)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989b3a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff819e11c4)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (ffffffff817ac87a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81905f31)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190ad1e)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffffffff8192495a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81936b91)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8199756f)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff819baef0)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d0c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7035)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff819f87f0)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dd73)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36136)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a377ca)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee84)
Location: include/linux/skbuff.h:966
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
In drivers/net/loopback.c (ffffffff817c680a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81926f61)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192be1e)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/core/dev.c (ffffffff81945df6)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81958347)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819ba24f)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff819c47fd)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee06c)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0d03)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81a02b5e)
Location: include/linux/skbuff.h:966
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39553)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41aac)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4317a)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bc08)
Location: include/linux/skbuff.h:966
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
</details>
</li>
</ul>

## Differences
