# Function: <code>fib_select_multipath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179e316)
Location: net/ipv4/fib_semantics.c:1563
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8179e5b0-ffffffff8179e5f5: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8180bf70)
Location: net/ipv4/fib_semantics.c:1593
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8180bf70-ffffffff8180c0c1: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183d090)
Location: net/ipv4/fib_semantics.c:1598
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8183d090-ffffffff8183d1e1: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185e740)
Location: net/ipv4/fib_semantics.c:1701
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8185e740-ffffffff8185e89a: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818de7a0)
Location: net/ipv4/fib_semantics.c:1742
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff818de7a0-ffffffff818de8ff: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81935310)
Location: net/ipv4/fib_semantics.c:1705
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81935310-ffffffff8193546f: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81964d10)
Location: net/ipv4/fib_semantics.c:1742
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81964d10-ffffffff81964e68: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819caa50)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff819caa50-ffffffff819cacf1: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a01640)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81a01640-ffffffff81a018e1: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af0650)
Location: net/ipv4/fib_semantics.c:2176
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81af0650-ffffffff81af0902: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afd640)
Location: net/ipv4/fib_semantics.c:2175
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81afd640-ffffffff81afd8f2: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae8e80)
Location: net/ipv4/fib_semantics.c:2178
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81ae8e80-ffffffff81ae912c: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2219
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81d3d0bb-ffffffff81d3d1af: fib_select_multipath.cold (STB_LOCAL)
ffffffff81ba8ea0-ffffffff81ba9167: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2207
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81f09907-ffffffff81f099f6: fib_select_multipath.cold (STB_LOCAL)
ffffffff81d3b8f0-ffffffff81d3bbf6: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2213
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff820b11e2-ffffffff820b12d1: fib_select_multipath.cold (STB_LOCAL)
ffffffff81f042d0-ffffffff81f045d6: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2213
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8213246d-ffffffff8213255f: fib_select_multipath.cold (STB_LOCAL)
ffffffff81f63cb0-ffffffff81f63f91: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2221
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff82213e2b-ffffffff82213f1d: fib_select_multipath.cold (STB_LOCAL)
ffffffff8202a280-ffffffff8202a561: fib_select_multipath (STB_GLOBAL)
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
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb9c68)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffff800010cb9c68-ffff800010cb9ee8: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc5470)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
c0dc5470-c0dc576c: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dd2d70)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
c000000000dd2d70-c000000000dd3104: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe000810750)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffe000810750-ffffffe0008109b2: fib_select_multipath (STB_GLOBAL)
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
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819a13e0)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff819a13e0-ffffffff819a1681: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8195aea0)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8195aea0-ffffffff8195b141: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a0bc80)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81a0bc80-ffffffff81a0bf21: fib_select_multipath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib_select_multipath(struct fib_result *res, int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a16470)
Location: net/ipv4/fib_semantics.c:2158
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81a16470-ffffffff81a16711: fib_select_multipath (STB_GLOBAL)
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
