# Function: <code>io_buffer_validate</code>

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
In fs/io_uring.c (ffffffff81398230)
Location: fs/io_uring.c:8403
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
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
In fs/io_uring.c (ffffffff813e3d7a)
Location: fs/io_uring.c:9117
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cd7b3)
Location: io_uring/io_uring.c:10441
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_sqe_buffers_update
Direct callers:
  - io_uring/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff816ca900-ffffffff816ca963: io_buffer_validate.isra.0 (STB_LOCAL)
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
In io_uring/rsrc.c (ffffffff817a2b8c)
Location: io_uring/rsrc.c:115
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3ba9)
Location: io_uring/rsrc.c:106
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81827c59)
Location: io_uring/rsrc.c:111
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
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
