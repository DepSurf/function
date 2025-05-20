# Function: <code>skb_set_owner_w</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817024f0)
Location: net/core/sock.c:1657
Inline: True
Direct callers:
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff817024f0-ffffffff81702588: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769720)
Location: net/core/sock.c:1673
Inline: True
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81769720-ffffffff817697b8: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81796640)
Location: net/core/sock.c:1671
Inline: True
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81796640-ffffffff817966d8: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4a10)
Location: net/core/sock.c:1814
Inline: True
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff817b4a10-ffffffff817b4aa8: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182cc40)
Location: net/core/sock.c:1825
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff8182cc40-ffffffff8182cceb: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81876a30)
Location: net/core/sock.c:1845
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81876a30-ffffffff81876ad7: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897200)
Location: net/core/sock.c:1841
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81897200-ffffffff818972a7: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1650)
Location: net/core/sock.c:1973
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff818e1650-ffffffff818e16f7: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913840)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81913840-ffffffff819138e7: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5f00)
Location: net/core/sock.c:2083
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
**Symbols:**

```
ffffffff819e5f00-ffffffff819e5fde: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e52d0)
Location: net/core/sock.c:2075
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
**Symbols:**

```
ffffffff819e52d0-ffffffff819e53ae: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cb300)
Location: net/core/sock.c:2104
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
**Symbols:**

```
ffffffff819cb300-ffffffff819cb3d8: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2228
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_expand_head
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
**Symbols:**

```
ffffffff81d34b4e-ffffffff81d34b6e: skb_set_owner_w.cold (STB_LOCAL)
ffffffff81a7a970-ffffffff81a7aa61: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81bee90f)
Location: net/core/sock.c:2395
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_expand_head
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81f01065-ffffffff81f01085: skb_set_owner_w.cold (STB_LOCAL)
ffffffff81bee850-ffffffff81bee964: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81d9af3f)
Location: net/core/sock.c:2474
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_expand_head
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff820aab96-ffffffff820aabb6: skb_set_owner_w.cold (STB_LOCAL)
ffffffff81d9ae80-ffffffff81d9af94: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81e0a144)
Location: net/core/sock.c:2523
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_expand_head
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff8212c0b8-ffffffff8212c0d1: skb_set_owner_w.cold (STB_LOCAL)
ffffffff81e0a090-ffffffff81e0a19a: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81ec6b34)
Location: net/core/sock.c:2503
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_expand_head
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff8220dd47-ffffffff8220dd60: skb_set_owner_w.cold (STB_LOCAL)
ffffffff81ec6a80-ffffffff81ec6b8a: skb_set_owner_w (STB_GLOBAL)
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
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baaa70)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffff800010baaa70-ffff800010baab24: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9d24)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
c0cc9d24-c0cc9dd0: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c81a30)
Location: net/core/sock.c:1986
Inline: True
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
c000000000c81a30-c000000000c81b68: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073ebf0)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffe00073ebf0-ffffffe00073ec88: skb_set_owner_w (STB_GLOBAL)
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
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3840)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff818b3840-ffffffff818b38e7: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186d790)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff8186d790-ffffffff8186d837: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904840)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81904840-ffffffff819048e7: skb_set_owner_w (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_set_owner_w(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819258e0)
Location: net/core/sock.c:1986
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:skb_cow_data
  - net/core/skmsg.c:sk_psock_strp_read
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff819258e0-ffffffff81925987: skb_set_owner_w (STB_GLOBAL)
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
