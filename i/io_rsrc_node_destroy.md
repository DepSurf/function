# Function: <code>io_rsrc_node_destroy</code>

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
In fs/io_uring.c (ffffffff8139ad34)
Location: fs/io_uring.c:7111
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_rsrc_put_work
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
In fs/io_uring.c (ffffffff813e5334)
Location: fs/io_uring.c:7714
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_rsrc_put_work
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
In io_uring/io_uring.c (ffffffff81e91263)
Location: io_uring/io_uring.c:9023
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_rsrc_put_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_rsrc_node_destroy(struct io_rsrc_node *ref_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a0d4b)
Location: io_uring/rsrc.c:221
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_put_work
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817a0e20-ffffffff817a0e46: io_rsrc_node_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_rsrc_node_destroy(struct io_ring_ctx *ctx, struct io_rsrc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e1f32)
Location: io_uring/rsrc.c:165
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817e1e20-ffffffff817e1e74: io_rsrc_node_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_rsrc_node_destroy(struct io_ring_ctx *ctx, struct io_rsrc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff818262ee)
Location: io_uring/rsrc.c:170
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff818261c0-ffffffff81826214: io_rsrc_node_destroy (STB_GLOBAL)
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
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct io_rsrc_node *node</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_rsrc_node *ref_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
