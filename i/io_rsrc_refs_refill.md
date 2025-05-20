# Function: <code>io_rsrc_refs_refill</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d72b1)
Location: io_uring/io_uring.c:1409
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_rsrc_refs_refill(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a0bf0)
Location: io_uring/rsrc.c:154
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/uring_cmd.c:io_uring_cmd_prep
  - io_uring/net.c:io_send_zc_prep
  - io_uring/rw.c:io_prep_rw
```
**Symbols:**

```
ffffffff817a0bf0-ffffffff817a0c45: io_rsrc_refs_refill (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
