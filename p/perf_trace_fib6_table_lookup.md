# Function: <code>perf_trace_fib6_table_lookup</code>

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
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817a8ee0)
Location: include/trace/events/fib6.h:12
Inline: False
```
**Symbols:**

```
ffffffff817a8ee0-ffffffff817a90ae: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817d7a20)
Location: include/trace/events/fib6.h:12
Inline: False
```
**Symbols:**

```
ffffffff817d7a20-ffffffff817d7bec: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817f5ee0)
Location: include/trace/events/fib6.h:12
Inline: False
```
**Symbols:**

```
ffffffff817f5ee0-ffffffff817f60d8: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81872380)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81872380-ffffffff81872544: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_info *f6i, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819701b0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819701b0-ffffffff819703e0: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_info *f6i, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5de0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819a5de0-ffffffff819a6010: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12400)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a12400-ffffffff81a1262e: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a48ff0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a48ff0-ffffffff81a4921e: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3fad0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81b3fad0-ffffffff81b3fd04: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4e590)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81b4e590-ffffffff81b4e7c4: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3c3f0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81b3c3f0-ffffffff81b3c619: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c02ce0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81c02ce0-ffffffff81c02f2f: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9cb70)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81d9cb70-ffffffff81d9cdf8: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6b8e0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81f6b8e0-ffffffff81f6bb9c: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcba30)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81fcba30-ffffffff81fcbce3: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82099170)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff82099170-ffffffff8209942a: perf_trace_fib6_table_lookup (STB_LOCAL)
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
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0f818)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffff800010d0f818-ffff800010d0fa20: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e121b8)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
c0e121b8-c0e123e0: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e36f10)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
c000000000e36f10-c000000000e371dc: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085337a)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffe00085337a-ffffffe000853558: perf_trace_fib6_table_lookup (STB_LOCAL)
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
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8680)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819e8680-ffffffff819e88ae: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5440)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819a5440-ffffffff819a566e: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53100)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a53100-ffffffff81a5332e: perf_trace_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f050)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a5f050-ffffffff81a5f27e: perf_trace_fib6_table_lookup (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib6_table *table</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 tb_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fib6_info *f6i</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct rt6_info *rt</code>
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
<code>const struct fib6_result *res</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fib6_info *f6i</code>
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
