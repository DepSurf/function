# Function: <code>io_aux_cqe</code>

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
bool io_aux_cqe(struct io_ring_ctx *ctx, bool defer, u64 user_data, s32 res, u32 cflags, bool allow_overflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178e270)
Location: io_uring/io_uring.c:893
Inline: False
Direct callers:
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/poll.c:io_poll_check_events
```
**Symbols:**

```
ffffffff8178e270-ffffffff8178e439: io_aux_cqe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_aux_cqe(const struct io_kiocb *req, bool defer, s32 res, u32 cflags, bool allow_overflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cf2c0)
Location: io_uring/io_uring.c:943
Inline: False
Direct callers:
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/timeout.c:io_timeout_complete
  - io_uring/poll.c:io_poll_check_events
```
**Symbols:**

```
ffffffff817cf2c0-ffffffff817cf4a9: io_aux_cqe (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<code>const struct io_kiocb *req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 user_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, defer, user_data, res, cflags, allow_overflow</code> ➡️ <code>req, defer, res, cflags, allow_overflow</code>
</li>
</ul>
</details>
</li>
</ul>
