# Function: <code>fib_info_update_nhc_saddr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c8d40)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff819c8d40-ffffffff819c8d85: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819ff900)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff819ff900-ffffffff819ff945: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aef48f)
Location: net/ipv4/fib_semantics.c:1289
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81aeee50-ffffffff81aeee95: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afc3e6)
Location: net/ipv4/fib_semantics.c:1289
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81afbdd0-ffffffff81afbe15: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae7bba)
Location: net/ipv4/fib_semantics.c:1290
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81ae7550-ffffffff81ae7595: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba7a47)
Location: net/ipv4/fib_semantics.c:1332
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81ba7390-ffffffff81ba73d5: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d3a40d)
Location: net/ipv4/fib_semantics.c:1317
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81d39d20-ffffffff81d39d79: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f02d6d)
Location: net/ipv4/fib_semantics.c:1323
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81f02660-ffffffff81f026b9: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f62791)
Location: net/ipv4/fib_semantics.c:1323
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff81f620c0-ffffffff81f62119: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff82028d61)
Location: net/ipv4/fib_semantics.c:1324
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
```
**Symbols:**

```
ffffffff82028690-ffffffff820286e9: fib_info_update_nhc_saddr (STB_GLOBAL)
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
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb7e78)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffff800010cb7e78-ffff800010cb7ef0: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc3264)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
c0dc3264-c0dc32b4: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dd06a0)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
c000000000dd06a0-c000000000dd0738: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080eef4)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffe00080eef4-ffffffe00080ef5e: fib_info_update_nhc_saddr (STB_GLOBAL)
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
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199f6a0)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff8199f6a0-ffffffff8199f6e5: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81959160)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81959160-ffffffff819591a5: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a09f40)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81a09f40-ffffffff81a09f85: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__be32 fib_info_update_nhc_saddr(struct net *net, struct fib_nh_common *nhc, unsigned char scope);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a14720)
Location: net/ipv4/fib_semantics.c:1280
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81a14720-ffffffff81a14765: fib_info_update_nhc_saddr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
