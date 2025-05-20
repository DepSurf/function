# Function: <code>netif_rx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719680)
Location: net/core/dev.c:3581
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81719680-ffffffff817196ec: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781b60)
Location: net/core/dev.c:3834
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81781b60-ffffffff81781bc5: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817af470)
Location: net/core/dev.c:3830
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff817af470-ffffffff817af4d5: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cdd80)
Location: net/core/dev.c:3917
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff817cdd80-ffffffff817cdde5: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184aa50)
Location: net/core/dev.c:4117
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8184aa50-ffffffff8184aab8: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81894e20)
Location: net/core/dev.c:4238
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81894e20-ffffffff81894e88: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b5880)
Location: net/core/dev.c:4547
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818b5880-ffffffff818b592d: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ff1e0)
Location: net/core/dev.c:4544
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818ff1e0-ffffffff818ff28d: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81931550)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81931550-ffffffff819315fd: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06cd0)
Location: net/core/dev.c:4808
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a06cd0-ffffffff81a06d7a: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a08290)
Location: net/core/dev.c:4837
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:netif_rx_any_context
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a08290-ffffffff81a0831d: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee9f0)
Location: net/core/dev.c:4945
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:netif_rx_any_context
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819ee9f0-ffffffff819eea7d: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9fd20)
Location: net/core/dev.c:4936
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:netif_rx_any_context
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a9fd20-ffffffff81a9fda7: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c15810)
Location: net/core/dev.c:4999
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_loopback_xmit
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81c15810-ffffffff81c1590b: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc6bc0)
Location: net/core/dev.c:4986
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81dc6bc0-ffffffff81dc6cbb: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e35f60)
Location: net/core/dev.c:4961
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_loopback_xmit
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81e35f60-ffffffff81e3605b: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef4220)
Location: net/core/dev.c:5109
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_loopback_xmit
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81ef4220-ffffffff81ef431b: netif_rx (STB_GLOBAL)
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
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcfd28)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffff800010bcfd28-ffff800010bcfe38: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce60c8)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c0ce60c8-c0ce61ec: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cac9a0)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c000000000cac9a0-c000000000cacaec: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000759eae)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffe000759eae-ffffffe000759f8c: netif_rx (STB_GLOBAL)
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
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d1550)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818d1550-ffffffff818d15fd: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b3e0)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8188b3e0-ffffffff8188b48d: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81922550)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81922550-ffffffff819225fd: netif_rx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netif_rx(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819436a0)
Location: net/core/dev.c:4446
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/filter.c:__bpf_redirect
  - net/core/gro_cells.c:gro_cells_receive
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819436a0-ffffffff81943775: netif_rx (STB_GLOBAL)
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
