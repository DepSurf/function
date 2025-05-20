# Function: <code>__io_import_iovec</code>

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
struct iovec *__io_import_iovec(int rw, struct io_kiocb *req, struct io_rw_state *s, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cce70)
Location: io_uring/io_uring.c:3745
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
```
**Symbols:**

```
ffffffff816cce70-ffffffff816cd1cb: __io_import_iovec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iovec *__io_import_iovec(int ddir, struct io_kiocb *req, struct io_rw_state *s, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a30f0)
Location: io_uring/rw.c:362
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_writev_prep_async
  - io_uring/rw.c:io_readv_prep_async
```
**Symbols:**

```
ffffffff817a30f0-ffffffff817a3254: __io_import_iovec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iovec *__io_import_iovec(int ddir, struct io_kiocb *req, struct io_rw_state *s, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e40a0)
Location: io_uring/rw.c:362
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_writev_prep_async
  - io_uring/rw.c:io_readv_prep_async
```
**Symbols:**

```
ffffffff817e40a0-ffffffff817e41f8: __io_import_iovec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iovec *__io_import_iovec(int ddir, struct io_kiocb *req, struct io_rw_state *s, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff81828150)
Location: io_uring/rw.c:414
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:io_writev_prep_async
  - io_uring/rw.c:io_readv_prep_async
```
**Symbols:**

```
ffffffff81828150-ffffffff818282b5: __io_import_iovec (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ddir</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
