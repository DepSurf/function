# Function: <code>ipv6_ext_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff817ffac0)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff817ffac0-ffffffff817ffae5: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff8187171c)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81871170-ffffffff81871199: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818a5c6c)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff818a56c0-ffffffff818a56e9: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818cc6cf)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff818cc150-ffffffff818cc175: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff8195147f)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81950f00-ffffffff81950f25: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819aaa2b)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff819aa480-ffffffff819aa4a5: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e1510)
Location: net/ipv6/exthdrs_core.c:12
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff819e0f90-ffffffff819e0fb5: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a502b9)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81a4fd40-ffffffff81a4fd65: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a86ef7)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81a86990-ffffffff81a869b5: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b821a7)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81b81c40-ffffffff81b81c65: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b91897)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81b91330-ffffffff81b91355: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b80530)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81b80530-ffffffff81b80557: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81c4c550)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81c4c550-ffffffff81c4c577: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81dec8f0)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81dec8f0-ffffffff81dec922: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81fc06b0)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81fc06b0-ffffffff81fc06e2: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff82021630)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
**Symbols:**

```
ffffffff82021630-ffffffff8202165a: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff820f0760)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
**Symbols:**

```
ffffffff820f0760-ffffffff820f078a: ipv6_ext_hdr (STB_GLOBAL)
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
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffff800010d5356c)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffff800010d52fb8-ffff800010d53004: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c0e53f24)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
c0e53958-c0e53998: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c000000000e8bd78)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
c000000000e8b620-c000000000e8b658: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffe00088b24a)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffe00088adb8-ffffffe00088adf0: ipv6_ext_hdr (STB_GLOBAL)
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
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a26587)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81a26020-ffffffff81a26045: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e3347)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff819e2de0-ffffffff819e2e05: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a92137)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
**Symbols:**

```
ffffffff81a91bd0-ffffffff81a91bf5: ipv6_ext_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ipv6_ext_hdr(u8 nexthdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a9e1e7)
Location: net/ipv6/exthdrs_core.c:13
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81a9dc80-ffffffff81a9dca5: ipv6_ext_hdr (STB_GLOBAL)
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
