# Function: <code>io_iopoll_req_issued</code>

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
In fs/io_uring.c (ffffffff8132f288)
Location: fs/io_uring.c:916
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
In fs/io_uring.c (ffffffff81342902)
Location: fs/io_uring.c:986
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
void io_iopoll_req_issued(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137b110)
Location: fs/io_uring.c:2046
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8137b110-ffffffff8137b1ec: io_iopoll_req_issued (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813982ca)
Location: fs/io_uring.c:2783
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
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
In fs/io_uring.c (ffffffff8139f353)
Location: fs/io_uring.c:2550
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
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
In fs/io_uring.c (ffffffff813ed102)
Location: fs/io_uring.c:2775
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
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
In io_uring/io_uring.c (ffffffff816cda92)
Location: io_uring/io_uring.c:3300
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790ca4)
Location: io_uring/io_uring.c:1615
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d21a5)
Location: io_uring/io_uring.c:1698
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818154c3)
Location: io_uring/io_uring.c:1722
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
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
In fs/io_uring.c (ffff800010404204)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (c05d3cc0)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (c00000000050c944)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (ffffffe0002aeb74)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (ffffffff8133aee2)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (ffffffff8132bbcc)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (ffffffff813389b2)
Location: fs/io_uring.c:986
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
In fs/io_uring.c (ffffffff8134b21c)
Location: fs/io_uring.c:986
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
</ul>
