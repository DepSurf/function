# Function: <code>skb_dst_force</code>

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
Location: include/net/dst.h:316
Inline: True
```
```
In net/core/sock.c (ffffffff81702f4a)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817061cd)
Location: include/net/dst.h:316
Inline: True
```
```
In net/core/dev.c (ffffffff817197fe)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81725b2a)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817528d1)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817574f6)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff8175b41a)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff8178e455)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b3867)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbf74)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc25c)
Location: include/net/dst.h:316
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
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
Location: include/net/dst.h:313
Inline: True
```
```
In net/core/sock.c (ffffffff8176840d)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176cbd1)
Location: include/net/dst.h:313
Inline: True
```
```
In net/core/dev.c (ffffffff817858e7)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8178f5d8)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817be9f5)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817c37d6)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817c771f)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff817fba4b)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823203)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81828b99)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8182917d)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
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
Location: include/net/dst.h:313
Inline: True
```
```
In net/core/sock.c (ffffffff8179544d)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81799da1)
Location: include/net/dst.h:313
Inline: True
```
```
In net/core/dev.c (ffffffff817b2edb)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817bce88)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817ee2af)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817f324c)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817f720f)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdf34)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/icmp.c (ffffffff8182c98f)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854b53)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a579)
Location: include/net/dst.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ab5d)
Location: include/net/dst.h:313
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
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff817b3a09)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b9310)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff817d06a9)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817db5cc)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8180e3d3)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e349)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187869a)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e4cc)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ed13)
Location: include/net/dst.h:319
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
In drivers/net/loopback.c (ffffffff816f7421)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8182d7a9)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831c1f)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff8184a0a6)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81855d98)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8188d8c4)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff818967a6)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb4c1)
Location: include/net/dst.h:334
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd01a)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff818cd9a8)
Location: include/net/dst.h:334
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8fa3)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff429)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffdd9)
Location: include/net/dst.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff8194fba6)
Location: include/net/dst.h:334
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
In drivers/net/loopback.c (ffffffff817345b6)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81877b6e)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187c0cf)
Location: include/net/dst.h:317
Inline: True
```
```
In net/core/dev.c (ffffffff81894288)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818a12b9)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff818e14d1)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff818eaac4)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910f7a)
Location: include/net/dst.h:317
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e73)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81923e4c)
Location: include/net/dst.h:317
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa1f)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f77)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819568e9)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a4a)
Location: include/net/dst.h:317
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
In drivers/net/loopback.c (ffffffff8175770e)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8189805b)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189c92f)
Location: include/net/dst.h:317
Inline: True
```
```
In net/core/dev.c (ffffffff818b4ca6)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818c3c19)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8190e07d)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81917847)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f5e4)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941630)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81952c28)
Location: include/net/dst.h:317
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198303f)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a76c)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b549)
Location: include/net/dst.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff819df574)
Location: include/net/dst.h:317
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
In drivers/net/loopback.c (ffffffff81793ec5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818e25cd)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e7937)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffff8190162c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8191352c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8196fb2d)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81979f4b)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39c5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c31)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff819b74ac)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecc4f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5372)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6a4d)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e11e)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (ffffffff817b79f5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8191479f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81919d19)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffff8193395a)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81945b8c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819a656f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff819b08ab)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6c7)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc9f1)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff819ee1ac)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23c5f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c022)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d6b5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d6f)
Location: include/net/dst.h:307
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
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e66c8)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb705)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81a08601)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a1620d)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f900)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a9a73b)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7876)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ad0)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81adbf70)
Location: include/net/dst.h:306
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15c6b)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e4d9)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fe6c)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81b80104)
Location: include/net/dst.h:306
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
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e5fb8)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb425)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81a09baf)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a16e6f)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a998f0)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81aa4694)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad324e)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a20)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81ae8acc)
Location: include/net/dst.h:306
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b240db)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cda9)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e77c)
Location: include/net/dst.h:306
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f287)
Location: include/net/dst.h:306
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
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819ccbf8)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1935)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff819f0540)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff819fdb17)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c00)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a8f789)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe2ee)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a7f)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81ad3d87)
Location: include/net/dst.h:309
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d0b)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a9ec)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c489)
Location: include/net/dst.h:309
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec47)
Location: include/net/dst.h:309
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
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81a7c338)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81505)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81aa196e)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf0e4)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f12e)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9c9)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bde7)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e443)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81b92a47)
Location: include/net/dst.h:310
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd585f)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf010)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0d88)
Location: include/net/dst.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3ac)
Location: include/net/dst.h:310
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
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81bf00b3)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf51d5)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81c19a9a)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e5a)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb86e)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81cd7824)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0bcfa)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e3c6)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81d24068)
Location: include/net/dst.h:311
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c09f)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75d74)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c4f)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81de9aa0)
Location: include/net/dst.h:311
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
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81d9c2cf)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da36f5)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81dcaa4f)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa3a)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6be)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81e97ea2)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0c1c)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3e76)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81eeb6f8)
Location: include/net/dst.h:305
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f373ff)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81f424b4)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f445d2)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd1e0)
Location: include/net/dst.h:305
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
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81e0ab17)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e122e9)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81e3b660)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81e4b7aa)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81ee970e)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81ef66ff)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f303dc)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32e6e)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81f4b02b)
Location: include/net/dst.h:319
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96dbb)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1ce4)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3db8)
Location: include/net/dst.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff8201df90)
Location: include/net/dst.h:319
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
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81ec7507)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf4a9)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (ffffffff81ef9a1b)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81f0a4ca)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff81fad47e)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff81fba68f)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff626b)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8fbe)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff82011135)
Location: include/net/dst.h:312
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82064156)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f12a)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820710e5)
Location: include/net/dst.h:312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffff820ecf70)
Location: include/net/dst.h:312
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
In drivers/net/loopback.c (ffff8000109d01f8)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffff800010bad5b4)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb401c)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffff800010bd1ab8)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffff800010be7600)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffff800010c55df0)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffff800010c60ed4)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8da7c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f95c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffff800010ca3d10)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0ec0)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaad4)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec06c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffff800010d50e04)
Location: include/net/dst.h:307
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
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c0ccb1b0)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd0c30)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (c0cec694)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c0cfd728)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (c0d657ec)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (c0d70874)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (c0d9c7a8)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea18)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (c0db09a4)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0dea1f8)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c0df2ae8)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4014)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (c0e51978)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (c000000000a8f160)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c000000000c82e30)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c86758)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/dev.c (c000000000caff60)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c000000000cc5b70)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (c000000000d5654c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (c000000000d641a0)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b30c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e980)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (c000000000db7720)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000e03344)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c000000000e0e76c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10130)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (c000000000e88cc0)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (ffffffe00061cc8e)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffe00073f7d0)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe0007440c4)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffe00075beb4)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffe0007698ac)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffe0007c012c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffe0007c9092)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee02c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc9e)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffe0007ffbb0)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082faca)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffe00083864a)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839950)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/seg6_local.c (ffffffe000889114)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (ffffffff8177c4cd)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818b479f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b9d19)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffff818d395a)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818e5b5c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819463df)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff8195071b)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a537)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c861)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff8198df4c)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c32ef)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb6b2)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccd45)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a243ff)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (ffffffff8175c27d)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8186e6ef)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81873c69)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffff8188d7ea)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8189f99c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff818ffecf)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff8190a20b)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933ff7)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936321)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81947a0c)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819800df)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819884a2)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989b35)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff819e11bf)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (ffffffff817ac875)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8190579f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190ad19)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffff8192495a)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81936b8c)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8199756f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff819baeeb)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d07)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7031)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff819f87ec)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dd6f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36132)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a377c5)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee7f)
Location: include/net/dst.h:307
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
In drivers/net/loopback.c (ffffffff817c6805)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819267ad)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192be19)
Location: include/net/dst.h:307
Inline: True
```
```
In net/core/dev.c (ffffffff81945df6)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81958342)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff819ba24f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_options.c (ffffffff819c47f9)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee067)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0cff)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/icmp.c (ffffffff81a02b5a)
Location: include/net/dst.h:307
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3954f)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41aa8)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a43175)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bc03)
Location: include/net/dst.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
</details>
</li>
</ul>

## Differences
