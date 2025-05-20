# Function: <code>rt6_flush_exceptions</code>

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
void rt6_flush_exceptions(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191eff0)
Location: net/ipv6/route.c:1359
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff8191eff0-ffffffff8191f078: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81975780)
Location: net/ipv6/route.c:1497
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff81975780-ffffffff819757fe: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab3d0)
Location: net/ipv6/route.c:1506
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff819ab3d0-ffffffff819ab44e: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18d60)
Location: net/ipv6/route.c:1749
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff81a18d60-ffffffff81a18d97: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4f9c0)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff81a4f9c0-ffffffff81a4f9f7: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47130)
Location: net/ipv6/route.c:1777
Inline: False
```
**Symbols:**

```
ffffffff81b47130-ffffffff81b47167: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55d30)
Location: net/ipv6/route.c:1760
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81b55d30-ffffffff81b55d67: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43950)
Location: net/ipv6/route.c:1770
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81b43950-ffffffff81b43987: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0a4d0)
Location: net/ipv6/route.c:1773
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81c0a4d0-ffffffff81c0a507: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da51d0)
Location: net/ipv6/route.c:1773
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81da51d0-ffffffff81da521f: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f746e0)
Location: net/ipv6/route.c:1773
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81f746e0-ffffffff81f7472f: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd4780)
Location: net/ipv6/route.c:1772
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81fd4780-ffffffff81fd47cf: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a2090)
Location: net/ipv6/route.c:1774
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff820a2090-ffffffff820a20df: rt6_flush_exceptions (STB_GLOBAL)
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
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d138d8)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffff800010d138d8-ffff800010d1392c: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19478)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
c0e19478-c0e194bc: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40210)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
c000000000e40210-c000000000e4026c: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008593e4)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffe0008593e4-ffffffe000859432: rt6_flush_exceptions (STB_GLOBAL)
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
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef050)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff819ef050-ffffffff819ef087: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abe10)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff819abe10-ffffffff819abe47: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59ad0)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff81a59ad0-ffffffff81a59b07: rt6_flush_exceptions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt6_flush_exceptions(struct fib6_info *f6i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65d10)
Location: net/ipv6/route.c:1755
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff81a65d10-ffffffff81a65d47: rt6_flush_exceptions (STB_GLOBAL)
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
