# Function: <code>io_poll_complete</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8132e4e0)
Location: fs/io_uring.c:1588
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
```
**Symbols:**

```
ffffffff8132e4e0-ffffffff8132e559: io_poll_complete.isra.0 (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81342dc2)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81382ba7)
Location: fs/io_uring.c:4258
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_add
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
In fs/io_uring.c (ffffffff81398b1e)
Location: fs/io_uring.c:5233
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_poll_task_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_poll_complete(struct io_kiocb *req, __poll_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393c50)
Location: fs/io_uring.c:4932
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81393c50-ffffffff81393ce0: io_poll_complete (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813e932a)
Location: fs/io_uring.c:5412
Inline: True
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/io_uring.c (ffff800010404908)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_poll_complete(struct io_ring_ctx *ctx, struct io_kiocb *req, __poll_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d3760)
Location: fs/io_uring.c:1769
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
```
**Symbols:**

```
c05d3760-c05d37a8: io_poll_complete (STB_LOCAL)
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
In fs/io_uring.c (c00000000050d1a8)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
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
In fs/io_uring.c (ffffffe0002af152)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
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
In fs/io_uring.c (ffffffff8133b3a2)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
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
In fs/io_uring.c (ffffffff8132c080)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
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
In fs/io_uring.c (ffffffff81338e72)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
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
In fs/io_uring.c (ffffffff8134b70e)
Location: fs/io_uring.c:1769
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
