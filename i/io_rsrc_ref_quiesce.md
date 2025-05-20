# Function: <code>io_rsrc_ref_quiesce</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8139e32c)
Location: fs/io_uring.c:7150
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff81398c40-ffffffff81398cfb: io_rsrc_ref_quiesce.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813ee51a)
Location: fs/io_uring.c:7802
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff813e3fb0-ffffffff813e4107: io_rsrc_ref_quiesce.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data *data, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e90b79)
Location: io_uring/io_uring.c:9114
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff81e90b79-ffffffff81e90ce8: io_rsrc_ref_quiesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data *data, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a109e)
Location: io_uring/rsrc.c:319
Inline: True
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_sqe_files_unregister
```
**Symbols:**

```
ffffffff817a1040-ffffffff817a114e: io_rsrc_ref_quiesce (STB_LOCAL)
ffffffff820779f7-ffffffff82077a0c: io_rsrc_ref_quiesce.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data *data, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:212
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_sqe_files_unregister
```
**Symbols:**

```
ffffffff817e20d0-ffffffff817e22f3: io_rsrc_ref_quiesce (STB_LOCAL)
ffffffff820f7aa5-ffffffff820f7aba: io_rsrc_ref_quiesce.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data *data, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:217
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_sqe_files_unregister
```
**Symbols:**

```
ffffffff81826480-ffffffff818266a3: io_rsrc_ref_quiesce (STB_LOCAL)
ffffffff821d5444-ffffffff821d5459: io_rsrc_ref_quiesce.cold (STB_LOCAL)
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
