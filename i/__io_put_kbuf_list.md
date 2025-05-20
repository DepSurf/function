# Function: <code>__io_put_kbuf_list</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178b710)
Location: io_uring/kbuf.h:95
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/kbuf.c (ffffffff8179f0ff)
Location: io_uring/kbuf.h:95
Inline: True
Inline callers:
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
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
In io_uring/io_uring.c (ffffffff817ceb10)
Location: io_uring/kbuf.h:102
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/kbuf.c (ffffffff817e036f)
Location: io_uring/kbuf.h:102
Inline: True
Inline callers:
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
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
In io_uring/io_uring.c (ffffffff81811c49)
Location: io_uring/kbuf.h:111
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/kbuf.c (ffffffff818247ef)
Location: io_uring/kbuf.h:111
Inline: True
Inline callers:
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
  - io_uring/kbuf.c:__io_put_kbuf
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
