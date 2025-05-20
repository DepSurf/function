# Function: <code>icmp6_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff817e7700)
Location: net/ipv6/icmp.c:391
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff817e7700-ffffffff817e7fb6: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81855b00)
Location: net/ipv6/icmp.c:391
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81855b00-ffffffff818564dd: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff818878c0)
Location: net/ipv6/icmp.c:392
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff818878c0-ffffffff818882c8: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff818adeb0)
Location: net/ipv6/icmp.c:405
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff818adeb0-ffffffff818ae997: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81930b30)
Location: net/ipv6/icmp.c:420
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81930b30-ffffffff8193165d: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81989760)
Location: net/ipv6/icmp.c:421
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81989760-ffffffff8198a173: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819c0090)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff819c0090-ffffffff819c0a26: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a2eed0)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81a2eed0-ffffffff81a2f720: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a65a20)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81a65a20-ffffffff81a66270: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5e370)
Location: net/ipv6/icmp.c:442
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81b5e370-ffffffff81b5ec7f: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b6cb40)
Location: net/ipv6/icmp.c:447
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81b6cb40-ffffffff81b6d3f8: icmp6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5aea0)
Location: net/ipv6/icmp.c:447
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81b5aea0-ffffffff81b5b78a: icmp6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:448
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81d40944-ffffffff81d4096a: icmp6_send.cold (STB_LOCAL)
ffffffff81c225b0-ffffffff81c22e95: icmp6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:440
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob_reason
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81f0d32d-ffffffff81f0d353: icmp6_send.cold (STB_LOCAL)
ffffffff81dbf300-ffffffff81dbfcf9: icmp6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:440
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob_reason
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff820b479f-ffffffff820b47c5: icmp6_send.cold (STB_LOCAL)
ffffffff81f8fa50-ffffffff81f90448: icmp6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:445
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob_reason
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff82135822-ffffffff8213583b: icmp6_send.cold (STB_LOCAL)
ffffffff81ff0280-ffffffff81ff0ca1: icmp6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr, const struct inet6_skb_parm *parm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:445
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob_reason
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff822172fd-ffffffff8221732f: icmp6_send.cold (STB_LOCAL)
ffffffff820bde50-ffffffff820be88e: icmp6_send (STB_GLOBAL)
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
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffff800010d2baf0)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffff800010d2baf0-ffff800010d2c1fc: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c0e2f95c)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
c0e2f95c-c0e30088: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c000000000e5d110)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
c000000000e5d110-c000000000e5da34: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffe00086be1a)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffe00086be1a-ffffffe00086c4f2: icmp6_send (STB_LOCAL)
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
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a050b0)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81a050b0-ffffffff81a05900: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819c1e70)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff819c1e70-ffffffff819c26c0: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a6fb30)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81a6fb30-ffffffff81a70380: icmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info, const struct in6_addr *force_saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a7c160)
Location: net/ipv6/icmp.c:423
Inline: False
Direct callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmpv6_param_prob
```
**Symbols:**

```
ffffffff81a7c160-ffffffff81a7c99b: icmp6_send (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr *force_saddr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inet6_skb_parm *parm</code>
</li>
</ul>
</details>
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
