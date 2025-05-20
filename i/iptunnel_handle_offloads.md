# Function: <code>iptunnel_handle_offloads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *iptunnel_handle_offloads(struct sk_buff *skb, bool csum_help, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4a00)
Location: net/ipv4/ip_tunnel_core.c:150
Inline: False
```
**Symbols:**

```
ffffffff817a4a00-ffffffff817a4b05: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81812710)
Location: net/ipv4/ip_tunnel_core.c:169
Inline: True
```
**Symbols:**

```
ffffffff81812710-ffffffff818127df: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81843c10)
Location: net/ipv4/ip_tunnel_core.c:158
Inline: True
```
**Symbols:**

```
ffffffff81843c10-ffffffff81843cdf: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff818654a0)
Location: net/ipv4/ip_tunnel_core.c:160
Inline: True
```
**Symbols:**

```
ffffffff818654a0-ffffffff8186556e: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff818e55f0)
Location: net/ipv4/ip_tunnel_core.c:160
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff818e55f0-ffffffff818e56be: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bea0)
Location: net/ipv4/ip_tunnel_core.c:160
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff8193bea0-ffffffff8193bf55: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bbc0)
Location: net/ipv4/ip_tunnel_core.c:161
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff8196bbc0-ffffffff8196bc72: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2900)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff819d2900-ffffffff819d29c3: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81a09470)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a09470-ffffffff81a09533: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8d90)
Location: net/ipv4/ip_tunnel_core.c:155
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81af8d90-ffffffff81af8e59: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05b60)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81b05b60-ffffffff81b05c29: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81af13e0)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81af13e0-ffffffff81af149f: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb18f0)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81bb18f0-ffffffff81bb19af: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44f90)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81d44f90-ffffffff81d45054: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e420)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81f0e420-ffffffff81f0e4e4: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e0d0)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81f6e0d0-ffffffff81f6e194: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff820347e0)
Location: net/ipv4/ip_tunnel_core.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff820347e0-ffffffff820348a4: iptunnel_handle_offloads (STB_GLOBAL)
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
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffff800010cc27f0)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffff800010cc27f0-ffff800010cc28d0: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (c0dcdf38)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
c0dcdf38-c0dce000: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (c000000000dde000)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
c000000000dde000-c000000000dde12c: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffe000817bb2)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffe000817bb2-ffffffe000817c7c: iptunnel_handle_offloads (STB_GLOBAL)
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
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9210)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff819a9210-ffffffff819a92d3: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81962cd0)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - drivers/net/vxlan.c:vxlan_build_skb
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81962cd0-ffffffff81962d93: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13ab0)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a13ab0-ffffffff81a13b73: iptunnel_handle_offloads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int iptunnel_handle_offloads(struct sk_buff *skb, int gso_type_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e490)
Location: net/ipv4/ip_tunnel_core.c:151
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a1e490-ffffffff81a1e553: iptunnel_handle_offloads (STB_GLOBAL)
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
<b>Param removed. </b>
<code>bool csum_help</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, csum_help, gso_type_mask</code> ➡️ <code>skb, gso_type_mask</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff *</code> ➡️ <code>int</code>
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
