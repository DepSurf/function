# Function: <code>io_init_bl_list</code>

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
int io_init_bl_list(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e6ac)
Location: io_uring/io_uring.c:5498
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_provide_buffers
```
**Symbols:**

```
ffffffff81e8e6ac-ffffffff81e8e720: io_init_bl_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int io_init_bl_list(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179ef10)
Location: io_uring/kbuf.c:191
Inline: True
Direct callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
```
**Symbols:**

```
ffffffff8179ef10-ffffffff8179ef9a: io_init_bl_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int io_init_bl_list(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e0180)
Location: io_uring/kbuf.c:192
Inline: True
Direct callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
```
**Symbols:**

```
ffffffff817e0180-ffffffff817e020a: io_init_bl_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_init_bl_list(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff818245c0)
Location: io_uring/kbuf.c:220
Inline: False
Direct callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
```
**Symbols:**

```
ffffffff818245c0-ffffffff81824655: io_init_bl_list (STB_LOCAL)
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
