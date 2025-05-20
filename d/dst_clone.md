# Function: <code>dst_clone</code>

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
In drivers/net/loopback.c (ffffffff815e98d9)
Location: include/net/dst.h:269
Inline: True
```
```
In net/core/sock.c (ffffffff81702f59)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81705bc5)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81719833)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81725b38)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817528df)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81757504)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff8175b45c)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8175c5b0)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81787e4e)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8178c30d)
Location: include/net/dst.h:269
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178e46b)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/ipmr.c (ffffffff817a73f0)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b25ed)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbf82)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc26a)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4b23)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff817d7b12)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6mr.c (ffffffff817f85f5)
Location: include/net/dst.h:269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In drivers/net/loopback.c (ffffffff81648029)
Location: include/net/dst.h:266
Inline: True
```
```
In net/core/sock.c (ffffffff8176841c)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176c895)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff817858fd)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8178f5e6)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817bea03)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817c37e4)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817c775e)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817c93b0)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff817f5583)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff817f993d)
Location: include/net/dst.h:266
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fba62)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818150e0)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823256)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff81828ba7)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8182918b)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff818351aa)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81846375)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6mr.c (ffffffff81867dd5)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In drivers/net/loopback.c (ffffffff81679149)
Location: include/net/dst.h:266
Inline: True
```
```
In net/core/sock.c (ffffffff8179545c)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81799a65)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff817b2ef1)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817bce96)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff817ee2bd)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff817f325a)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817f724e)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817f8f50)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdf44)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/udp.c (ffffffff8182664a)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8182a80d)
Location: include/net/dst.h:266
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8182c9a6)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818468a0)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854ba6)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a587)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ab6b)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81866ce8)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff818780d5)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6mr.c (ffffffff8189ac35)
Location: include/net/dst.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In drivers/net/loopback.c (ffffffff8168d8f8)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff817b3a18)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b9349)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff817d06c1)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817db5da)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/netfilter/nf_queue.c (ffffffff8180e3e1)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/ip_output.c (ffffffff81819370)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e357)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/udp.c (ffffffff81846da7)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184ba20)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818695c4)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff818786a7)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e4e7)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ea1d)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8188b397)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8189d2b4)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6mr.c (ffffffff818c156d)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81831895)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81897930)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff818c67d9)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cb690)
Location: include/net/dst.h:273
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e9c14)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffa8d)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8190c5c7)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff819448bd)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff8187bd85)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff818ebd5b)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8191c00d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921b73)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819402cd)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819566a3)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963ac8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff8199d5d7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff8189bfe5)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8191902b)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8194a5bf)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81950993)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8197014d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b199)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81998a72)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff819d4137)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff818e689d)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8197b02c)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819aecc4)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819b5275)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d9a00)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66ca)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a048df)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff81a42fde)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff819189e5)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819b199c)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819e59e1)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819ebfa3)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a10860)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d34a)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b4d0)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b3e)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff819ec830)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81a957b1)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1e0)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81ad5790)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ada048)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81b02299)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ef2a)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b30a8f)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b316a0)
Location: include/net/dst.h:244
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b747e3)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff819ec4f0)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81a6f3e8)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a9f841)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81aa6040)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81ae1d2e)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae6ab8)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81b1063e)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d7da)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6bf)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40290)
Location: include/net/dst.h:244
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83557)
Location: include/net/dst.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff819d29e0)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81a57cbb)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a8a781)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81a91200)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81acba01)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad1d88)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81afe24e)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c522)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d55d)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e8a0)
Location: include/net/dst.h:247
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b721ca)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81a82657)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81b10c86)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81b45671)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81b4c597)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81b8a291)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b909d8)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81bbf4de)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0e23)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf370d)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c6f)
Location: include/net/dst.h:247
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c67a)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81bf7047)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81c97e04)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81cd238c)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81cd9be7)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81d1db74)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d21ecc)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81d54278)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77d0e)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d88ae4)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da90)
Location: include/net/dst.h:248
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa57)
Location: include/net/dst.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81da5fb7)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81e53da4)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81e929bc)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81e9a377)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81ee4c33)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ee932c)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81f1e458)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444a5)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f568e4)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bbc0)
Location: include/net/dst.h:242
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fac766)
Location: include/net/dst.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81e150a7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81eaf624)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81ef115d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81ef8cd7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81f445f4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81f48c5c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/ipmr.c (ffffffff81f7df48)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3c8d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb62e3)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb980)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200cf06)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81ed2447)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81f720a4)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81fb52ad)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81fbcbf7)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8200a5ce)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8200edbc)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/xfrm/xfrm_output.c (ffffffff82070fba)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff820839a3)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088db7)
Location: include/net/dst.h:249
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dbed6)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffff800010bb4790)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffff800010c62358)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffff800010c9e308)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a84)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb488)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffff800010cec190)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5d8)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffff800010d43e20)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (c0cd0544)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c0d71b48)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (c0da9110)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c0dae8c4)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd597c)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (c0df409c)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0e039f0)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (c0e45bd4)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (c000000000c87a88)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c000000000d65618)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (c000000000db0474)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c000000000db4d10)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de8110)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (c000000000e102a0)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e240dc)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (c000000000e78978)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffe000742504)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f1e)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffe0007f81c2)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffe0007fe29c)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081e7b6)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffe0008399b8)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe000846e98)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffe00087e9ba)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff818b89e5)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8195180c)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81985851)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8198bdd3)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b0270)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9da)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819dab60)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff81a191ce)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff81872935)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8190b2fc)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8193f311)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81945893)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196c8a0)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819897ca)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81997920)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff819d5f8e)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff819099e5)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819bbfdc)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819f0021)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819f65e3)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1ab10)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a3745a)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a455e0)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff81a83c4e)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/skbuff.c (ffffffff8192aae5)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819c58ec)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819fa8a8)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81a007f3)
Location: include/net/dst.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a25970)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42dea)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a512b0)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6mr.c (ffffffff81a9056e)
Location: include/net/dst.h:245
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
</ul>

## Differences
