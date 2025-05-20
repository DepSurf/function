# Function: <code>__skb_flow_dissect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81711d30)
Location: net/core/flow_dissector.c:121
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:skb_get_poff
  - net/ethernet/eth.c:eth_get_headlen
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81711d30-ffffffff81712696: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81779680)
Location: net/core/flow_dissector.c:108
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81779680-ffffffff8177a023: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817a67d0)
Location: net/core/flow_dissector.c:132
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff817a67d0-ffffffff817a75cc: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c4aa0)
Location: net/core/flow_dissector.c:420
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:fib_multipath_hash
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff817c4aa0-ffffffff817c5c09: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183e3b0)
Location: net/core/flow_dissector.c:525
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:fib_multipath_hash
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8183e3b0-ffffffff8183f7fa: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81888c20)
Location: net/core/flow_dissector.c:578
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81888c20-ffffffff81889d8f: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818a97f0)
Location: net/core/flow_dissector.c:702
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff818a97f0-ffffffff818aacca: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f5210)
Location: net/core/flow_dissector.c:828
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff818f5210-ffffffff818f6668: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819270e0)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff819270e0-ffffffff8192866b: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fb580)
Location: net/core/flow_dissector.c:885
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff819fb580-ffffffff819fc89c: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fb180)
Location: net/core/flow_dissector.c:902
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff819fb180-ffffffff819fc4d3: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e13a0)
Location: net/core/flow_dissector.c:914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff819e13a0-ffffffff819e2d5e: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a917e0)
Location: net/core/flow_dissector.c:915
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff81a917e0-ffffffff81a931bf: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c07980)
Location: net/core/flow_dissector.c:917
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff81c07980-ffffffff81c09337: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db7420)
Location: net/core/flow_dissector.c:946
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff81db7420-ffffffff81db90b4: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/flow_dissector.c (0)
Location: net/core/flow_dissector.c:980
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff8212c6e0-ffffffff8212c73e: __skb_flow_dissect.cold (STB_LOCAL)
ffffffff81e27ae0-ffffffff81e296cd: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/flow_dissector.c (0)
Location: net/core/flow_dissector.c:1024
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff8220e40a-ffffffff8220e468: __skb_flow_dissect.cold (STB_LOCAL)
ffffffff81ee5a90-ffffffff81ee7732: __skb_flow_dissect (STB_GLOBAL)
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
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc3680)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffff800010bc3680-ffff800010bc48bc: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0cde948)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
c0cde948-c0cdfef8: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9d7a0)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
c000000000c9d7a0-c000000000c9eed0: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe000750124)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffe000750124-ffffffe000751442: __skb_flow_dissect (STB_GLOBAL)
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
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c70e0)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff818c70e0-ffffffff818c866b: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81881020)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81881020-ffffffff818825ab: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819180e0)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff819180e0-ffffffff8191966b: __skb_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __skb_flow_dissect(const struct net *net, const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81939330)
Location: net/core/flow_dissector.c:877
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/ethernet/eth.c:eth_get_headlen
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81939330-ffffffff8193a8a4: __skb_flow_dissect (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, flow_dissector, target_container, data, proto, nhoff, hlen, flags</code> ➡️ <code>net, skb, flow_dissector, target_container, data, proto, nhoff, hlen, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
</ul>
</details>
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
