# Function: <code>perf_trace_io_uring_cqe_overflow</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c5a40)
Location: include/trace/events/io_uring.h:602
Inline: False
```
**Symbols:**

```
ffffffff816c5a40-ffffffff816c5b61: perf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81786a70)
Location: include/trace/events/io_uring.h:574
Inline: False
```
**Symbols:**

```
ffffffff81786a70-ffffffff81786b8e: perf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c6fb0)
Location: include/trace/events/io_uring.h:571
Inline: False
```
**Symbols:**

```
ffffffff817c6fb0-ffffffff817c70ce: perf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180bc80)
Location: include/trace/events/io_uring.h:571
Inline: False
```
**Symbols:**

```
ffffffff8180bc80-ffffffff8180bd9e: perf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
