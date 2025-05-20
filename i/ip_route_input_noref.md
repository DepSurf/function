# Function: <code>ip_route_input_noref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81755420)
Location: net/ipv4/route.c:1954
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
**Symbols:**

```
ffffffff81755420-ffffffff81756284: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c15b0)
Location: net/ipv4/route.c:1961
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
**Symbols:**

```
ffffffff817c15b0-ffffffff817c24a5: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f1ab0)
Location: net/ipv4/route.c:1989
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
**Symbols:**

```
ffffffff817f1ab0-ffffffff817f2a65: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818122d0)
Location: net/ipv4/route.c:2068
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
**Symbols:**

```
ffffffff818122d0-ffffffff8181230e: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818918f0)
Location: net/ipv4/route.c:2083
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff818918f0-ffffffff8189192e: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e5870)
Location: net/ipv4/route.c:2115
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff818e5870-ffffffff818e58ae: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81912780)
Location: net/ipv4/route.c:2116
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81912780-ffffffff819127be: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81974ea0)
Location: net/ipv4/route.c:2243
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81974ea0-ffffffff81974ede: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ab8c0)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff819ab8c0-ffffffff819ab8fe: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a95b00)
Location: net/ipv4/route.c:2289
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81a95b00-ffffffff81a95b3e: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9fb70)
Location: net/ipv4/route.c:2295
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81a9fb70-ffffffff81a9fbbf: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8aab0)
Location: net/ipv4/route.c:2296
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81a8aab0-ffffffff81a8aaff: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b459a0)
Location: net/ipv4/route.c:2415
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
**Symbols:**

```
ffffffff81b459a0-ffffffff81b459ef: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd2740)
Location: net/ipv4/route.c:2443
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
**Symbols:**

```
ffffffff81cd2740-ffffffff81cd27df: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e92830)
Location: net/ipv4/route.c:2486
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
**Symbols:**

```
ffffffff81e92830-ffffffff81e928f5: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef0fd0)
Location: net/ipv4/route.c:2484
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
**Symbols:**

```
ffffffff81ef0fd0-ffffffff81ef1095: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb5120)
Location: net/ipv4/route.c:2487
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
**Symbols:**

```
ffffffff81fb5120-ffffffff81fb51e5: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5ba40)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffff800010c5ba40-ffff800010c5bac8: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6b050)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
c0d6b050-c0d6b0b8: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5db20)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
c000000000d5db20-c000000000d5db80: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c4c60)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffe0007c4c60-ffffffe0007c4cb0: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194b730)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff8194b730-ffffffff8194b76e: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81905220)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81905220-ffffffff8190525e: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b5f00)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff819b5f00-ffffffff819b5f3e: ip_route_input_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bf6c0)
Location: net/ipv4/route.c:2247
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/arp.c:arp_process
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff819bf6c0-ffffffff819bf740: ip_route_input_noref (STB_GLOBAL)
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
