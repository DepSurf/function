# Function: <code>io_poll_remove_entries</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d1da2)
Location: io_uring/io_uring.c:6608
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
Direct callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff816caaf0-ffffffff816cabdb: io_poll_remove_entries.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (ffffffff8179d245)
Location: io_uring/poll.c:190
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
Direct callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff8179cad0-ffffffff8179cbbb: io_poll_remove_entries.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (ffffffff817de475)
Location: io_uring/poll.c:192
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
Direct callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff817ddd00-ffffffff817dddeb: io_poll_remove_entries.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (ffffffff81822845)
Location: io_uring/poll.c:192
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
Direct callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff818220a0-ffffffff8182218b: io_poll_remove_entries.part.0 (STB_LOCAL)
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
