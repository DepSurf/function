# Function: <code>lwtstate_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81723f1a)
Location: include/net/lwtunnel.h:40
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c344)
Location: include/net/lwtunnel.h:40
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:fib_nh_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8178d958)
Location: include/net/lwtunnel.h:40
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a32f)
Location: include/net/lwtunnel.h:40
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817d9720)
Location: net/core/lwtunnel.c:190
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
**Symbols:**

```
ffffffff817d9720-ffffffff817d9777: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817f8710)
Location: net/core/lwtunnel.c:210
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
**Symbols:**

```
ffffffff817f8710-ffffffff817f875a: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81875ff0)
Location: net/core/lwtunnel.c:212
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
**Symbols:**

```
ffffffff81875ff0-ffffffff8187603d: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818c7900)
Location: net/core/lwtunnel.c:212
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
**Symbols:**

```
ffffffff818c7900-ffffffff818c795a: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818f0a60)
Location: net/core/lwtunnel.c:212
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
**Symbols:**

```
ffffffff818f0a60-ffffffff818f0aba: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81942420)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81942420-ffffffff8194247d: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81977350)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81977350-ffffffff819773ad: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a4c140)
Location: net/core/lwtunnel.c:209
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a4c140-ffffffff81a4c19d: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a51d70)
Location: net/core/lwtunnel.c:209
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a51d70-ffffffff81a51dcd: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a37670)
Location: net/core/lwtunnel.c:209
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a37670-ffffffff81a376cd: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81aed390)
Location: net/core/lwtunnel.c:218
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81aed390-ffffffff81aed407: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81c70010)
Location: net/core/lwtunnel.c:218
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81c70010-ffffffff81c7009e: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e27f70)
Location: net/core/lwtunnel.c:221
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81e27f70-ffffffff81e27ffe: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e9d580)
Location: net/core/lwtunnel.c:221
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81e9d580-ffffffff81e9d60c: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81f5fd00)
Location: net/core/lwtunnel.c:221
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81f5fd00-ffffffff81f5fd8c: lwtstate_free (STB_GLOBAL)
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
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffff800010c1dcc8)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffff800010c1dcc8-ffff800010c1dd3c: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c0d3594c)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c0d3594c-c0d359ac: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c000000000d0f2a0)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c000000000d0f2a0-c000000000d0f398: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffe00079783a)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffe00079783a-ffffffe0007978a6: lwtstate_free (STB_GLOBAL)
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
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819171c0)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff819171c0-ffffffff8191721d: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818d0f70)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff818d0f70-ffffffff818d0fcd: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81968350)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81968350-ffffffff819683ad: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state *lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8198a610)
Location: net/core/lwtunnel.c:207
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff8198a610-ffffffff8198a66d: lwtstate_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
