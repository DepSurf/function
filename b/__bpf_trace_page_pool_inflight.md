# Function: <code>__bpf_trace_page_pool_inflight</code>

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
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193c8e0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8193c8e0-ffffffff8193c8f2: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196f770)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8196f770-ffffffff8196f782: __bpf_trace_page_pool_inflight (STB_LOCAL)
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
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c14eb0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffff800010c14eb0-ffff800010c14ed0: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2dc80)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
c0d2dc80-c0d2dcc4: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d047e0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
c000000000d047e0-c000000000d04810: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190f740)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff8190f740-ffffffff8190f752: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c9500)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff818c9500-ffffffff818c9512: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81960770)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff81960770-ffffffff81960782: __bpf_trace_page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_page_pool_inflight(void *__data, const struct page_pool *pool, s32 inflight, u32 hold, u32 release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819829e0)
Location: include/trace/events/page_pool.h:13
Inline: False
```
**Symbols:**

```
ffffffff819829e0-ffffffff819829f2: __bpf_trace_page_pool_inflight (STB_LOCAL)
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
