# Function: <code>ip_route_output_key</code>

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
In net/ipv4/route.c (ffffffff81757412)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8175f758)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff8178c773)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8178e324)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff817956b0)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff817ab795)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff817ac140)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff817c36b2)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff817cb9f8)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff817f9d6e)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff817fb925)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff818030a0)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81819293)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81819480)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff817f2cd5)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff817fb665)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff8182ac3e)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8182c828)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff81834040)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff8184ab11)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff8184ad10)
Location: include/net/route.h:130
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/ip_output.c (ffffffff8181ba37)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff8184be36)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8184dc12)
Location: include/net/route.h:133
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8185560c)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff8186e510)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff8186e770)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/ip_output.c (ffffffff8189a970)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff818cbadc)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff818cd922)
Location: include/net/route.h:133
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d54ac)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff818eeeaa)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff818ef130)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/ip_output.c (ffffffff818eee34)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81921fd4)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81923d13)
Location: include/net/route.h:132
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8192be58)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff819457bd)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81945ac5)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/ip_output.c (ffffffff8191c621)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81950e04)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81952afd)
Location: include/net/route.h:132
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195b2e8)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81975b56)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81975de5)
Location: include/net/route.h:132
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff8194322f)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff8197e94c)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff819b56d3)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819b7383)
Location: include/net/route.h:133
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819bff8d)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff819df6b0)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff819df975)
Location: include/net/route.h:133
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff819781a4)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff819b52ec)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff819ec3f3)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819ee083)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f6b2d)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81a166f3)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81a169a5)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81a4ccc2)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a96d88)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/ip_output.c (ffffffff81a9f54e)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81ada348)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81adbe47)
Location: include/net/route.h:140
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81ae510d)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81b076c7)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81b079e5)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81a52982)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81aa0e78)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/ip_output.c (ffffffff81aa948e)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81ae6de8)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81ae896d)
Location: include/net/route.h:140
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81af1fdd)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81b15ac6)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81b15dc0)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81a380fc)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a8bdfa)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/ip_output.c (ffffffff81a94658)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81ad20b7)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81ad45bb)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81add7cd)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81b038d4)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81b03bc0)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81aedf3c)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81b46d8a)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/ip_output.c (ffffffff81b4fad8)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81b90d07)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81b93fd0)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81b9cc3d)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81bc5b64)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81bc5e70)
Location: include/net/route.h:140
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81c70d72)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81cd3e4b)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/ip_output.c (ffffffff81cdd557)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81d236ca)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81d25466)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81d2ece2)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81d5ae5a)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81d5b170)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81e28df2)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81e9408b)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/arp.c (ffffffff81eeacda)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81eeca56)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81ef6d32)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81f252ca)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81f255f0)
Location: include/net/route.h:154
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81e9e425)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81ef283b)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
```
In net/ipv4/arp.c (ffffffff81f4a63a)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81f4b642)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81f567a2)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81f84e5b)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81f85180)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81f60ba1)
Location: include/net/route.h:142
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/arp.c (ffffffff8201074a)
Location: include/net/route.h:142
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff82011752)
Location: include/net/route.h:142
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff8201cc52)
Location: include/net/route.h:142
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff8204b5d2)
Location: include/net/route.h:142
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff8204b830)
Location: include/net/route.h:142
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffff800010c1ea24)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffff800010c65a30)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffff800010ca1f4c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffff800010ca3c3c)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cad650)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffff800010cd239c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffff800010cd25dc)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (c0d36a68)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (c0d7569c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (c0daed2c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c0db08b4)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (c0dba550)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (c0ddc26c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (c0ddc4fc)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (c000000000d10ba4)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (c000000000d6a1b4)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (c000000000db52a0)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c000000000db75ec)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc3c14)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (c000000000df0844)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (c000000000df0b50)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffe000798630)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffe0007cd18a)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffe0007fdb8c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffe0007fface)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000807a84)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffe000823740)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffe000823934)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff81918014)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff8195515c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff8198c223)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8198de23)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819968cd)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff819b5d83)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff819b6035)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In drivers/net/vxlan.c (ffffffff8176e778)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_get_route
```
```
In net/core/lwt_bpf.c (ffffffff818d1dc4)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff8190ec4c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81945ce3)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819478e3)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195038d)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967585)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev
```
```
In net/ipv4/syncookies.c (ffffffff81972b73)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81972e25)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff819691a4)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff819bf92c)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff819f6a33)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819f86c3)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0116d)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81a20623)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81a208d5)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/core/lwt_bpf.c (ffffffff8198b584)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_output.c (ffffffff819c92ab)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/arp.c (ffffffff81a00c53)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81a029f3)
Location: include/net/route.h:134
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0b65d)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/syncookies.c (ffffffff81a2bb23)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81a2bdf5)
Location: include/net/route.h:134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
</details>
</li>
</ul>

## Differences
