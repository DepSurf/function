# Function: <code>io_poll_add</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132f370)
Location: fs/io_uring.c:1679
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81342a0d)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_poll_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81382a30)
Location: fs/io_uring.c:4746
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81382a30-ffffffff81382be7: io_poll_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398a2c)
Location: fs/io_uring.c:5672
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81397bc0)
Location: fs/io_uring.c:5433
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81397bc0-ffffffff81397cb3: io_poll_add.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813e9290)
Location: fs/io_uring.c:5893
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813e9290-ffffffff813e93d0: io_poll_add.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_poll_add(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d13e0)
Location: io_uring/io_uring.c:7205
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_poll_remove
```
**Symbols:**

```
ffffffff816d13e0-ffffffff816d14bd: io_poll_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_poll_add(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179de70)
Location: io_uring/poll.c:946
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove
```
**Symbols:**

```
ffffffff8179de70-ffffffff8179df31: io_poll_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_poll_add(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817df070)
Location: io_uring/poll.c:949
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove
```
**Symbols:**

```
ffffffff817df070-ffffffff817df130: io_poll_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_poll_add(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81823450)
Location: io_uring/poll.c:967
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove
```
**Symbols:**

```
ffffffff81823450-ffffffff81823510: io_poll_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010404528)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d3e08)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050cad0)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002aebe8)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133afed)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132bcd7)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338abd)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134b31f)
Location: fs/io_uring.c:1865
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
