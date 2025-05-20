# Function: <code>io_iopoll_getevents</code>

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
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e730)
Location: fs/io_uring.c:778
Inline: False
Direct callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff8132e730-ffffffff8132ea1f: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81341c40)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff81341c40-ffffffff81341f27: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81385633)
Location: fs/io_uring.c:1890
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff81384ea0-ffffffff81384f1d: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2542
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
```
</details>
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
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010402748)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffff800010402748-ffff800010402a8c: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d57a4)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
c05d57a4-c05d5b4c: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050bdd0)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
c00000000050bdd0-c00000000050c240: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ae216)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffe0002ae216-ffffffe0002ae494: io_iopoll_getevents (STB_LOCAL)
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
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a220)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff8133a220-ffffffff8133a507: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132af30)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff8132af30-ffffffff8132b217: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81337cf0)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff81337cf0-ffffffff81337fd7: io_iopoll_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134cb90)
Location: fs/io_uring.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff8134cb90-ffffffff8134ceb1: io_iopoll_getevents (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
