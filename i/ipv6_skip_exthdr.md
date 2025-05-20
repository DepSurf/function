# Function: <code>ipv6_skip_exthdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff817ffb80)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff817ffb80-ffffffff817ffcf5: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81871220)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81871220-ffffffff81871395: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818a5770)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff818a5770-ffffffff818a58e5: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818cc200)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff818cc200-ffffffff818cc366: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81950fb0)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81950fb0-ffffffff81951116: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819aa530)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819aa530-ffffffff819aa69c: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e1040)
Location: net/ipv6/exthdrs_core.c:71
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819e1040-ffffffff819e11a0: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a4fe00)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a4fe00-ffffffff81a4ff61: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a86a50)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a86a50-ffffffff81a86bb1: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b81d00)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b81d00-ffffffff81b81e61: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b913f0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81b913f0-ffffffff81b91551: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b805f0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81b805f0-ffffffff81b80760: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81c4c610)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81c4c610-ffffffff81c4c780: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81dec9d0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81dec9d0-ffffffff81decb5a: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81fc07b0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81fc07b0-ffffffff81fc093a: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff82021720)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff82021720-ffffffff820218b5: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff820f0850)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff820f0850-ffffffff820f09d6: ipv6_skip_exthdr (STB_GLOBAL)
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
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffff800010d530c0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffff800010d530c0-ffff800010d5324c: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c0e53a34)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
c0e53a34-c0e53bc0: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c000000000e8b720)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
c000000000e8b720-c000000000e8b938: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffe00088ae70)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffe00088ae70-ffffffe00088afba: ipv6_skip_exthdr (STB_GLOBAL)
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
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a260e0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a260e0-ffffffff81a26241: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e2ea0)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819e2ea0-ffffffff819e3001: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a91c90)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/netfilter/nf_conntrack_core.c:get_l4proto
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a91c90-ffffffff81a91df1: ipv6_skip_exthdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_skip_exthdr(const struct sk_buff *skb, int start, u8 *nexthdrp, __be16 *frag_offp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a9dd40)
Location: net/ipv6/exthdrs_core.c:72
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a9dd40-ffffffff81a9dea1: ipv6_skip_exthdr (STB_GLOBAL)
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
