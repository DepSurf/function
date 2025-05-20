# Function: <code>perf_trace_io_uring_complete</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137a090)
Location: include/trace/events/io_uring.h:295
Inline: False
```
**Symbols:**

```
ffffffff8137a090-ffffffff8137a177: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388360)
Location: include/trace/events/io_uring.h:295
Inline: False
```
**Symbols:**

```
ffffffff81388360-ffffffff81388447: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138f480)
Location: include/trace/events/io_uring.h:296
Inline: False
```
**Symbols:**

```
ffffffff8138f480-ffffffff8138f570: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dcd10)
Location: include/trace/events/io_uring.h:296
Inline: False
```
**Symbols:**

```
ffffffff813dcd10-ffffffff813dce00: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c5910)
Location: include/trace/events/io_uring.h:340
Inline: False
```
**Symbols:**

```
ffffffff816c5910-ffffffff816c5a3f: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81786930)
Location: include/trace/events/io_uring.h:326
Inline: False
```
**Symbols:**

```
ffffffff81786930-ffffffff81786a5c: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c6e70)
Location: include/trace/events/io_uring.h:326
Inline: False
```
**Symbols:**

```
ffffffff817c6e70-ffffffff817c6f9c: perf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180bb40)
Location: include/trace/events/io_uring.h:326
Inline: False
```
**Symbols:**

```
ffffffff8180bb40-ffffffff8180bc6c: perf_trace_io_uring_complete (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cflags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int res</code> ➡️ <code>int res</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *req</code>
</li>
<li>
<b>Param added. </b>
<code>u64 extra1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 extra2</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, user_data, res, cflags</code> ➡️ <code>__data, ctx, req, user_data, res, cflags, extra1, extra2</code>
</li>
</ul>
</details>
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
