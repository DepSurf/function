# Function: <code>io_req_cqe_overflow</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool io_req_cqe_overflow(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178ee54)
Location: io_uring/io_uring.c:767
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
Direct callers:
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff8178d3c0-ffffffff8178d422: io_req_cqe_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool io_req_cqe_overflow(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d0174)
Location: io_uring/io_uring.c:817
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
Direct callers:
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff817ce7a0-ffffffff817ce802: io_req_cqe_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_req_cqe_overflow(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81811a50)
Location: io_uring/io_uring.c:825
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff81811a50-ffffffff81811aae: io_req_cqe_overflow (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
