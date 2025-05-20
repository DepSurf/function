# Function: <code>io_queue_iowq</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_queue_iowq(struct io_kiocb *req, bool *dont_use);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d2b50)
Location: io_uring/io_uring.c:1859
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_sqe_fallback
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
```
**Symbols:**

```
ffffffff816d2b50-ffffffff816d2c8e: io_queue_iowq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_queue_iowq(struct io_kiocb *req, bool *dont_use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817902c0)
Location: io_uring/io_uring.c:453
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_sqe_fallback
  - io_uring/io_uring.c:io_queue_async
```
**Symbols:**

```
ffffffff817902c0-ffffffff817903ce: io_queue_iowq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_queue_iowq(struct io_kiocb *req, struct io_tw_state *ts_dont_use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce370)
Location: io_uring/io_uring.c:491
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_sqe_fallback
  - io_uring/io_uring.c:io_queue_async
```
**Symbols:**

```
ffffffff817ce370-ffffffff817ce47e: io_queue_iowq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_queue_iowq(struct io_kiocb *req, struct io_tw_state *ts_dont_use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81811620)
Location: io_uring/io_uring.c:505
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_sqe_fallback
  - io_uring/io_uring.c:io_queue_async
```
**Symbols:**

```
ffffffff81811620-ffffffff8181172e: io_queue_iowq (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_tw_state *ts_dont_use</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *dont_use</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
