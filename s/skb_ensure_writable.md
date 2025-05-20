# Function: <code>skb_ensure_writable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81709960)
Location: net/core/skbuff.c:4391
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
**Symbols:**

```
ffffffff81709960-ffffffff81709a04: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81771cc0)
Location: net/core/skbuff.c:4465
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff81771cc0-ffffffff81771d64: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179edf0)
Location: net/core/skbuff.c:4509
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff8179edf0-ffffffff8179ee94: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bc560)
Location: net/core/skbuff.c:4603
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff817bc560-ffffffff817bc5ff: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81836c30)
Location: net/core/skbuff.c:5034
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff81836c30-ffffffff81836ccf: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81880d50)
Location: net/core/skbuff.c:5114
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff81880d50-ffffffff81880df4: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a1c00)
Location: net/core/skbuff.c:5142
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff818a1c00-ffffffff818a1c98: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ec5e0)
Location: net/core/skbuff.c:5335
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff818ec5e0-ffffffff818ec677: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191e710)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff8191e710-ffffffff8191e7a7: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f0f90)
Location: net/core/skbuff.c:5449
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff819f0f90-ffffffff819f102c: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f0f20)
Location: net/core/skbuff.c:5517
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff819f0f20-ffffffff819f0fbc: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d61e0)
Location: net/core/skbuff.c:5605
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff819d61e0-ffffffff819d627c: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a86820)
Location: net/core/skbuff.c:5680
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81a86820-ffffffff81a868bc: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, unsigned int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfbf30)
Location: net/core/skbuff.c:5601
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81bfbf30-ffffffff81bfbfe8: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, unsigned int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daade0)
Location: net/core/skbuff.c:5803
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81daade0-ffffffff81daae98: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, unsigned int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1a960)
Location: net/core/skbuff.c:5860
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81e1a960-ffffffff81e1aa18: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, unsigned int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed8000)
Location: net/core/skbuff.c:5988
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
**Symbols:**

```
ffffffff81ed8000-ffffffff81ed80b8: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb8eb8)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffff800010bb8eb8-ffff800010bb8f90: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd597c)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
c0cd597c-c0cd5a40: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c91330)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
c000000000c91330-c000000000c91438: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000748508)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffe000748508-ffffffe0007485b6: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818be710)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff818be710-ffffffff818be7a7: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81878650)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff81878650-ffffffff818786e7: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190f710)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
**Symbols:**

```
ffffffff8190f710-ffffffff8190f7a7: skb_ensure_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int skb_ensure_writable(struct sk_buff *skb, int write_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81930840)
Location: net/core/skbuff.c:5347
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
**Symbols:**

```
ffffffff81930840-ffffffff819308d7: skb_ensure_writable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int write_len</code> ➡️ <code>unsigned int write_len</code>
</li>
</ul>
</details>
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
