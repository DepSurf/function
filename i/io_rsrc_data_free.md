# Function: <code>io_rsrc_data_free</code>

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
In fs/io_uring.c (ffffffff813986d9)
Location: fs/io_uring.c:7189
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:__io_sqe_buffers_unregister
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dfd00)
Location: fs/io_uring.c:7857
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_unregister
  - fs/io_uring.c:io_rsrc_data_alloc
```
**Symbols:**

```
ffffffff813dfd00-ffffffff813dfd62: io_rsrc_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e659)
Location: io_uring/io_uring.c:9170
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:__io_sqe_buffers_unregister
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - io_uring/io_uring.c:io_rsrc_data_alloc
```
**Symbols:**

```
ffffffff81e8e659-ffffffff81e8e68e: io_rsrc_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a0510)
Location: io_uring/rsrc.c:376
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
**Symbols:**

```
ffffffff817a0510-ffffffff817a057a: io_rsrc_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e1840)
Location: io_uring/rsrc.c:280
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
**Symbols:**

```
ffffffff817e1840-ffffffff817e18aa: io_rsrc_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81825bd0)
Location: io_uring/rsrc.c:285
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
**Symbols:**

```
ffffffff81825bd0-ffffffff81825c3a: io_rsrc_data_free (STB_LOCAL)
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
