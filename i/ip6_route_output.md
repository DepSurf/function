# Function: <code>ip6_route_output</code>

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
In net/ipv6/ip6_output.c (ffffffff817c45f9)
Location: include/net/ip6_route.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff817d6ee1)
Location: include/net/ip6_route.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff817e0d4d)
Location: include/net/ip6_route.h:70
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff817e7a6d)
Location: include/net/ip6_route.h:70
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff817f9fa9)
Location: include/net/ip6_route.h:70
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc001)
Location: include/net/ip6_route.h:70
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff817fdb71)
Location: include/net/ip6_route.h:70
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/ip6_output.c (ffffffff81831704)
Location: include/net/ip6_route.h:71
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81842726)
Location: include/net/ip6_route.h:71
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff8184f646)
Location: include/net/ip6_route.h:71
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81855eff)
Location: include/net/ip6_route.h:71
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81869813)
Location: include/net/ip6_route.h:71
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b8fa)
Location: include/net/ip6_route.h:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff8186d4a1)
Location: include/net/ip6_route.h:71
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/ip6_output.c (ffffffff81863170)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff818744a6)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff818815a9)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81887d54)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8189c663)
Location: include/net/ip6_route.h:75
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e75a)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff818a0281)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a46dd)
Location: include/net/ip6_route.h:75
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81887958)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81899469)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff818a7615)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff818ae3b1)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff818c2a23)
Location: include/net/ip6_route.h:76
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4e0a)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff818c68c1)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caf7a)
Location: include/net/ip6_route.h:76
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81908c08)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff8191da43)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff8192a081)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81931053)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81944e33)
Location: include/net/ip6_route.h:77
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81947e9d)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81949ca1)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e8c0)
Location: include/net/ip6_route.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff8195fda0)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81972810)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff8198235a)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81989cf4)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8199e1bb)
Location: include/net/ip6_route.h:84
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a0ff7)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff819a2cb1)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7c39)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81994b3f)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819a837f)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff819b8a0a)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff819c05aa)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff819d4c7b)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7c2a)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff819d9951)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de792)
Location: include/net/ip6_route.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81a00746)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a15587)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81a2747a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81a2eb29)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81a43acc)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46c37)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81a481c1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d30b)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81a37316)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a4c157)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81a5deda)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81a65679)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a74c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d7e7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81a7ed71)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83edb)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81b2c846)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81b45cd6)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81b56ca6)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81b5eb12)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81b7601e)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b780d7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81b799c1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ec91)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81b3b215)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81b5469a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81b65316)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81b6d29a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81b84d9e)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87027)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81b88911)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8dcab)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81b28f1c)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b41dfa)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81b5360a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81b5b5d1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81b73a52)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75cf7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81b77641)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7cb7d)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81bf0103)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c09b50)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81c1ab1a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81c22ce4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e031)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40767)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81c42111)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47ced)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
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
In net/ipv6/ip6_output.c (ffffffff81d887a1)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da4d41)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81db70dd)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81dbfbc1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc6ae)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddede9)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81de0aa1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de7153)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec383)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/ipv6/ip6_output.c (ffffffff81f56581)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f741f1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81f86dad)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81f90310)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81fad73e)
Location: include/net/ip6_route.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb0e99)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81fb2ed1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9fe3)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbffd3)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/ipv6/ip6_output.c (ffffffff81fb5f63)
Location: include/net/ip6_route.h:90
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd42d4)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81fe70ed)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81ff0b64)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff8200deee)
Location: include/net/ip6_route.h:90
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011549)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff820135c1)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a716)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020f51)
Location: include/net/ip6_route.h:90
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/ipv6/ip6_output.c (ffffffff82083633)
Location: include/net/ip6_route.h:89
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a1be6)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff820b4f4c)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff820be758)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff820dca7e)
Location: include/net/ip6_route.h:89
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e04e3)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff820e2721)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e96d0)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f007e)
Location: include/net/ip6_route.h:89
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/ipv6/ip6_output.c (ffff800010cf9e64)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffff800010d1165c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffff800010d22fa4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffff800010d2b8dc)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffff800010d44214)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d489a4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffff800010d4a318)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fc20)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (c0dfe81c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (c0e15a7c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (c0e275f0)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (c0e2f4c0)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (c0e46764)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (c0e4a014)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (c0e4b564)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c0e50990)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (c000000000e1ece0)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (c000000000e3ab04)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (c000000000e52e8c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (c000000000e5ce10)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (c000000000e7a6b8)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7ddbc)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (c000000000e7fea4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e874b4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffe0008433a2)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffe0008562b4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffe000864a18)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffe00086ba7e)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffe0008800ea)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffe0008820e4)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffe000883514)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888330)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff819d69a6)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819eb7e7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff819fd56a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81a04d09)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81a19ddc)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1ce77)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81a1e401)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a2356b)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81993766)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819a85a7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff819ba32a)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff819c1ac9)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff819d6b9c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9c37)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff819db1c1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e032b)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81a41426)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a56267)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81a67fea)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81a6f789)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81a8485c)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a878f7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81a88e81)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dfeb)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv6/ip6_output.c (ffffffff81a4cfde)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a622b7)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
```
```
In net/ipv6/ndisc.c (ffffffff81a745da)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81a7bdb9)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/ip6mr.c (ffffffff81a911ac)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a944e0)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/netfilter.c (ffffffff81a95ae1)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ad2f)
Location: include/net/ip6_route.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
</details>
</li>
</ul>

## Differences
