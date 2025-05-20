# Function: <code>io_poll_check_events</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_poll_check_events(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:6649
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff816cde00-ffffffff816ce021: io_poll_check_events (STB_LOCAL)
ffffffff81e90b5d-ffffffff81e90b79: io_poll_check_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_poll_check_events(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:239
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff8179cd50-ffffffff8179cf69: io_poll_check_events (STB_LOCAL)
ffffffff820778a8-ffffffff820778c5: io_poll_check_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_poll_check_events(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:241
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff817ddf80-ffffffff817de193: io_poll_check_events (STB_LOCAL)
ffffffff820f7928-ffffffff820f793d: io_poll_check_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_poll_check_events(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:262
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81822320-ffffffff8182253e: io_poll_check_events (STB_LOCAL)
ffffffff821d531b-ffffffff821d5330: io_poll_check_events.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_tw_state *ts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
