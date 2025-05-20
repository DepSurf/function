# Function: <code>__bpf_trace_io_uring_cqe_overflow</code>

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
void __bpf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c6ea0)
Location: include/trace/events/io_uring.h:602
Inline: False
```
**Symbols:**

```
ffffffff816c6ea0-ffffffff816c6ec2: __bpf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81788430)
Location: include/trace/events/io_uring.h:574
Inline: False
```
**Symbols:**

```
ffffffff81788430-ffffffff81788452: __bpf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c8b40)
Location: include/trace/events/io_uring.h:571
Inline: False
```
**Symbols:**

```
ffffffff817c8b40-ffffffff817c8b62: __bpf_trace_io_uring_cqe_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_io_uring_cqe_overflow(void *__data, void *ctx, long long unsigned int user_data, s32 res, u32 cflags, void *ocqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180d810)
Location: include/trace/events/io_uring.h:571
Inline: False
```
**Symbols:**

```
ffffffff8180d810-ffffffff8180d832: __bpf_trace_io_uring_cqe_overflow (STB_LOCAL)
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
