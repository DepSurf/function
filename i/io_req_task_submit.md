# Function: <code>io_req_task_submit</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_req_task_submit(struct callback_head *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398f00)
Location: fs/io_uring.c:2229
Inline: False
```
**Symbols:**

```
ffffffff81398f00-ffffffff81398f51: io_req_task_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_req_task_submit(struct callback_head *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a04d0)
Location: fs/io_uring.c:2069
Inline: False
```
**Symbols:**

```
ffffffff813a04d0-ffffffff813a04e7: io_req_task_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_submit(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813edfc1)
Location: fs/io_uring.c:2279
Inline: True
Direct callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff813edf60-ffffffff813edfe4: io_req_task_submit (STB_LOCAL)
ffffffff81cc5cc6-ffffffff81cc5cdb: io_req_task_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_submit(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d2ed3)
Location: io_uring/io_uring.c:2841
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_apoll_task_func
```
**Symbols:**

```
ffffffff816d2e40-ffffffff816d2f74: io_req_task_submit (STB_LOCAL)
ffffffff81e91496-ffffffff81e914ab: io_req_task_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_submit(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790f8a)
Location: io_uring/io_uring.c:1370
Inline: True
Direct callers:
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff820776af-ffffffff820776c4: io_req_task_submit.cold (STB_LOCAL)
ffffffff81790f10-ffffffff81790fc0: io_req_task_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_submit(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d243e)
Location: io_uring/io_uring.c:1476
Inline: True
Direct callers:
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff820f76df-ffffffff820f76f4: io_req_task_submit.cold (STB_LOCAL)
ffffffff817d23a0-ffffffff817d2474: io_req_task_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_submit(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff81815ae8)
Location: io_uring/io_uring.c:1497
Inline: True
Direct callers:
  - io_uring/poll.c:io_poll_task_func
```
**Symbols:**

```
ffffffff821d50aa-ffffffff821d50bf: io_req_task_submit.cold (STB_LOCAL)
ffffffff81815a50-ffffffff81815b14: io_req_task_submit (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_kiocb *req</code>
</li>
<li>
<b>Param added. </b>
<code>bool *locked</code>
</li>
<li>
<b>Param removed. </b>
<code>struct callback_head *cb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
