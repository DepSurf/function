# Function: <code>skb_checksum_help</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718ca0)
Location: net/core/dev.c:2429
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81718ca0-ffffffff81718e28: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780550)
Location: net/core/dev.c:2451
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_csum_offload_chk
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81780550-ffffffff817806d8: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817adea0)
Location: net/core/dev.c:2583
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff817adea0-ffffffff817ae035: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817caa30)
Location: net/core/dev.c:2599
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff817caa30-ffffffff817cabd3: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818460a0)
Location: net/core/dev.c:2626
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff818460a0-ffffffff81846243: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f550)
Location: net/core/dev.c:2668
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff8188f550-ffffffff8188f6fb: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aed70)
Location: net/core/dev.c:2905
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff818aed70-ffffffff818aeeff: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fbd40)
Location: net/core/dev.c:2913
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff818fbd40-ffffffff818fbeec: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192e2e0)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff8192e2e0-ffffffff8192e48c: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a028b0)
Location: net/core/dev.c:3193
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a028b0-ffffffff81a029e7: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03130)
Location: net/core/dev.c:3218
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a03130-ffffffff81a03267: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e98f0)
Location: net/core/dev.c:3286
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff819e98f0-ffffffff819e9a22: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9a570)
Location: net/core/dev.c:3213
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a9a570-ffffffff81a9a6a2: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3248
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81f02797-ffffffff81f027c1: skb_checksum_help.cold (STB_LOCAL)
ffffffff81c121e0-ffffffff81c1237f: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3235
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff820ab39d-ffffffff820ab3c7: skb_checksum_help.cold (STB_LOCAL)
ffffffff81dc25c0-ffffffff81dc275f: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3264
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff8212cd66-ffffffff8212cd90: skb_checksum_help.cold (STB_LOCAL)
ffffffff81e3a1e0-ffffffff81e3a37f: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3267
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/xdp/xsk.c:xsk_build_skb
```
**Symbols:**

```
ffffffff8220eaa5-ffffffff8220eaf9: skb_checksum_help.cold (STB_LOCAL)
ffffffff81ef84f0-ffffffff81ef870d: skb_checksum_help (STB_GLOBAL)
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
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc98d0)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffff800010bc98d0-ffff800010bc9a74: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce7b0c)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c0ce7b0c-c0ce7c94: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca7580)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c000000000ca7580-c000000000ca77c4: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000756f7e)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffe000756f7e-ffffffe0007570e0: skb_checksum_help (STB_GLOBAL)
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
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ce2e0)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff818ce2e0-ffffffff818ce48c: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81888400)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81888400-ffffffff818885ac: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191f2e0)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff8191f2e0-ffffffff8191f48c: skb_checksum_help (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_checksum_help(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941040)
Location: net/core/dev.c:2831
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81941040-ffffffff819411ec: skb_checksum_help (STB_GLOBAL)
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
