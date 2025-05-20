# Function: <code>demangle_poll</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:134
Inline: True
```
```
In fs/fuse/file.c (ffffffff813c901c)
Location: include/linux/poll.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:134
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:134
Inline: True
```
```
In fs/fuse/file.c (ffffffff813e2feb)
Location: include/linux/poll.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff8140eb01)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff81427a47)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff81477967)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (ffffffff813951de)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
```
```
In fs/fuse/file.c (ffffffff81492dee)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (ffffffff8139c90a)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
```
In fs/fuse/file.c (ffffffff81497d5e)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (ffffffff813e6859)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
```
In fs/fuse/file.c (ffffffff814ef96f)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157cdda)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/io_uring.c (ffffffff816c5249)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_add_prep
  - io_uring/io_uring.c:io_poll_remove_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/fuse/file.c (ffffffff8162292a)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/poll.c (ffffffff8179de23)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_prep
  - io_uring/poll.c:io_poll_remove_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165ad6f)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/poll.c (ffffffff817df023)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_prep
  - io_uring/poll.c:io_poll_remove_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:136
Inline: True
```
```
In fs/fuse/file.c (ffffffff81694a3f)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/poll.c (ffffffff81823403)
Location: include/linux/poll.h:136
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_prep
  - io_uring/poll.c:io_poll_remove_prep
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffff80001050c6bc)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (c06c5fb0)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (c0000000006500c0)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffe000376ef0)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff81420027)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff81410aa7)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff8141c1c7)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/poll.h:138
Inline: True
```
```
In fs/fuse/file.c (ffffffff81431d05)
Location: include/linux/poll.h:138
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
</details>
</li>
</ul>

## Differences
