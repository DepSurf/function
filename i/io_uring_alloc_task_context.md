# Function: <code>io_uring_alloc_task_context</code>

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
int io_uring_alloc_task_context(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a800)
Location: fs/io_uring.c:8139
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_add_task_file
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff8138a800-ffffffff8138a8e2: io_uring_alloc_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct *task, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813923a0)
Location: fs/io_uring.c:7924
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_add_task_file
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff813923a0-ffffffff813925bd: io_uring_alloc_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct *task, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e03d0)
Location: fs/io_uring.c:8638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_add_tctx_node
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff813e03d0-ffffffff813e05d9: io_uring_alloc_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct *task, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8eaf5)
Location: io_uring/io_uring.c:9913
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_add_tctx_node
  - io_uring/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff81e8eaf5-ffffffff81e8ecfe: io_uring_alloc_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct *task, struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff8179ba40)
Location: io_uring/tctx.c:60
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff8179ba40-ffffffff8179bc60: io_uring_alloc_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct *task, struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff817dcb70)
Location: io_uring/tctx.c:60
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff817dcb70-ffffffff817dcd90: io_uring_alloc_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct *task, struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff81820e20)
Location: io_uring/tctx.c:60
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff81820e20-ffffffff818210a9: io_uring_alloc_task_context (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
</ul>
</details>
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
