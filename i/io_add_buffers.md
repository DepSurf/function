# Function: <code>io_add_buffers</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81384184)
Location: fs/io_uring.c:3254
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
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
In fs/io_uring.c (ffffffff8139379a)
Location: fs/io_uring.c:4243
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139bf5b)
Location: fs/io_uring.c:4014
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
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
In fs/io_uring.c (ffffffff813eabba)
Location: fs/io_uring.c:4435
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_add_buffers(struct io_ring_ctx *ctx, struct io_provide_buf *pbuf, struct io_buffer_list *bl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c87c0)
Location: io_uring/io_uring.c:5472
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_provide_buffers
```
**Symbols:**

```
ffffffff816c87c0-ffffffff816c89d0: io_add_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_add_buffers(struct io_ring_ctx *ctx, struct io_provide_buf *pbuf, struct io_buffer_list *bl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179eb90)
Location: io_uring/kbuf.c:395
Inline: False
Direct callers:
  - io_uring/kbuf.c:io_provide_buffers
```
**Symbols:**

```
ffffffff8179eb90-ffffffff8179eda0: io_add_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_add_buffers(struct io_ring_ctx *ctx, struct io_provide_buf *pbuf, struct io_buffer_list *bl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817dfd80)
Location: io_uring/kbuf.c:408
Inline: False
Direct callers:
  - io_uring/kbuf.c:io_provide_buffers
```
**Symbols:**

```
ffffffff817dfd80-ffffffff817dff90: io_add_buffers (STB_LOCAL)
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
In io_uring/kbuf.c (ffffffff81825042)
Location: io_uring/kbuf.c:466
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
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
</ul>
