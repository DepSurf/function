# Function: <code>io_poll_cancel</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81382470)
Location: fs/io_uring.c:4658
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_async_find_and_cancel
```
**Symbols:**

```
ffffffff81382470-ffffffff813824dd: io_poll_cancel.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813915d0)
Location: fs/io_uring.c:5587
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_async_find_and_cancel
```
**Symbols:**

```
ffffffff813915d0-ffffffff8139163a: io_poll_cancel.isra.0 (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81397931)
Location: fs/io_uring.c:5337
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
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
In fs/io_uring.c (ffffffff813e5fb5)
Location: fs/io_uring.c:5796
Inline: True
Inline callers:
  - fs/io_uring.c:io_try_cancel_userdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d31cc)
Location: io_uring/io_uring.c:7127
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_try_cancel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_poll_cancel(struct io_ring_ctx *ctx, struct io_cancel_data *cd, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179dc50)
Location: io_uring/poll.c:867
Inline: False
Direct callers:
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff8179dc50-ffffffff8179dcec: io_poll_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_poll_cancel(struct io_ring_ctx *ctx, struct io_cancel_data *cd, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817dee50)
Location: io_uring/poll.c:870
Inline: False
Direct callers:
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff817dee50-ffffffff817deee7: io_poll_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_poll_cancel(struct io_ring_ctx *ctx, struct io_cancel_data *cd, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81823230)
Location: io_uring/poll.c:888
Inline: False
Direct callers:
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff81823230-ffffffff818232c7: io_poll_cancel (STB_GLOBAL)
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
