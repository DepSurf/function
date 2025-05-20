# Function: <code>nf_hook</code>

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
In net/ipv4/ip_output.c (ffffffff8175e17c)
Location: include/linux/netfilter.h:192
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc3c7)
Location: include/linux/netfilter.h:192
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/output_core.c (ffffffff8180063b)
Location: include/linux/netfilter.h:192
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff817ca3ac)
Location: include/linux/netfilter.h:185
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/xfrm/xfrm_output.c (ffffffff818292f1)
Location: include/linux/netfilter.h:185
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/output_core.c (ffffffff81871d55)
Location: include/linux/netfilter.h:185
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff817f4f70)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff817f6960)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817fa973)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff8182393e)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8182a76b)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81848260)
Location: include/linux/netfilter.h:189
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e6e3)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184eb00)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8185acd1)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff818658a9)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8186775d)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8187e6e5)
Location: include/linux/netfilter.h:189
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818867f0)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8188a9a5)
Location: include/linux/netfilter.h:189
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189c4f0)
Location: include/linux/netfilter.h:189
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f591)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189faf0)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff818a62f0)
Location: include/linux/netfilter.h:189
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff8181540a)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81816d4e)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181adaa)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff818443d2)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184b98b)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818693e0)
Location: include/linux/netfilter.h:180
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff8187213d)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff818726c8)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8187eae8)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8188a0b6)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8188beed)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff818a4725)
Location: include/linux/netfilter.h:180
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818acb4e)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818b0d95)
Location: include/linux/netfilter.h:180
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c28c0)
Location: include/linux/netfilter.h:180
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5ad9)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c6128)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff818ccd3f)
Location: include/linux/netfilter.h:180
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff818945dd)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81895f14)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81899d8a)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff818c3d10)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cb5fb)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818e9a20)
Location: include/linux/netfilter.h:182
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2b1d)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f30c8)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffb86)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8190b250)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8190d1dd)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819270d5)
Location: include/linux/netfilter.h:182
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f3ab)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819333d5)
Location: include/linux/netfilter.h:182
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944660)
Location: include/linux/netfilter.h:182
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948e0b)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819494c8)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81951b1f)
Location: include/linux/netfilter.h:182
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int nf_hook(u_int8_t pf, unsigned int hook, struct net *net, struct sock *sk, struct sk_buff *skb, struct net_device *indev, struct net_device *outdev, int (*okfn)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff818e87ef)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff818ea211)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ee21a)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81919918)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921ad0)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819400d0)
Location: include/linux/netfilter.h:193
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81949465)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819499d8)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8195677f)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819636f4)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff819645dd)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8197f480)
Location: include/linux/netfilter.h:193
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81987d83)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8198bdc0)
Location: include/linux/netfilter.h:193
Inline: True
Direct callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff8199e010)
Location: include/linux/netfilter.h:193
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1eee)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a25a8)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff819ab0af)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff8195ff70-ffffffff81960055: nf_hook (STB_LOCAL)
ffffffff8197f480-ffffffff8197f541: nf_hook.constprop.32 (STB_LOCAL)
ffffffff8198bdc0-ffffffff8198be81: nf_hook.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int nf_hook(u_int8_t pf, unsigned int hook, struct net *net, struct sock *sk, struct sk_buff *skb, struct net_device *indev, struct net_device *outdev, int (*okfn)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819153ee)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81917668)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191b9e7)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819481f3)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819508f0)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819709e5)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b12a)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b698)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b257)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819986b4)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81999f1d)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819b5a50)
Location: include/linux/netfilter.h:193
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff819be6d7)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819c26a0)
Location: include/linux/netfilter.h:193
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff819d39b0)
Location: include/linux/netfilter.h:193
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8b43)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d9218)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff819e1bcc)
Location: include/linux/netfilter.h:193
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81914cb0-ffffffff81914cbd: nf_hook.part.21 (STB_LOCAL)
ffffffff81994d00-ffffffff81994e3b: nf_hook (STB_LOCAL)
ffffffff81998f90-ffffffff81998f9d: nf_hook.part.26 (STB_LOCAL)
ffffffff819b5a50-ffffffff819b5b44: nf_hook.constprop.32 (STB_LOCAL)
ffffffff819c26a0-ffffffff819c2794: nf_hook.constprop.39 (STB_LOCAL)
ffffffff819d39b0-ffffffff819d3aab: nf_hook.constprop.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81977923)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819795c7)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197dcc0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819ac42c)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b51cc)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819d8bb0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e463b)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4bca)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819f678c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a036b7)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05e6e)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a24530)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a2d12c)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a31560)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a42c70)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a4739f)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47a9a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a509a0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff819d8bb0-ffffffff819d8cab: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a24530-ffffffff81a24624: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a31560-ffffffff81a31654: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a42c70-ffffffff81a42d6b: nf_hook.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819ae2b3)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819afedc)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4660)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819e2f64)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819ebefc)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a10681)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b64b)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bbea)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d403)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a287)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c9de)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a5afb0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a63c7a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a680b0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a5b1)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7df4f)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e64a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a875c0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81a5afb0-ffffffff81a5b0a4: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a680b0-ffffffff81a681a4: nf_hook.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff81a987a0)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81a99e01)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9e763)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81ad0847)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad9c6a)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b01e91)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c6e8)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0caa3)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20095)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2fa17)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b3207c)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81b53e99)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c6f9)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b6190d)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b75e81)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78a9d)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b790ea)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81b829ce)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81aa2720)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3d6a)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa86a3)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81adc857)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ae66bb)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b0ff72)
Location: include/linux/netfilter.h:205
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aa08)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1add3)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e9aa)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e443)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b40c7e)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81b6248e)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b6af39)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b7008f)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b84bf2)
Location: include/linux/netfilter.h:205
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87a0d)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b8806a)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81b92030)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81a8d743)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81a8edd5)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a91d93)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81ac7896)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad198b)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81afdb62)
Location: include/linux/netfilter.h:205
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b086b8)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b08a99)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c724)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cc2f)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e51e)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81b50518)
Location: include/linux/netfilter.h:205
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5924b)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b5d848)
Location: include/linux/netfilter.h:205
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b73882)
Location: include/linux/netfilter.h:205
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b766bd)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76da9)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81b812c0)
Location: include/linux/netfilter.h:205
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81b48913)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81b4a009)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4d1a3)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81b860ea)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81b905bb)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bbfc72)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb5c8)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcb999)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81be1094)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2da9)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf483e)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81c17888)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c2085a)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81c24cc8)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3de52)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c4114d)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41859)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47dd8)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81c49401)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff81c4d2e0)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81cd5d11)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7601)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cda951)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81d16a30)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81d22eb7)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d54604)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61075)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d6149d)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77f5a)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b8bc)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d610)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81db36b7)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbd5da)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81dc2fbc)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc494)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf8d6)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81de006d)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de7274)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81de8bb0)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff81ded7f9)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81e961c1)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81e97c54)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9b151)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81edd1df)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81eea3b7)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f1e7f4)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b965)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2bdbd)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81f447fa)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81f598c6)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b700)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81f83047)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8db19)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81f93a0c)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fad514)
Location: include/linux/netfilter.h:211
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1ba6)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb23ad)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fba106)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbad0)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff81fc1629)
Location: include/linux/netfilter.h:211
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81ef4a01)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81ef649e)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef9b71)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81f3c42f)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81f49ce7)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f7e2f4)
Location: include/linux/netfilter.h:212
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b7bf)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8ba5d)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3ffb)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81fb957a)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb4d0)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81fe3347)
Location: include/linux/netfilter.h:212
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fee2f2)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81ff4366)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200dcd4)
Location: include/linux/netfilter.h:212
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012290)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012abd)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a83d)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201c3cf)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff820225a9)
Location: include/linux/netfilter.h:212
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffff81fb8991)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81fba431)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbda9d)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff82002559)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff8200fe07)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82043c74)
Location: include/linux/netfilter.h:223
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff820530bf)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8205335d)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8207132b)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff82086b40)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff820888e0)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff820b1267)
Location: include/linux/netfilter.h:223
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bbebd)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff820c0f37)
Location: include/linux/netfilter.h:223
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dc894)
Location: include/linux/netfilter.h:223
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1400)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1c1d)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e97fd)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820eb39f)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff820f16c9)
Location: include/linux/netfilter.h:223
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffff800010c5e7ac)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffff800010c6061c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c64db8)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffff800010c97d24)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca16b0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffff800010cc9920)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd78c4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7eb8)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffff800010cec484)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffff800010cfb250)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfdd20)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffff800010d20388)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffff800010d29d3c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffff800010d2de9c)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d42ea8)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffff800010d4930c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49b08)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffff800010d53e94)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffff800010d20388-ffff800010d20424: nf_hook.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (c0d6de64)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (c0d6ff60)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d74a18)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (c0da5b38)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (c0dae804)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (c0dd7464)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_input.c (c0de13d4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c0de19a0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (c0df4380)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c0e01d8c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e0578c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (c0e251c4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (c0e2db4c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c0e338dc)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (c0e468b4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_input.c (c0e4a6d8)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c0e4ae18)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (c0e54654)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (c000000000d610a8)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (c000000000d63618)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69130)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (c000000000da8ca0)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (c000000000db4c38)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (c000000000de7eb4)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (c000000000df7790)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c000000000df7fc0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (c000000000e105d0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c000000000e227dc)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e25f7c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (c000000000e4ec0c)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5ab9c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c000000000e60c6c)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7a434)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e844)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c000000000e7f2a0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (c000000000e8c7f4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_input.c (ffffffe0007c6e50)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffe0007c87e0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cc6d0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffe0007f6122)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fe1e6)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffe00081e61e)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827fa6)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082846c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffe000839b74)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffe000845d5a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe0008481b8)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffe0008628c2)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086a57a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffe00086ec2e)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087ff54)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffe00088280e)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882eb4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffe00088b9d8)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff8194e123)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff8194fd4c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819544d0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81982dd4)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198bd2c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819b0091)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bacdb)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb27a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819cca93)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d9917)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dc06e)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819fa640)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a0330a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a07740)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a19c41)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d5df)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1dcda)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a26c50)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff819fa640-ffffffff819fa734: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a07740-ffffffff81a07834: nf_hook.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81907c13)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff8190983c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190dfc0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff8193c894)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819457ec)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196c6c1)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977acb)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197806a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81989883)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819966d7)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998e2e)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819b7400)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff819c00ca)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff819c4500)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff819d6a01)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da39f)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819daa9a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff819e3a10)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff819b7400-ffffffff819b74f4: nf_hook.constprop.0 (STB_LOCAL)
ffffffff819c4500-ffffffff819c45f4: nf_hook.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819b88f3)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819ba51c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819beca0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819ed5a4)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f653c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a1a931)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a2575b)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25cfa)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37513)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a44397)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a46aee)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a650c0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a6dd8a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a721c0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a846c1)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a8805f)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a8875a)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a92800)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81a650c0-ffffffff81a651b4: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a721c0-ffffffff81a722b4: nf_hook.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819c2160)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819c3e0c)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8600)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819f7484)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a0073f)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a25774)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30bdd)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a311a0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42eaa)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a50042)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a52840)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a715f0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a7a3af)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7e7f0)
Location: include/linux/netfilter.h:209
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a90ff4)
Location: include/linux/netfilter.h:209
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94c7f)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a953b0)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a9e8e4)
Location: include/linux/netfilter.h:209
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81a715f0-ffffffff81a7172a: nf_hook.constprop.0 (STB_LOCAL)
ffffffff81a7e7f0-ffffffff81a7e92a: nf_hook.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
