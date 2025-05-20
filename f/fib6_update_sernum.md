# Function: <code>fib6_update_sernum</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib6_update_sernum(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81922e50)
Location: net/ipv6/ip6_fib.c:108
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81922e50-ffffffff81922ec5: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197b1c0)
Location: net/ipv6/ip6_fib.c:108
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff8197b1c0-ffffffff8197b203: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b0e90)
Location: net/ipv6/ip6_fib.c:110
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819b0e90-ffffffff819b0ed3: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1f150)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a1f150-ffffffff81a1f192: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a55dd0)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a55dd0-ffffffff81a55e12: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4e630)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
```
**Symbols:**

```
ffffffff81b4e630-ffffffff81b4e672: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5d2a0)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
```
**Symbols:**

```
ffffffff81b5d2a0-ffffffff81b5d2e2: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4b4e0)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81b4b4e0-ffffffff81b4b522: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12820)
Location: net/ipv6/ip6_fib.c:107
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81c12820-ffffffff81c12862: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dadd20)
Location: net/ipv6/ip6_fib.c:108
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81dadd20-ffffffff81dadd76: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7d7e0)
Location: net/ipv6/ip6_fib.c:107
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81f7d7e0-ffffffff81f7d828: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdd9f0)
Location: net/ipv6/ip6_fib.c:107
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81fdd9f0-ffffffff81fdda38: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820aaaa0)
Location: net/ipv6/ip6_fib.c:107
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff820aaaa0-ffffffff820aaae8: fib6_update_sernum (STB_GLOBAL)
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
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1a8b0)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffff800010d1a8b0-ffff800010d1a8ec: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1fd20)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
c0e1fd20-c0e1fd4c: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e48b80)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
c000000000e48b80-c000000000e48c24: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085ec34)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffe00085ec34-ffffffe00085eca2: fib6_update_sernum (STB_GLOBAL)
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
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f5460)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819f5460-ffffffff819f54a2: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b2220)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819b2220-ffffffff819b2262: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5fee0)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a5fee0-ffffffff81a5ff22: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib6_update_sernum(struct net *net, struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6c390)
Location: net/ipv6/ip6_fib.c:106
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a6c390-ffffffff81a6c3d2: fib6_update_sernum (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>struct fib6_info *f6i</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rt6_info *rt</code>
</li>
</ul>
</details>
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
