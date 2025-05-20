# Function: <code>fib6_update_sernum_upto_root</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819234d6)
Location: net/ipv6/ip6_fib.c:1110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197b480)
Location: net/ipv6/ip6_fib.c:1187
Inline: False
```
**Symbols:**

```
ffffffff8197b480-ffffffff8197b4ca: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1160)
Location: net/ipv6/ip6_fib.c:1221
Inline: False
```
**Symbols:**

```
ffffffff819b1160-ffffffff819b11aa: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1fcf0)
Location: net/ipv6/ip6_fib.c:1282
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffff81a1fcf0-ffffffff81a1fd3a: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a56950)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffff81a56950-ffffffff81a5699a: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4eb3e)
Location: net/ipv6/ip6_fib.c:1348
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81b4ead0-ffffffff81b4eb1c: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5d7be)
Location: net/ipv6/ip6_fib.c:1351
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81b5d750-ffffffff81b5d79c: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4ba1e)
Location: net/ipv6/ip6_fib.c:1352
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81b4b9b0-ffffffff81b4b9fa: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12d7e)
Location: net/ipv6/ip6_fib.c:1354
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81c12d10-ffffffff81c12d5a: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dae2fe)
Location: net/ipv6/ip6_fib.c:1355
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81dae280-ffffffff81dae2de: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7de2e)
Location: net/ipv6/ip6_fib.c:1354
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81f7ddc0-ffffffff81f7ddf8: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fde03e)
Location: net/ipv6/ip6_fib.c:1354
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff81fddfd0-ffffffff81fde008: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820abbbe)
Location: net/ipv6/ip6_fib.c:1354
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
Direct callers:
  - net/ipv6/route.c:fib6_ifup
```
**Symbols:**

```
ffffffff820abb50-ffffffff820abb88: fib6_update_sernum_upto_root (STB_GLOBAL)
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
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1b4bc)
Location: net/ipv6/ip6_fib.c:1283
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffff800010d1b410-ffff800010d1b458: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e2090c)
Location: net/ipv6/ip6_fib.c:1283
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
c0e208a4-c0e208e4: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e49a20)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
c000000000e49a20-c000000000e49ae4: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085f566)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffe00085f566-ffffffe00085f5d8: fib6_update_sernum_upto_root (STB_GLOBAL)
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
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f5fe0)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffff819f5fe0-ffffffff819f602a: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b2da0)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffff819b2da0-ffffffff819b2dea: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a60a60)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffff81a60a60-ffffffff81a60aaa: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6cf20)
Location: net/ipv6/ip6_fib.c:1283
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
```
**Symbols:**

```
ffffffff81a6cf20-ffffffff81a6cf6a: fib6_update_sernum_upto_root (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
