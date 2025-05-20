# Function: <code>io_prep_fsync</code>

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
In fs/io_uring.c (ffffffff8132f55f)
Location: fs/io_uring.c:1380
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
In fs/io_uring.c (ffffffff81342c1e)
Location: fs/io_uring.c:1544
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int io_prep_fsync(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137bce0)
Location: fs/io_uring.c:2980
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8137bce0-ffffffff8137bd3a: io_prep_fsync (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81394f87)
Location: fs/io_uring.c:3956
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
```
</details>
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
In fs/io_uring.c (ffff800010404708)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (c05d3d78)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (c00000000050ca50)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (ffffffe0002aee46)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (ffffffff8133b1fe)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (ffffffff8132bee2)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (ffffffff81338cce)
Location: fs/io_uring.c:1544
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
In fs/io_uring.c (ffffffff8134b500)
Location: fs/io_uring.c:1544
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
