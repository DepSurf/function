# Function: <code>loop_rw_iter</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81340fb7)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81340a80-ffffffff81340b8d: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t loop_rw_iter(int rw, struct file *file, struct kiocb *kiocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137bfc0)
Location: fs/io_uring.c:2530
Inline: True
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff8137bfc0-ffffffff8137c10f: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int rw, struct io_kiocb *req, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813897e0)
Location: fs/io_uring.c:3262
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
```
**Symbols:**

```
ffffffff813897e0-ffffffff813898f8: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int rw, struct io_kiocb *req, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390600)
Location: fs/io_uring.c:3060
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
```
**Symbols:**

```
ffffffff81390600-ffffffff81390731: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int rw, struct io_kiocb *req, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ddbe0)
Location: fs/io_uring.c:3282
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff813ddbe0-ffffffff813ddd07: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int rw, struct io_kiocb *req, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8650)
Location: io_uring/io_uring.c:3818
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
```
**Symbols:**

```
ffffffff816c8650-ffffffff816c8787: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int ddir, struct io_rw *rw, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a3270)
Location: io_uring/rw.c:429
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
```
**Symbols:**

```
ffffffff817a3270-ffffffff817a33a7: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int ddir, struct io_rw *rw, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e4210)
Location: io_uring/rw.c:429
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
```
**Symbols:**

```
ffffffff817e4210-ffffffff817e4345: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t loop_rw_iter(int ddir, struct io_rw *rw, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff818282d0)
Location: io_uring/rw.c:480
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
```
**Symbols:**

```
ffffffff818282d0-ffffffff81828415: loop_rw_iter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffff800010400f0c)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffff800010400a38-ffff800010400b9c: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (c05d2dc8)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
c05d2954-c05d2a70: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (c00000000050aa40)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
c00000000050a440-c00000000050a5ec: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffe0002ad42e)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffe0002ad09c-ffffffe0002ad1a4: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81339597)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81339060-ffffffff8133916d: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8132a2c7)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81329d90-ffffffff81329e9d: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81337067)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81336b30-ffffffff81336c3d: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8134a127)
Location: fs/io_uring.c:1334
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81349c00-ffffffff81349cf8: loop_rw_iter.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_kiocb *req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kiocb *kiocb</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, file, kiocb, iter</code> ➡️ <code>rw, req, iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<code>struct io_kiocb *req</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, req, iter</code> ➡️ <code>ddir, rw, iter</code>
</li>
<li>
<b>Param type changed. </b>
<code>int rw</code> ➡️ <code>struct io_rw *rw</code>
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
