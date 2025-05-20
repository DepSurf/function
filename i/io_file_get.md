# Function: <code>io_file_get</code>

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
In fs/io_uring.c (ffffffff813300b0)
Location: fs/io_uring.c:962
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffff813437b3)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_file_get(struct io_submit_state *state, struct io_kiocb *req, int fd, struct file **out_file, bool fixed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137e5e0)
Location: fs/io_uring.c:5587
Inline: False
Direct callers:
  - fs/io_uring.c:io_init_req
```
**Symbols:**

```
ffffffff8137e5e0-ffffffff8137e7b6: io_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *io_file_get(struct io_submit_state *state, struct io_kiocb *req, int fd, bool fixed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81394270)
Location: fs/io_uring.c:6462
Inline: False
Direct callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
```
**Symbols:**

```
ffffffff81394270-ffffffff81394513: io_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *io_file_get(struct io_submit_state *state, struct io_kiocb *req, int fd, bool fixed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393240)
Location: fs/io_uring.c:6351
Inline: False
Direct callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
```
**Symbols:**

```
ffffffff81393240-ffffffff81393400: io_file_get (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813e151a)
Location: fs/io_uring.c:6940
Inline: True
Inline callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
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
In fs/io_uring.c (ffff8000104054c4)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (c05d513c)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (c00000000050df6c)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffe0002af5e6)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffff8133bd93)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffff8132ca73)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffff81339863)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffff8134c593)
Location: fs/io_uring.c:1032
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file **out_file</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, req, fd, out_file, fixed</code> ➡️ <code>state, req, fd, fixed</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct file *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
