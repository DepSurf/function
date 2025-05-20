# Function: <code>trace_event_raw_event_fib6_table_lookup</code>

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
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817a9d00)
Location: include/trace/events/fib6.h:12
Inline: False
```
**Symbols:**

```
ffffffff817a9d00-ffffffff817a9e9e: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817d8840)
Location: include/trace/events/fib6.h:12
Inline: False
```
**Symbols:**

```
ffffffff817d8840-ffffffff817d89de: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817f60e0)
Location: include/trace/events/fib6.h:12
Inline: False
```
**Symbols:**

```
ffffffff817f60e0-ffffffff817f62ae: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81874d30)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81874d30-ffffffff81874ed1: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_info *f6i, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819703e0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819703e0-ffffffff819705ec: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_info *f6i, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6010)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819a6010-ffffffff819a621c: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12630)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a12630-ffffffff81a1283e: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49220)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a49220-ffffffff81a4942e: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3fd10)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81b3fd10-ffffffff81b3ff15: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4e7d0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81b4e7d0-ffffffff81b4e9d5: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3c620)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81b3c620-ffffffff81b3c801: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c02f30)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81c02f30-ffffffff81c03130: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9ce00)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81d9ce00-ffffffff81d9d029: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6bbb0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81f6bbb0-ffffffff81f6be17: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcbd00)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81fcbd00-ffffffff81fcbf59: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82099440)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff82099440-ffffffff820996a0: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
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
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0c550)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffff800010d0c550-ffff800010d0c73c: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e123e0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
c0e123e0-c0e125f8: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e371e0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
c000000000e371e0-c000000000e37460: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000853558)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffe000853558-ffffffe000853740: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
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
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e88b0)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819e88b0-ffffffff819e8abe: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5670)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff819a5670-ffffffff819a587e: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53330)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a53330-ffffffff81a5353e: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f280)
Location: include/trace/events/fib6.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a5f280-ffffffff81a5f48e: trace_event_raw_event_fib6_table_lookup (STB_LOCAL)
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
