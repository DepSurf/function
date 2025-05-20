# Function: <code>aio_read</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t aio_read(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81298d20)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff81298d20-ffffffff81298e31: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t aio_read(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a6e20)
Location: fs/aio.c:1485
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff812a6e20-ffffffff812a6f64: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t aio_read(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812ca420)
Location: fs/aio.c:1499
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff812ca420-ffffffff812ca56d: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t aio_read(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f4470)
Location: fs/aio.c:1486
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff812f4470-ffffffff812f45ef: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307230)
Location: fs/aio.c:1517
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81307230-ffffffff81307390: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328800)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff81328800-ffffffff81328956: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b5b0)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff8133b5b0-ffffffff8133b706: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813754a0)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff813754a0-ffffffff81375600: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383340)
Location: fs/aio.c:1518
Inline: False
```
**Symbols:**

```
ffffffff81383340-ffffffff813834d7: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a3d0)
Location: fs/aio.c:1515
Inline: False
```
**Symbols:**

```
ffffffff8138a3d0-ffffffff8138a57c: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d76e0)
Location: fs/aio.c:1516
Inline: False
```
**Symbols:**

```
ffffffff813d76e0-ffffffff813d788c: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81461360)
Location: fs/aio.c:1541
Inline: False
```
**Symbols:**

```
ffffffff81461360-ffffffff81461577: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f1310)
Location: fs/aio.c:1542
Inline: False
```
**Symbols:**

```
ffffffff814f1310-ffffffff814f1527: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff815288a0)
Location: fs/aio.c:1534
Inline: False
```
**Symbols:**

```
ffffffff815288a0-ffffffff81528ac6: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155d9b0)
Location: fs/aio.c:1586
Inline: False
```
**Symbols:**

```
ffffffff8155d9b0-ffffffff8155dbcf: aio_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa348)
Location: fs/aio.c:1520
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffff8000103fa348-ffff8000103fa4a0: aio_read (STB_LOCAL)
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
In fs/aio.c (c05cef10)
Location: fs/aio.c:1520
Inline: True
```
**Symbols:**

```
c05cef10-c05cf080: aio_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000503a00)
Location: fs/aio.c:1520
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
c000000000503a00-c000000000503bc8: aio_read (STB_LOCAL)
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
In fs/aio.c (ffffffe0002a9e06)
Location: fs/aio.c:1520
Inline: True
```
**Symbols:**

```
ffffffe0002a9e06-ffffffe0002a9f16: aio_read.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333b90)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff81333b90-ffffffff81333ce6: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324800)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff81324800-ffffffff81324956: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331660)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff81331660-ffffffff813317b6: aio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aio_read(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81344250)
Location: fs/aio.c:1520
Inline: False
```
**Symbols:**

```
ffffffff81344250-ffffffff813443a6: aio_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iocb *iocb</code> ➡️ <code>const struct iocb *iocb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
