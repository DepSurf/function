# Function: <code>io_req_set_rsrc_node</code>

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
In fs/io_uring.c (ffffffff813932a1)
Location: fs/io_uring.c:1088
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_prep_rw
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
In fs/io_uring.c (ffffffff813e1557)
Location: fs/io_uring.c:1183
Inline: True
Inline callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
  - fs/io_uring.c:io_prep_rw
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
In io_uring/io_uring.c (ffffffff816d713c)
Location: io_uring/io_uring.c:1416
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_prep_rw
  - io_uring/io_uring.c:io_prep_rw
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
In io_uring/io_uring.c (ffffffff81791414)
Location: io_uring/rsrc.h:142
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/uring_cmd.c (ffffffff81794f19)
Location: io_uring/rsrc.h:142
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff8179770d)
Location: io_uring/rsrc.h:142
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/rw.c (ffffffff817a4033)
Location: io_uring/rsrc.h:142
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In io_uring/io_uring.c (ffffffff817d2676)
Location: io_uring/rsrc.h:128
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/uring_cmd.c (ffffffff817d5c1c)
Location: io_uring/rsrc.h:128
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff817d846d)
Location: io_uring/rsrc.h:128
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/rw.c (ffffffff817e5093)
Location: io_uring/rsrc.h:128
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In io_uring/uring_cmd.c (ffffffff81819e8c)
Location: io_uring/rsrc.h:113
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff8181c77d)
Location: io_uring/rsrc.h:113
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/rw.c (ffffffff81829681)
Location: io_uring/rsrc.h:113
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw_fixed
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
