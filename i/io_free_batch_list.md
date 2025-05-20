# Function: <code>io_free_batch_list</code>

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
void io_free_batch_list(struct io_ring_ctx *ctx, struct io_wq_work_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d57a0)
Location: io_uring/io_uring.c:2878
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
```
**Symbols:**

```
ffffffff816d57a0-ffffffff816d5aa2: io_free_batch_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_free_batch_list(struct io_ring_ctx *ctx, struct io_wq_work_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178eb80)
Location: io_uring/io_uring.c:1401
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff8178eb80-ffffffff8178edcd: io_free_batch_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_free_batch_list(struct io_ring_ctx *ctx, struct io_wq_work_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cff90)
Location: io_uring/io_uring.c:1509
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff817cff90-ffffffff817d00ec: io_free_batch_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_free_batch_list(struct io_ring_ctx *ctx, struct io_wq_work_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813120)
Location: io_uring/io_uring.c:1530
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
```
**Symbols:**

```
ffffffff81813120-ffffffff8181327c: io_free_batch_list (STB_LOCAL)
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
