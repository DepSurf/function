# Function: <code>io_iter_do_read</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int io_iter_do_read(struct io_kiocb *req, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a330)
Location: fs/io_uring.c:3484
Inline: True
Direct callers:
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff8138a330-ffffffff8138a36d: io_iter_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int io_iter_do_read(struct io_kiocb *req, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390ed0)
Location: fs/io_uring.c:3263
Inline: True
Direct callers:
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81390ed0-ffffffff81390f0d: io_iter_do_read (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813ebab1)
Location: fs/io_uring.c:3488
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
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
In io_uring/io_uring.c (ffffffff816d7817)
Location: io_uring/io_uring.c:4036
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
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
In io_uring/rw.c (ffffffff817a4369)
Location: io_uring/rw.c:638
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
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
In io_uring/rw.c (ffffffff817e5369)
Location: io_uring/rw.c:640
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
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
In io_uring/rw.c (ffffffff818289a6)
Location: io_uring/rw.c:698
Inline: True
Inline callers:
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
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
</ul>
