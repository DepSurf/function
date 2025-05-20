# Function: <code>aio_write</code>

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
ssize_t aio_write(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81298bd0)
Location: fs/aio.c:1503
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff81298bd0-ffffffff81298d19: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t aio_write(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a6cb0)
Location: fs/aio.c:1508
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff812a6cb0-ffffffff812a6e17: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t aio_write(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812ca2b0)
Location: fs/aio.c:1522
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff812ca2b0-ffffffff812ca41d: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t aio_write(struct kiocb *req, struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f42a0)
Location: fs/aio.c:1519
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff812f42a0-ffffffff812f4463: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307390)
Location: fs/aio.c:1545
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81307390-ffffffff8130752c: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328960)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff81328960-ffffffff81328af9: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b710)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff8133b710-ffffffff8133b8a9: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375230)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff81375230-ffffffff813753d3: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383080)
Location: fs/aio.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81383080-ffffffff8138327b: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a0f0)
Location: fs/aio.c:1543
Inline: False
```
**Symbols:**

```
ffffffff8138a0f0-ffffffff8138a303: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7400)
Location: fs/aio.c:1544
Inline: False
```
**Symbols:**

```
ffffffff813d7400-ffffffff813d7613: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81461000)
Location: fs/aio.c:1568
Inline: False
```
**Symbols:**

```
ffffffff81461000-ffffffff8146128e: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f0f90)
Location: fs/aio.c:1569
Inline: False
```
**Symbols:**

```
ffffffff814f0f90-ffffffff814f121e: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff815282f0)
Location: fs/aio.c:1561
Inline: False
```
**Symbols:**

```
ffffffff815282f0-ffffffff81528594: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155d370)
Location: fs/aio.c:1613
Inline: False
```
**Symbols:**

```
ffffffff8155d370-ffffffff8155d617: aio_write (STB_LOCAL)
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
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa4a0)
Location: fs/aio.c:1548
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffff8000103fa4a0-ffff8000103fa630: aio_write (STB_LOCAL)
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
In fs/aio.c (c05ceb10)
Location: fs/aio.c:1548
Inline: True
```
**Symbols:**

```
c05ceb10-c05cecbc: aio_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000503bd0)
Location: fs/aio.c:1548
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
c000000000503bd0-c000000000503de4: aio_write (STB_LOCAL)
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
In fs/aio.c (ffffffe0002a9c2e)
Location: fs/aio.c:1548
Inline: True
```
**Symbols:**

```
ffffffe0002a9c2e-ffffffe0002a9d70: aio_write.isra.0 (STB_LOCAL)
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
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333cf0)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff81333cf0-ffffffff81333e89: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324960)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff81324960-ffffffff81324af9: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813317c0)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff813317c0-ffffffff81331959: aio_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aio_write(struct kiocb *req, const struct iocb *iocb, bool vectored, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813443b0)
Location: fs/aio.c:1548
Inline: False
```
**Symbols:**

```
ffffffff813443b0-ffffffff81344549: aio_write (STB_LOCAL)
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
