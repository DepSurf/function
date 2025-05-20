# Function: <code>fib6_nh_age_exceptions</code>

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
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a165c0)
Location: net/ipv6/route.c:2092
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81a165c0-ffffffff81a1676c: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4d200)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81a4d200-ffffffff81a4d3ae: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b471c4)
Location: net/ipv6/route.c:2120
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81b43190-ffffffff81b4322c: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55dc4)
Location: net/ipv6/route.c:2103
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81b51880-ffffffff81b5191c: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b439e4)
Location: net/ipv6/route.c:2110
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81b3f540-ffffffff81b3f6e7: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0a564)
Location: net/ipv6/route.c:2113
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81c05b00-ffffffff81c05cc1: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
ffffffff81d3fc73-ffffffff81d3fcac: fib6_nh_age_exceptions.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81da527e)
Location: net/ipv6/route.c:2113
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81da0170-ffffffff81da036c: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
ffffffff81f0c5f1-ffffffff81f0c62a: fib6_nh_age_exceptions.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81f7479e)
Location: net/ipv6/route.c:2113
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81f6f3b0-ffffffff81f6f5ac: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
ffffffff820b3c42-ffffffff820b3c7b: fib6_nh_age_exceptions.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd483e)
Location: net/ipv6/route.c:2112
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81fcf490-ffffffff81fcf68c: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
ffffffff82134d57-ffffffff82134d90: fib6_nh_age_exceptions.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff820a214e)
Location: net/ipv6/route.c:2114
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff8209ccf0-ffffffff8209ceec: fib6_nh_age_exceptions.part.0 (STB_LOCAL)
ffffffff8221681b-ffffffff82216854: fib6_nh_age_exceptions.part.0.cold (STB_LOCAL)
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
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d10f40)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffff800010d10f40-ffff800010d11160: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e16164)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
c0e16164-c0e1639c: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3c130)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
c000000000e3c130-c000000000e3c3b0: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000856a0c)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffe000856a0c-ffffffe000856bf6: fib6_nh_age_exceptions (STB_LOCAL)
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
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec890)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff819ec890-ffffffff819eca3e: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9650)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff819a9650-ffffffff819a97fe: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a57310)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81a57310-ffffffff81a574be: fib6_nh_age_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fib6_nh_age_exceptions(const struct fib6_nh *nh, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a633c0)
Location: net/ipv6/route.c:2098
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_nh_age_exceptions
```
**Symbols:**

```
ffffffff81a633c0-ffffffff81a6356c: fib6_nh_age_exceptions (STB_LOCAL)
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
