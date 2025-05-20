# Function: <code>__io_register_rsrc_update</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139e9a3)
Location: fs/io_uring.c:9923
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
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
In fs/io_uring.c (ffffffff813ee942)
Location: fs/io_uring.c:10596
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
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
In io_uring/io_uring.c (ffffffff816d8b56)
Location: io_uring/io_uring.c:12288
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_rsrc_update
  - io_uring/io_uring.c:io_register_rsrc_update
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_files_update
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
In io_uring/rsrc.c (ffffffff817a1b1e)
Location: io_uring/rsrc.c:588
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_files_update
  - io_uring/rsrc.c:io_register_files_update
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
In io_uring/rsrc.c (ffffffff817e2cab)
Location: io_uring/rsrc.c:478
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_files_update
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
In io_uring/rsrc.c (ffffffff81826c0b)
Location: io_uring/rsrc.c:473
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_files_update
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
