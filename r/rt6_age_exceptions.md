# Function: <code>rt6_age_exceptions</code>

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
void rt6_age_exceptions(struct rt6_info *rt, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191f170)
Location: net/ipv6/route.c:1648
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff8191f170-ffffffff8191f331: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *rt, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81975800)
Location: net/ipv6/route.c:1787
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81975800-ffffffff819759af: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *rt, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab450)
Location: net/ipv6/route.c:1778
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff819ab450-ffffffff819ab5ff: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18da0)
Location: net/ipv6/route.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81a18da0-ffffffff81a18e07: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4fa00)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81a4fa00-ffffffff81a4fa67: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47170)
Location: net/ipv6/route.c:2162
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81b47170-ffffffff81b471e3: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55d70)
Location: net/ipv6/route.c:2145
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81b55d70-ffffffff81b55de3: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43990)
Location: net/ipv6/route.c:2152
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81b43990-ffffffff81b43a03: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0a510)
Location: net/ipv6/route.c:2155
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81c0a510-ffffffff81c0a583: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da5220)
Location: net/ipv6/route.c:2155
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81da5220-ffffffff81da529d: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f74740)
Location: net/ipv6/route.c:2155
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81f74740-ffffffff81f747bd: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd47e0)
Location: net/ipv6/route.c:2154
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81fd47e0-ffffffff81fd485d: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a20f0)
Location: net/ipv6/route.c:2156
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff820a20f0-ffffffff820a216d: rt6_age_exceptions (STB_GLOBAL)
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
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13930)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffff800010d13930-ffff800010d139bc: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e194bc)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
c0e194bc-c0e19548: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40270)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
c000000000e40270-c000000000e40304: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859432)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffe000859432-ffffffe00085949c: rt6_age_exceptions (STB_GLOBAL)
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
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef090)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff819ef090-ffffffff819ef0f7: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abe50)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff819abe50-ffffffff819abeb7: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59b10)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81a59b10-ffffffff81a59b77: rt6_age_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt6_age_exceptions(struct fib6_info *f6i, struct fib6_gc_args *gc_args, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65d50)
Location: net/ipv6/route.c:2140
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
**Symbols:**

```
ffffffff81a65d50-ffffffff81a65db7: rt6_age_exceptions (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib6_info *f6i</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *rt</code>
</li>
</ul>
</details>
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
