# Function: <code>io_post_aux_cqe</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_post_aux_cqe(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178e230)
Location: io_uring/io_uring.c:888
Inline: False
Direct callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
  - io_uring/rsrc.c:io_rsrc_put_work
  - io_uring/rsrc.c:io_rsrc_put_work
```
**Symbols:**

```
ffffffff8178e230-ffffffff8178e255: io_post_aux_cqe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_post_aux_cqe(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cf280)
Location: io_uring/io_uring.c:938
Inline: False
Direct callers:
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_tw_complete
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
**Symbols:**

```
ffffffff817cf280-ffffffff817cf2a5: io_post_aux_cqe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_post_aux_cqe(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81812400)
Location: io_uring/io_uring.c:937
Inline: False
Direct callers:
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_tw_complete
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
**Symbols:**

```
ffffffff81812400-ffffffff81812425: io_post_aux_cqe (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
