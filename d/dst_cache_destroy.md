# Function: <code>dst_cache_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817aada0)
Location: net/core/dst_cache.c:156
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
```
**Symbols:**

```
ffffffff817aada0-ffffffff817aae0b: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817da3c0)
Location: net/core/dst_cache.c:156
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff817da3c0-ffffffff817da42d: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817f9630)
Location: net/core/dst_cache.c:156
Inline: True
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff817f9630-ffffffff817f969d: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81876f50)
Location: net/core/dst_cache.c:156
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff81876f50-ffffffff81876fb4: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818c8670)
Location: net/core/dst_cache.c:156
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff818c8670-ffffffff818c86d3: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818f35a0)
Location: net/core/dst_cache.c:156
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff818f35a0-ffffffff818f3603: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81945a30)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff81945a30-ffffffff81945a8d: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8197aa50)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff8197aa50-ffffffff8197aaad: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a4ff10)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff81a4ff10-ffffffff81a4ff6d: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a55f50)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff81a55f50-ffffffff81a55fad: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a38f60)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff81a38f60-ffffffff81a38fbd: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81aeef20)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff81aeef20-ffffffff81aeef9f: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81c71ed0)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state
```
**Symbols:**

```
ffffffff81c71ed0-ffffffff81c71f58: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e2a010)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state
```
**Symbols:**

```
ffffffff81e2a010-ffffffff81e2a0ae: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e9f680)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state
```
**Symbols:**

```
ffffffff81e9f680-ffffffff81e9f71e: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81f61df0)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state
```
**Symbols:**

```
ffffffff81f61df0-ffffffff81f61e8e: dst_cache_destroy (STB_GLOBAL)
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
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffff800010c21f58)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffff800010c21f58-ffff800010c21fec: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c0d39338)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
c0d39338-c0d393b8: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c000000000d14560)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
c000000000d14560-c000000000d14630: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffe00079ac04)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffe00079ac04-ffffffe00079ac94: dst_cache_destroy (STB_GLOBAL)
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
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8191a8c0)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff8191a8c0-ffffffff8191a91d: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818d4670)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - drivers/net/vxlan.c:vxlan_dst_free
  - drivers/net/vxlan.c:__vxlan_fdb_free
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv4/ip_tunnel.c:ip_tunnel_init
  - net/ipv4/ip_tunnel.c:ip_tunnel_dev_free
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff818d4670-ffffffff818d46cd: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8196ba50)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff8196ba50-ffffffff8196baad: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dst_cache_destroy(struct dst_cache *dst_cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8198ded0)
Location: net/core/dst_cache.c:152
Inline: True
Direct callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free
  - net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state
  - net/ipv6/seg6_iptunnel.c:seg6_destroy_state
```
**Symbols:**

```
ffffffff8198ded0-ffffffff8198df2d: dst_cache_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
