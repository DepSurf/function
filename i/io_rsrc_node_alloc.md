# Function: <code>io_rsrc_node_alloc</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81392039)
Location: fs/io_uring.c:7642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dfe89)
Location: fs/io_uring.c:7750
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d4ced)
Location: io_uring/io_uring.c:9059
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_rsrc_update
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:io_sqe_files_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2990)
Location: io_uring/rsrc.c:264
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_register_rsrc_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_rsrc_node *io_rsrc_node_alloc(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e2050)
Location: io_uring/rsrc.c:192
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
**Symbols:**

```
ffffffff817e2050-ffffffff817e20b5: io_rsrc_node_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_rsrc_node *io_rsrc_node_alloc(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff818263d0)
Location: io_uring/rsrc.c:197
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
**Symbols:**

```
ffffffff818263d0-ffffffff81826464: io_rsrc_node_alloc (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
