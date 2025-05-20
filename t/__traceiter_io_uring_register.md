# Function: <code>__traceiter_io_uring_register</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, bool eventfd, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81387660)
Location: include/trace/events/io_uring.h:67
Inline: False
```
**Symbols:**

```
ffffffff81387660-ffffffff813876d0: __traceiter_io_uring_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, bool eventfd, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e720)
Location: include/trace/events/io_uring.h:67
Inline: False
```
**Symbols:**

```
ffffffff8138e720-ffffffff8138e78e: __traceiter_io_uring_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, bool eventfd, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dbf80)
Location: include/trace/events/io_uring.h:67
Inline: False
```
**Symbols:**

```
ffffffff813dbf80-ffffffff813dbfee: __traceiter_io_uring_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c4620)
Location: include/trace/events/io_uring.h:68
Inline: False
```
**Symbols:**

```
ffffffff816c4620-ffffffff816c469f: __traceiter_io_uring_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81785b40)
Location: include/trace/events/io_uring.h:69
Inline: False
```
**Symbols:**

```
ffffffff81785b40-ffffffff81785bbf: __traceiter_io_uring_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c5fd0)
Location: include/trace/events/io_uring.h:69
Inline: False
```
**Symbols:**

```
ffffffff817c5fd0-ffffffff817c604f: __traceiter_io_uring_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_io_uring_register(void *__data, void *ctx, unsigned int opcode, unsigned int nr_files, unsigned int nr_bufs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180acf0)
Location: include/trace/events/io_uring.h:69
Inline: False
```
**Symbols:**

```
ffffffff8180acf0-ffffffff8180ad6f: __traceiter_io_uring_register (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool eventfd</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, opcode, nr_files, nr_bufs, eventfd, ret</code> ➡️ <code>__data, ctx, opcode, nr_files, nr_bufs, ret</code>
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
