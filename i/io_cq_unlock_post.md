# Function: <code>io_cq_unlock_post</code>

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
void io_cq_unlock_post(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178e0f0)
Location: io_uring/io_uring.c:621
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff8178e0f0-ffffffff8178e16e: io_cq_unlock_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_cq_unlock_post(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce660)
Location: io_uring/io_uring.c:656
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff817ce660-ffffffff817ce6de: io_cq_unlock_post (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_cq_unlock_post(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81811900)
Location: io_uring/io_uring.c:664
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff81811900-ffffffff8181198f: io_cq_unlock_post (STB_LOCAL)
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
