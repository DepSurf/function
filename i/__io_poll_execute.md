# Function: <code>__io_poll_execute</code>

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
In io_uring/io_uring.c (ffffffff816ce710)
Location: io_uring/io_uring.c:6757
Inline: True
Direct callers:
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_poll_cancel_req
```
**Symbols:**

```
ffffffff816ce710-ffffffff816ce7c2: __io_poll_execute.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_poll_execute(struct io_kiocb *req, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179ca30)
Location: io_uring/poll.c:365
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
**Symbols:**

```
ffffffff8179ca30-ffffffff8179cab7: __io_poll_execute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_poll_execute(struct io_kiocb *req, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817ddc60)
Location: io_uring/poll.c:367
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
**Symbols:**

```
ffffffff817ddc60-ffffffff817ddce4: __io_poll_execute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_poll_execute(struct io_kiocb *req, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81822000)
Location: io_uring/poll.c:232
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81822000-ffffffff8182208a: __io_poll_execute (STB_LOCAL)
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
