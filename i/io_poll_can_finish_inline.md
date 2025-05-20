# Function: <code>io_poll_can_finish_inline</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool io_poll_can_finish_inline(struct io_kiocb *req, struct io_poll_table *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:543
Inline: False
Direct callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
```
**Symbols:**

```
ffffffff8179d2d0-ffffffff8179d338: io_poll_can_finish_inline (STB_LOCAL)
ffffffff8207790b-ffffffff82077926: io_poll_can_finish_inline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool io_poll_can_finish_inline(struct io_kiocb *req, struct io_poll_table *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:545
Inline: False
Direct callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
```
**Symbols:**

```
ffffffff817de500-ffffffff817de568: io_poll_can_finish_inline (STB_LOCAL)
ffffffff820f7983-ffffffff820f799e: io_poll_can_finish_inline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool io_poll_can_finish_inline(struct io_kiocb *req, struct io_poll_table *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:566
Inline: False
Direct callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
```
**Symbols:**

```
ffffffff818228d0-ffffffff81822938: io_poll_can_finish_inline (STB_LOCAL)
ffffffff821d5376-ffffffff821d5391: io_poll_can_finish_inline.cold (STB_LOCAL)
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
