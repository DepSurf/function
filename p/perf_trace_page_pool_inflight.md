# Function: <code>perf_trace_page_pool_inflight</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193b5a0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8193b5a0-ffffffff8193b686: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196e430)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8196e430-ffffffff8196e516: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c16808)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffff800010c16808-ffff800010c168e8: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2c578)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
c0d2c578-c0d2c670: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d02670)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
c000000000d02670-c000000000d027d8: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe00078fe5a)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffe00078fe5a-ffffffe00078fef0: perf_trace_page_pool_inflight (STB_LOCAL)
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
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190e400)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8190e400-ffffffff8190e4e6: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c81c0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff818c81c0-ffffffff818c82a6: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8195f430)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8195f430-ffffffff8195f516: perf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819816a0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff819816a0-ffffffff81981786: perf_trace_page_pool_inflight (STB_LOCAL)
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
