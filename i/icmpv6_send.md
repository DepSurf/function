# Function: <code>icmpv6_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81800420)
Location: net/ipv6/ip6_icmp.c:33
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81800420-ffffffff81800441: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81871b30)
Location: net/ipv6/ip6_icmp.c:33
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81871b30-ffffffff81871b54: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff818a6090)
Location: net/ipv6/ip6_icmp.c:33
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff818a6090-ffffffff818a60b4: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff818ccaf0)
Location: net/ipv6/ip6_icmp.c:33
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff818ccaf0-ffffffff818ccb15: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff819518d0)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff819518d0-ffffffff819518f8: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff819aae50)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff819aae50-ffffffff819aae77: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff819e1970)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff819e1970-ffffffff819e1997: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81a50740)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81a50740-ffffffff81a50767: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81a87360)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81a87360-ffffffff81a87387: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81b82767)
Location: net/ipv6/ip6_icmp.c:34
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
**Symbols:**

```
ffffffff81b82610-ffffffff81b82637: icmpv6_send (STB_GLOBAL)
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
In security/smack/smack_lsm.c (ffffffff814f29ba)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d9ed)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ebdb)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b40bca)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b4eba6)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81b6986a)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b74927)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c334)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b88382)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
In security/smack/smack_lsm.c (ffffffff814f990d)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bab4)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b983)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e462)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b3c9d6)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81b57b3b)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b63447)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81b6ae21)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b770b2)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
In security/smack/smack_lsm.c (ffffffff815544ed)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81be02e5)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1a63)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf476a)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81c03315)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81c1f145)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81c2af06)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81c32c81)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41b52)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
In security/smack/smack_lsm.c (ffffffff815f0272)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77290)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a495)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d502)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81d9d2a0)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81dbb9cd)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81dc879d)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81dd046e)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de03f2)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
In security/smack/smack_lsm.c (ffffffff816a0622)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43b10)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f58425)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b5ae)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81f6c1d0)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81f8bad2)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81f99545)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81fa17fe)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb2782)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
In security/smack/smack_lsm.c (ffffffff816d8f7e)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa32ec)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7fa6)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb36f)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81fcc2d5)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81fec20d)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81ff9f15)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff82002070)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012e92)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
In security/smack/smack_lsm.c (ffffffff817159a5)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff82070972)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff820855bb)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8208877f)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff82099ab8)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff820b9e03)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff820c7b85)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff820d0e70)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e1ff2)
Location: include/linux/icmpv6.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
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
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffff800010d53ab8)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffff800010d53ab8-ffff800010d53b14: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (c0e54378)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
c0e54378-c0e543b8: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (c000000000e8c410)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
c000000000e8c410-c000000000e8c464: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffe00088b78a)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffe00088b78a-ffffffe00088b7d2: icmpv6_send (STB_GLOBAL)
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
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81a269f0)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81a269f0-ffffffff81a26a17: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff819e37b0)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff819e37b0-ffffffff819e37d7: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81a925a0)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire
```
**Symbols:**

```
ffffffff81a925a0-ffffffff81a925c7: icmpv6_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff *skb, u8 type, u8 code, __u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_icmp.c (ffffffff81a9e690)
Location: net/ipv6/ip6_icmp.c:34
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81a9e690-ffffffff81a9e6df: icmpv6_send (STB_GLOBAL)
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
