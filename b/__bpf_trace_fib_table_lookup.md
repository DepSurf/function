# Function: <code>__bpf_trace_fib_table_lookup</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh *nh, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c3850)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff818c3850-ffffffff818c3860: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh *nh, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ec750)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff818ec750-ffffffff818ec760: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193c8b0)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff8193c8b0-ffffffff8193c8c0: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196f740)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff8196f740-ffffffff8196f750: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a43650)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a43650-ffffffff81a43660: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a47250)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a47250-ffffffff81a47260: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a2bf00)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81a2bf00-ffffffff81a2bf10: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81ae0f80)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81ae0f80-ffffffff81ae0f90: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c65260)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81c65260-ffffffff81c6527f: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1bec0)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81e1bec0-ffffffff81e1bedf: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e90220)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81e90220-ffffffff81e9023f: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f525f0)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81f525f0-ffffffff81f5260f: __bpf_trace_fib_table_lookup (STB_LOCAL)
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
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c14e60)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffff800010c14e60-ffff800010c14e7c: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2dbb4)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
c0d2dbb4-c0d2dbf8: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d04750)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
c000000000d04750-c000000000d04780: __bpf_trace_fib_table_lookup (STB_LOCAL)
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
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190f710)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff8190f710-ffffffff8190f720: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c94d0)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff818c94d0-ffffffff818c94e0: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81960740)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff81960740-ffffffff81960750: __bpf_trace_fib_table_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_fib_table_lookup(void *__data, u32 tb_id, const struct flowi4 *flp, const struct fib_nh_common *nhc, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819829b0)
Location: include/trace/events/fib.h:13
Inline: False
```
**Symbols:**

```
ffffffff819829b0-ffffffff819829c0: __bpf_trace_fib_table_lookup (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fib_nh_common *nhc</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fib_nh *nh</code>
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
