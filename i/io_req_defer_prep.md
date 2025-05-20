# Function: <code>io_req_defer_prep</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81388761)
Location: fs/io_uring.c:5083
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_req_defer
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_req_defer
```
**Symbols:**

```
ffffffff81386200-ffffffff8138694e: io_req_defer_prep.part.0 (STB_LOCAL)
ffffffff81389c22-ffffffff81389c43: io_req_defer_prep.part.0.cold (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81399403)
Location: fs/io_uring.c:6119
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
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
