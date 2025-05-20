# Function: <code>skb_scrub_packet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817062d0)
Location: net/core/skbuff.c:4286
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff817062d0-ffffffff817063d5: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176cc30)
Location: net/core/skbuff.c:4327
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8176cc30-ffffffff8176cd25: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a0b0)
Location: net/core/skbuff.c:4371
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8179a0b0-ffffffff8179a1a5: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b9370)
Location: net/core/skbuff.c:4465
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff817b9370-ffffffff817b946c: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818321f0)
Location: net/core/skbuff.c:4858
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818321f0-ffffffff81832302: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187c990)
Location: net/core/skbuff.c:4897
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8187c990-ffffffff8187caa1: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d3c0)
Location: net/core/skbuff.c:4919
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8189d3c0-ffffffff8189d492: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7c40)
Location: net/core/skbuff.c:5104
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818e7c40-ffffffff818e7d0a: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919e60)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81919e60-ffffffff81919f08: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec030)
Location: net/core/skbuff.c:5218
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819ec030-ffffffff819ec0de: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb840)
Location: net/core/skbuff.c:5285
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_channel_bridge_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819eb840-ffffffff819eb8ee: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1e30)
Location: net/core/skbuff.c:5373
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819d1e30-ffffffff819d1ede: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81ab0)
Location: net/core/skbuff.c:5448
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a81ab0-ffffffff81a81b5e: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf62a0)
Location: net/core/skbuff.c:5369
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81bf62a0-ffffffff81bf6384: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da4b90)
Location: net/core/skbuff.c:5571
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81da4b90-ffffffff81da4c74: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13800)
Location: net/core/skbuff.c:5769
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81e13800-ffffffff81e13907: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed0830)
Location: net/core/skbuff.c:5897
Inline: True
Direct callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81ed0830-ffffffff81ed0937: skb_scrub_packet (STB_GLOBAL)
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
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3d50)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffff800010bb3d50-ffff800010bb3e2c: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd0ccc)
Location: net/core/skbuff.c:5116
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c0cd0ccc-c0cd0dc0: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8a520)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c000000000c8a520-c000000000c8a664: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744792)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffe000744792-ffffffe000744860: skb_scrub_packet (STB_GLOBAL)
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
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9e60)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818b9e60-ffffffff818b9f08: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873db0)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81873db0-ffffffff81873e58: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190ae60)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8190ae60-ffffffff8190af08: skb_scrub_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff *skb, bool xnet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192bf60)
Location: net/core/skbuff.c:5116
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8192bf60-ffffffff8192c008: skb_scrub_packet (STB_GLOBAL)
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
