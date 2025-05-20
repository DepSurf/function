# Function: <code>dst_cache_set_ip4</code>

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
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817ab020)
Location: net/core/dst_cache.c:94
Inline: False
```
**Symbols:**

```
ffffffff817ab020-ffffffff817ab071: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817da640)
Location: net/core/dst_cache.c:94
Inline: False
```
**Symbols:**

```
ffffffff817da640-ffffffff817da691: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817f9820)
Location: net/core/dst_cache.c:94
Inline: False
```
**Symbols:**

```
ffffffff817f9820-ffffffff817f989e: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81877140)
Location: net/core/dst_cache.c:94
Inline: False
```
**Symbols:**

```
ffffffff81877140-ffffffff818771be: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818c8870)
Location: net/core/dst_cache.c:94
Inline: False
```
**Symbols:**

```
ffffffff818c8870-ffffffff818c88e7: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818f3790)
Location: net/core/dst_cache.c:94
Inline: False
```
**Symbols:**

```
ffffffff818f3790-ffffffff818f3807: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (0)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffff81945c91-ffffffff81945c9b: dst_cache_set_ip4.cold (STB_LOCAL)
ffffffff81945c00-ffffffff81945c61: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8197ac10)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffff8197ac10-ffffffff8197ac71: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a500d0)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81a500d0-ffffffff81a50131: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a56110)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81a56110-ffffffff81a56171: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a39120)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81a39120-ffffffff81a39181: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81aef100)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81aef100-ffffffff81aef161: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81c72100)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81c72100-ffffffff81c7216d: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e2a2a0)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81e2a2a0-ffffffff81e2a30d: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e9f940)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_tunnel
```
**Symbols:**

```
ffffffff81e9f940-ffffffff81e9f9af: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81f620b0)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffff81f620b0-ffffffff81f6211f: dst_cache_set_ip4 (STB_GLOBAL)
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
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffff800010c222b0)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffff800010c222b0-ffff800010c2235c: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c0d39648)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
c0d39648-c0d396f0: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c000000000d148b0)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
c000000000d148b0-c000000000d14964: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffe00079ae5c)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffe00079ae5c-ffffffe00079aee2: dst_cache_set_ip4 (STB_GLOBAL)
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
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8191aa80)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffff8191aa80-ffffffff8191aae1: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818d4830)
Location: net/core/dst_cache.c:90
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_get_route
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
**Symbols:**

```
ffffffff818d4830-ffffffff818d4891: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8196bc10)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffff8196bc10-ffffffff8196bc71: dst_cache_set_ip4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dst_cache_set_ip4(struct dst_cache *dst_cache, struct dst_entry *dst, __be32 saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8198e090)
Location: net/core/dst_cache.c:90
Inline: False
```
**Symbols:**

```
ffffffff8198e090-ffffffff8198e0f1: dst_cache_set_ip4 (STB_GLOBAL)
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
