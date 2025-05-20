# Function: <code>io_cqring_event_overflow</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx *ctx, u64 user_data, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391d40)
Location: fs/io_uring.c:1548
Inline: False
Direct callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
```
**Symbols:**

```
ffffffff81391d40-ffffffff81391e01: io_cqring_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx *ctx, u64 user_data, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de660)
Location: fs/io_uring.c:1775
Inline: False
Direct callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
```
**Symbols:**

```
ffffffff813de660-ffffffff813de71b: io_cqring_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cb800)
Location: io_uring/io_uring.c:2205
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
```
**Symbols:**

```
ffffffff816cb800-ffffffff816cb979: io_cqring_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a9d0)
Location: io_uring/io_uring.c:727
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_flush_post_cqes
  - io_uring/io_uring.c:__io_flush_post_cqes
```
**Symbols:**

```
ffffffff8178a9d0-ffffffff8178ab49: io_cqring_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cb470)
Location: io_uring/io_uring.c:777
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_flush_post_cqes
  - io_uring/io_uring.c:__io_flush_post_cqes
```
**Symbols:**

```
ffffffff817cb470-ffffffff817cb5e8: io_cqring_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx *ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180f960)
Location: io_uring/io_uring.c:785
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_post_aux_cqe
  - io_uring/io_uring.c:__io_flush_post_cqes
  - io_uring/io_uring.c:__io_flush_post_cqes
  - io_uring/io_uring.c:io_req_cqe_overflow
```
**Symbols:**

```
ffffffff8180f960-ffffffff8180facf: io_cqring_event_overflow (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 extra1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 extra2</code>
</li>
<li>
<b>Param type changed. </b>
<code>long int res</code> ➡️ <code>s32 res</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int cflags</code> ➡️ <code>u32 cflags</code>
</li>
</ul>
</details>
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
