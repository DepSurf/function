# Function: <code>io_fill_cqe_aux</code>

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
bool io_fill_cqe_aux(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cbf20)
Location: io_uring/io_uring.c:2297
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
```
**Symbols:**

```
ffffffff816cbf20-ffffffff816cc093: io_fill_cqe_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_fill_cqe_aux(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178d6e0)
Location: io_uring/io_uring.c:820
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_flush_post_cqes
```
**Symbols:**

```
ffffffff8178d6e0-ffffffff8178d824: io_fill_cqe_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_fill_cqe_aux(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cef50)
Location: io_uring/io_uring.c:870
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_flush_post_cqes
```
**Symbols:**

```
ffffffff817cef50-ffffffff817cf094: io_fill_cqe_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_fill_cqe_aux(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818120f0)
Location: io_uring/io_uring.c:870
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_flush_post_cqes
```
**Symbols:**

```
ffffffff818120f0-ffffffff81812218: io_fill_cqe_aux (STB_LOCAL)
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
