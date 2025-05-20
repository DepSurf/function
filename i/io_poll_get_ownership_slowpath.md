# Function: <code>io_poll_get_ownership_slowpath</code>

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
bool io_poll_get_ownership_slowpath(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179c540)
Location: io_uring/poll.c:68
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_can_finish_inline
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
**Symbols:**

```
ffffffff8179c540-ffffffff8179c593: io_poll_get_ownership_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_poll_get_ownership_slowpath(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817dd770)
Location: io_uring/poll.c:71
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_can_finish_inline
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
**Symbols:**

```
ffffffff817dd770-ffffffff817dd7c3: io_poll_get_ownership_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_poll_get_ownership_slowpath(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81821ac0)
Location: io_uring/poll.c:71
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_can_finish_inline
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
**Symbols:**

```
ffffffff81821ac0-ffffffff81821b13: io_poll_get_ownership_slowpath (STB_LOCAL)
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
