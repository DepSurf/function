# Function: <code>dst_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff8175a6f5)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff8175c250)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff817840f0)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff817a78a0)
Location: include/net/dst.h:490
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b019a)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b5f7a)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc4ec)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c44b0)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ndisc.c (ffffffff817de100)
Location: include/net/dst.h:490
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e4fc0)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff817e8b40)
Location: include/net/dst.h:490
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f7f88)
Location: include/net/dst.h:490
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd1c0)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81800490)
Location: include/net/dst.h:490
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff8175c250-ffffffff8175c261: dst_output (STB_LOCAL)
ffffffff817840f0-ffffffff81784101: dst_output (STB_LOCAL)
ffffffff817c44b0-ffffffff817c44c1: dst_output (STB_LOCAL)
ffffffff817de100-ffffffff817de111: dst_output (STB_LOCAL)
ffffffff817e4fc0-ffffffff817e4fd1: dst_output (STB_LOCAL)
ffffffff817e8b40-ffffffff817e8b51: dst_output (STB_LOCAL)
ffffffff81800490-ffffffff818004a1: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff817c6ab5)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff817ca461)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff817f2b44)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81815580)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d0ca)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822f9a)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81829401)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81833e37)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ndisc.c (ffffffff8184c1a0)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81854a88)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81857380)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81867c78)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186caf0)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81871e01)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff817c84f0-ffffffff817c8501: dst_output (STB_LOCAL)
ffffffff817f1680-ffffffff817f1691: dst_output (STB_LOCAL)
ffffffff81831ce0-ffffffff81831cf1: dst_output (STB_LOCAL)
ffffffff8184c1a0-ffffffff8184c1b1: dst_output (STB_LOCAL)
ffffffff818532a0-ffffffff818532b1: dst_output (STB_LOCAL)
ffffffff81857380-ffffffff81857391: dst_output (STB_LOCAL)
ffffffff81871ba0-ffffffff81871bb1: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff817f65b5)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff817f9d48)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81823943)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81846d40)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184e98b)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818548e0)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8185add6)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff818658ae)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ndisc.c (ffffffff8187e070)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818867f5)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81889180)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189aad8)
Location: include/net/dst.h:499
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f8e0)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4696)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff818a63e1)
Location: include/net/dst.h:499
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff817f7fe0-ffffffff817f7ff1: dst_output (STB_LOCAL)
ffffffff81822410-ffffffff81822421: dst_output (STB_LOCAL)
ffffffff81863710-ffffffff81863721: dst_output (STB_LOCAL)
ffffffff8187e070-ffffffff8187e081: dst_output (STB_LOCAL)
ffffffff81884fb0-ffffffff81884fc1: dst_output (STB_LOCAL)
ffffffff81889180-ffffffff81889191: dst_output (STB_LOCAL)
ffffffff818a6100-ffffffff818a6111: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff818169c5)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff8181a16c)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff818443d7)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81868700)
Location: include/net/dst.h:469
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8187245b)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818784a6)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ed66)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81888f3d)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff818a40b0)
Location: include/net/dst.h:469
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818acb53)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818af810)
Location: include/net/dst.h:469
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c0c88)
Location: include/net/dst.h:469
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5cee)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caf0e)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff818cce31)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff818183d0-ffffffff818183e1: dst_output (STB_LOCAL)
ffffffff81843080-ffffffff81843091: dst_output (STB_LOCAL)
ffffffff818877e0-ffffffff818877f1: dst_output (STB_LOCAL)
ffffffff818a40b0-ffffffff818a40c1: dst_output (STB_LOCAL)
ffffffff818ab3a0-ffffffff818ab3b1: dst_output (STB_LOCAL)
ffffffff818af810-ffffffff818af821: dst_output (STB_LOCAL)
ffffffff818ccb60-ffffffff818ccb71: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff81895b85)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff818987ac)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff818c3d15)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818e8ad0)
Location: include/net/dst.h:458
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2e41)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8db2)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffe51)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8190b2ac)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff81926a50)
Location: include/net/dst.h:458
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f3b0)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81932530)
Location: include/net/dst.h:458
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81943e98)
Location: include/net/dst.h:458
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194906e)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e84e)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81951c11)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81897530-ffffffff81897547: dst_output (STB_LOCAL)
ffffffff818c29f0-ffffffff818c2a07: dst_output (STB_LOCAL)
ffffffff81908a10-ffffffff81908a27: dst_output (STB_LOCAL)
ffffffff81926a50-ffffffff81926a67: dst_output (STB_LOCAL)
ffffffff8192df30-ffffffff8192df47: dst_output (STB_LOCAL)
ffffffff81932530-ffffffff81932547: dst_output (STB_LOCAL)
ffffffff81951940-ffffffff81951957: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff818e9e45)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff818ed548)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff8191991d)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff8193f210)
Location: include/net/dst.h:442
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949771)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f7ea)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8195699a)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81962785)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff8197f75f)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81987d93)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8198c570)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff8199c5f8)
Location: include/net/dst.h:442
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a221f)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7b32)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff819ab1a1)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff818eb810-ffffffff818eb827: dst_output (STB_LOCAL)
ffffffff81918680-ffffffff81918697: dst_output (STB_LOCAL)
ffffffff8195fbd0-ffffffff8195fbe7: dst_output (STB_LOCAL)
ffffffff8197ee70-ffffffff8197ee87: dst_output (STB_LOCAL)
ffffffff81986bc0-ffffffff81986bd7: dst_output (STB_LOCAL)
ffffffff8198b030-ffffffff8198b047: dst_output (STB_LOCAL)
ffffffff819aaec0-ffffffff819aaed7: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_forward.c (ffffffff81917267)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff8191a048)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819481f8)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81970a11)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b431)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982e0b)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b61c)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8199777d)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff819b5d50)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff819be6dc)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819c2ce3)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff819d4e03)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8e7c)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de67f)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff819e1cc1)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81918d30-ffffffff81918d47: dst_output (STB_LOCAL)
ffffffff81946e00-ffffffff81946e17: dst_output (STB_LOCAL)
ffffffff81994960-ffffffff81994977: dst_output (STB_LOCAL)
ffffffff819b5440-ffffffff819b5457: dst_output (STB_LOCAL)
ffffffff819bd4c0-ffffffff819bd4d7: dst_output (STB_LOCAL)
ffffffff819c1950-ffffffff819c1967: dst_output (STB_LOCAL)
ffffffff819e19e0-ffffffff819e19f7: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff819432d7)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81979198)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff8197d352)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819ab480)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819da26c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4981)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec9fc)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6b2b)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a0373c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a24830)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a2bf60)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a31bab)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a43c69)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a476ec)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d1f5)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81a50a82)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff8197ac70-ffffffff8197ac87: dst_output (STB_LOCAL)
ffffffff819ab480-ffffffff819ab497: dst_output (STB_LOCAL)
ffffffff81a004c0-ffffffff81a004d7: dst_output (STB_LOCAL)
ffffffff81a23ed0-ffffffff81a23ee7: dst_output (STB_LOCAL)
ffffffff81a2bf60-ffffffff81a2bf77: dst_output (STB_LOCAL)
ffffffff81a30760-ffffffff81a30777: dst_output (STB_LOCAL)
ffffffff81a507b0-ffffffff81a507c7: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81978250)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff819afb08)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff819b3d02)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819e2150)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a0f27e)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1b9a1)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23a14)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d793)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a30c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a5b2b0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a63c7f)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a686fb)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a79112)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e26c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83dc5)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81a876a2)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff819b15e0-ffffffff819b15f7: dst_output (STB_LOCAL)
ffffffff819e2150-ffffffff819e2167: dst_output (STB_LOCAL)
ffffffff81a37090-ffffffff81a370a7: dst_output (STB_LOCAL)
ffffffff81a5a950-ffffffff81a5a967: dst_output (STB_LOCAL)
ffffffff81a62ac0-ffffffff81a62ad7: dst_output (STB_LOCAL)
ffffffff81a672b0-ffffffff81a672c7: dst_output (STB_LOCAL)
ffffffff81a873d0-ffffffff81a873e7: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4cd5e)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81a999d8)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a9f237)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81ad090f)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81b0035e)
Location: include/net/dst.h:441
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0ca8f)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15962)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20179)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2fa8f)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b53f69)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c6fe)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b619f9)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b73612)
Location: include/net/dst.h:441
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78f61)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb89)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81b82ab2)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81a9b580-ffffffff81a9b597: dst_output (STB_LOCAL)
ffffffff81acf7e0-ffffffff81acf7f7: dst_output (STB_LOCAL)
ffffffff81b2c310-ffffffff81b2c327: dst_output (STB_LOCAL)
ffffffff81b533f0-ffffffff81b53407: dst_output (STB_LOCAL)
ffffffff81b5b380-ffffffff81b5b397: dst_output (STB_LOCAL)
ffffffff81b5fce0-ffffffff81b5fcf7: dst_output (STB_LOCAL)
ffffffff81b82830-ffffffff81b82847: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a52a20)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3928)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81aa9177)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81adc92b)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81b0e3de)
Location: include/net/dst.h:439
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1adbf)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23dc7)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2eaa9)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e4bb)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff81b62572)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b6af3e)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b7019a)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b82342)
Location: include/net/dst.h:439
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87ee1)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db9e)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81b92122)
Location: include/net/dst.h:439
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81aa53f0-ffffffff81aa5407: dst_output (STB_LOCAL)
ffffffff81adb800-ffffffff81adb817: dst_output (STB_LOCAL)
ffffffff81b3ad30-ffffffff81b3ad47: dst_output (STB_LOCAL)
ffffffff81b61960-ffffffff81b61977: dst_output (STB_LOCAL)
ffffffff81b69ba0-ffffffff81b69bb7: dst_output (STB_LOCAL)
ffffffff81b6e450-ffffffff81b6e467: dst_output (STB_LOCAL)
ffffffff81b91e90-ffffffff81b91ea7: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a381a9)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81a8e9c8)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a942f7)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81ac7967)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81afc0ae)
Location: include/net/dst.h:446
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b089fd)
Location: include/net/dst.h:446
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11aa2)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c826)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cca7)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b50130)
Location: include/net/dst.h:446
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b59250)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b5cc10)
Location: include/net/dst.h:446
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b71382)
Location: include/net/dst.h:446
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76c17)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca69)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81b814a2)
Location: include/net/dst.h:446
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81a91e00-ffffffff81a91e35: dst_output (STB_LOCAL)
ffffffff81ac6bf0-ffffffff81ac6c25: dst_output (STB_LOCAL)
ffffffff81b2c120-ffffffff81b2c155: dst_output (STB_LOCAL)
ffffffff81b50130-ffffffff81b50165: dst_output (STB_LOCAL)
ffffffff81b58370-ffffffff81b583a5: dst_output (STB_LOCAL)
ffffffff81b5cc10-ffffffff81b5cc45: dst_output (STB_LOCAL)
ffffffff81b811e0-ffffffff81b81215: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee012)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81b49bc8)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81b4f777)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81b861c4)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81bbd5ae)
Location: include/net/dst.h:448
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcb8fd)
Location: include/net/dst.h:448
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd55c8)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81be1193)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2e21)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81c17490)
Location: include/net/dst.h:448
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c2085f)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81c24460)
Location: include/net/dst.h:448
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3b5f2)
Location: include/net/dst.h:448
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41685)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47bc7)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/output_core.c (ffffffff81c4d4c2)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81b4d210-ffffffff81b4d245: dst_output (STB_LOCAL)
ffffffff81b85410-ffffffff81b85445: dst_output (STB_LOCAL)
ffffffff81bf22b0-ffffffff81bf22e5: dst_output (STB_LOCAL)
ffffffff81c17490-ffffffff81c174c5: dst_output (STB_LOCAL)
ffffffff81c1f700-ffffffff81c1f735: dst_output (STB_LOCAL)
ffffffff81c24460-ffffffff81c24495: dst_output (STB_LOCAL)
ffffffff81c46af0-ffffffff81c46b25: dst_output (STB_LOCAL)
ffffffff81c4d200-ffffffff81c4d235: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c70e4e)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81cd711c)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81cdd127)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81d16b19)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81d51dad)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d613c9)
Location: include/net/dst.h:449
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bddc)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7809b)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b935)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff81db31c0)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbd5df)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81dc30d0)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9712)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfea2)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de7063)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec25e)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/output_core.c (ffffffff81deda31)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81cda9d0-ffffffff81cdaa23: dst_output (STB_LOCAL)
ffffffff81d16150-ffffffff81d161a3: dst_output (STB_LOCAL)
ffffffff81d8ad10-ffffffff81d8ad63: dst_output (STB_LOCAL)
ffffffff81db31c0-ffffffff81db3213: dst_output (STB_LOCAL)
ffffffff81dbc2f0-ffffffff81dbc343: dst_output (STB_LOCAL)
ffffffff81dc15c0-ffffffff81dc1613: dst_output (STB_LOCAL)
ffffffff81de5dd0-ffffffff81de5e23: dst_output (STB_LOCAL)
ffffffff81ded700-ffffffff81ded753: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e28ece)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81e976dc)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81e9dbb7)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81edd1e4)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81f1bd8d)
Location: include/net/dst.h:442
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2bcd9)
Location: include/net/dst.h:442
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3711c)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4491f)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81f5993f)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff81f827b0)
Location: include/net/dst.h:442
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8db1e)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81f93a11)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fab342)
Location: include/net/dst.h:442
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb21c2)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9ef3)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfeae)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/output_core.c (ffffffff81fc1901)
Location: include/net/dst.h:442
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81e9b1e0-ffffffff81e9b233: dst_output (STB_LOCAL)
ffffffff81edc2d0-ffffffff81edc323: dst_output (STB_LOCAL)
ffffffff81f58cf0-ffffffff81f58d43: dst_output (STB_LOCAL)
ffffffff81f827b0-ffffffff81f82803: dst_output (STB_LOCAL)
ffffffff81f8c490-ffffffff81f8c4e3: dst_output (STB_LOCAL)
ffffffff81f91da0-ffffffff81f91df3: dst_output (STB_LOCAL)
ffffffff81fb8650-ffffffff81fb86a3: dst_output (STB_LOCAL)
ffffffff81fc1520-ffffffff81fc1573: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9e502)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81ef5f0c)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81efc377)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff81f3c434)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff81f7b86d)
Location: include/net/dst.h:456
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8b979)
Location: include/net/dst.h:456
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f969e0)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa4107)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81fb95f3)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff81fe2ac0)
Location: include/net/dst.h:456
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fee2f7)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81ff436b)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200bae2)
Location: include/net/dst.h:456
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff820128d2)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a626)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020e86)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/output_core.c (ffffffff82022881)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81ef9c00-ffffffff81ef9c53: dst_output (STB_LOCAL)
ffffffff81f3b370-ffffffff81f3b3c3: dst_output (STB_LOCAL)
ffffffff81fb89c0-ffffffff81fb8a13: dst_output (STB_LOCAL)
ffffffff81fe2ac0-ffffffff81fe2b13: dst_output (STB_LOCAL)
ffffffff81fecc60-ffffffff81feccb3: dst_output (STB_LOCAL)
ffffffff81ff26c0-ffffffff81ff2713: dst_output (STB_LOCAL)
ffffffff82018dc0-ffffffff82018e13: dst_output (STB_LOCAL)
ffffffff820224a0-ffffffff820224f3: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f60c7b)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9ea1)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81fc02b7)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/raw.c (ffffffff8200255e)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (ffffffff82041f4e)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff82053279)
Location: include/net/dst.h:449
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063e0e)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff82071437)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff82086b63)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ndisc.c (ffffffff820b09e0)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bbec2)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff820c0320)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820daac0)
Location: include/net/dst.h:449
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1a30)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e95e3)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820effb3)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/output_core.c (ffffffff820f19a1)
Location: include/net/dst.h:449
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81fbdb30-ffffffff81fbdb83: dst_output (STB_LOCAL)
ffffffff82001490-ffffffff820014e3: dst_output (STB_LOCAL)
ffffffff82085fa0-ffffffff82085ff3: dst_output (STB_LOCAL)
ffffffff820b09e0-ffffffff820b0a33: dst_output (STB_LOCAL)
ffffffff820ba860-ffffffff820ba8b3: dst_output (STB_LOCAL)
ffffffff820c0320-ffffffff820c0373: dst_output (STB_LOCAL)
ffffffff820e7d90-ffffffff820e7de3: dst_output (STB_LOCAL)
ffffffff820f15c0-ffffffff820f1613: dst_output (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffff800010c1eaac)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffff800010c601c4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffff800010c644fc)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffff800010c96120)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cc98a4)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7c30)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c90)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffff800010cec568)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffff800010cfb2ec)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffff800010d20bd0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffff800010d29d40)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffff800010d2d2e0)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d42e68)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49694)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fb14)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffff800010d53f7c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffff800010c61b88-ffff800010c61ba8: dst_output (STB_LOCAL)
ffff800010c96120-ffff800010c96140: dst_output (STB_LOCAL)
ffff800010cf80a8-ffff800010cf80c8: dst_output (STB_LOCAL)
ffff800010d1fc38-ffff800010d1fc58: dst_output (STB_LOCAL)
ffff800010d27cc8-ffff800010d27ce8: dst_output (STB_LOCAL)
ffff800010d2d2e0-ffff800010d2d300: dst_output (STB_LOCAL)
ffff800010d53c68-ffff800010d53c88: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d36b04)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (c0d6fa88)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d74054)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (c0da5c78)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ipmr.c (c0dd758c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (c0de1714)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (c0de9fb4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (c0df445c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c0e01fd4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (c0e252dc)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (c0e2de20)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c0e339f8)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (c0e46ab4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (c0e4aa70)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (c0e50870)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (c0e54730)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
c0d714d0-c0d714f0: dst_output (STB_LOCAL)
c0da4900-c0da4920: dst_output (STB_LOCAL)
c0dfe3fc-c0dfe41c: dst_output (STB_LOCAL)
c0e24818-c0e24838: dst_output (STB_LOCAL)
c0e2c738-c0e2c758: dst_output (STB_LOCAL)
c0e310dc-c0e310fc: dst_output (STB_LOCAL)
c0e54464-c0e54484: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c000000000d10c58)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (c000000000d63094)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c000000000d68534)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (c000000000da7660)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de69c8)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (c000000000df7c60)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (c000000000e02f2c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (c000000000e10630)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c000000000e22890)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (c000000000e4e330)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5aba0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c000000000e5ef00)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e77560)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ed14)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e872f0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (c000000000e8c964)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
c000000000d65140-c000000000d65180: dst_output (STB_LOCAL)
c000000000da7660-c000000000da76a0: dst_output (STB_LOCAL)
c000000000e1e990-c000000000e1e9d0: dst_output (STB_LOCAL)
c000000000e4e330-c000000000e4e370: dst_output (STB_LOCAL)
c000000000e58ce0-c000000000e58d20: dst_output (STB_LOCAL)
c000000000e5ef00-c000000000e5ef40: dst_output (STB_LOCAL)
c000000000e8c500-c000000000e8c540: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffe0007986c4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffe0007c849c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffe0007cbe90)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffe0007f522c)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081d68c)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082824c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f906)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffe000839bf4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffe000845e58)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffe000861e2e)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086a696)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffe00086d39e)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087d938)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882b04)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888244)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffe00088ba8a)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffe0007c9ba6-ffffffe0007c9bbe: dst_output (STB_LOCAL)
ffffffe0007f522c-ffffffe0007f5244: dst_output (STB_LOCAL)
ffffffe000861e2e-ffffffe000861e46: dst_output (STB_LOCAL)
ffffffe000869556-ffffffe00086956e: dst_output (STB_LOCAL)
ffffffe00086d39e-ffffffe00086d3b6: dst_output (STB_LOCAL)
ffffffe0008430ac-ffffffe0008430c4: dst_output (STB_LOCAL)
ffffffe00088b820-ffffffe00088b838: dst_output (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff819180c0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff8194f978)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff81953b72)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81981fc0)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819aedfe)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb031)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c30a4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff819cce23)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d999c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819fa940)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a0330f)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a07d8b)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a187a2)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d8fc)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23455)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81a26d32)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff81951450-ffffffff81951467: dst_output (STB_LOCAL)
ffffffff81981fc0-ffffffff81981fd7: dst_output (STB_LOCAL)
ffffffff819d6720-ffffffff819d6737: dst_output (STB_LOCAL)
ffffffff819f9fe0-ffffffff819f9ff7: dst_output (STB_LOCAL)
ffffffff81a02150-ffffffff81a02167: dst_output (STB_LOCAL)
ffffffff81a06940-ffffffff81a06957: dst_output (STB_LOCAL)
ffffffff81a26a60-ffffffff81a26a77: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818d1e70)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff81909468)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff8190d662)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff8193ba80)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196b42e)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977e21)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fe94)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81989c13)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8199675c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819b7700)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff819c00cf)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff819c4b4b)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff819d5562)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da6bc)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e0215)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff819e3af2)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff8190af40-ffffffff8190af57: dst_output (STB_LOCAL)
ffffffff8193ba80-ffffffff8193ba97: dst_output (STB_LOCAL)
ffffffff819934e0-ffffffff819934f7: dst_output (STB_LOCAL)
ffffffff819b6da0-ffffffff819b6db7: dst_output (STB_LOCAL)
ffffffff819bef10-ffffffff819bef27: dst_output (STB_LOCAL)
ffffffff819c3700-ffffffff819c3717: dst_output (STB_LOCAL)
ffffffff819e3820-ffffffff819e3837: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81969250)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff819ba148)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff819be342)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819ec790)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1969e)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25ab1)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2db24)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81a378a3)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a4441c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a653c0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a6dd8f)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7280b)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a83222)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a8837c)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8ded5)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81a928e2)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff819bbc20-ffffffff819bbc37: dst_output (STB_LOCAL)
ffffffff819ec790-ffffffff819ec7a7: dst_output (STB_LOCAL)
ffffffff81a411a0-ffffffff81a411b7: dst_output (STB_LOCAL)
ffffffff81a64a60-ffffffff81a64a77: dst_output (STB_LOCAL)
ffffffff81a6cbd0-ffffffff81a6cbe7: dst_output (STB_LOCAL)
ffffffff81a713c0-ffffffff81a713d7: dst_output (STB_LOCAL)
ffffffff81a92610-ffffffff81a92627: dst_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dst_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff8198b630)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_forward.c (ffffffff819c3a38)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffffffff819c7c72)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819f6680)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a2435e)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a30f51)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a392e0)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81a43255)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a500c7)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a71933)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a7a3b4)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7ee8d)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a8fb02)
Location: include/net/dst.h:434
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94fcc)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ac19)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/output_core.c (ffffffff81a9e9e2)
Location: include/net/dst.h:434
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
```
**Symbols:**

```
ffffffff819c5530-ffffffff819c5547: dst_output (STB_LOCAL)
ffffffff819f6680-ffffffff819f6697: dst_output (STB_LOCAL)
ffffffff81a4cd90-ffffffff81a4cda7: dst_output (STB_LOCAL)
ffffffff81a70f90-ffffffff81a70fa7: dst_output (STB_LOCAL)
ffffffff81a79210-ffffffff81a79227: dst_output (STB_LOCAL)
ffffffff81a7d9d0-ffffffff81a7d9e7: dst_output (STB_LOCAL)
ffffffff81a9e6e0-ffffffff81a9e6f7: dst_output (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
