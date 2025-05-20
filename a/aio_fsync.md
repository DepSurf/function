# Function: <code>aio_fsync</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f27e0)
Location: fs/aio.c:1575
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff812f27e0-ffffffff812f2893: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307530)
Location: fs/aio.c:1595
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81307530-ffffffff813075b5: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328b00)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffff81328b00-ffffffff81328b88: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b8b0)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffff8133b8b0-ffffffff8133b938: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813753e0)
Location: fs/aio.c:1600
Inline: True
```
**Symbols:**

```
ffffffff813753e0-ffffffff81375492: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383280)
Location: fs/aio.c:1598
Inline: True
```
**Symbols:**

```
ffffffff81383280-ffffffff81383332: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a310)
Location: fs/aio.c:1595
Inline: True
```
**Symbols:**

```
ffffffff8138a310-ffffffff8138a3c2: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7620)
Location: fs/aio.c:1596
Inline: True
```
**Symbols:**

```
ffffffff813d7620-ffffffff813d76d2: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81461290)
Location: fs/aio.c:1620
Inline: True
```
**Symbols:**

```
ffffffff81461290-ffffffff8146135a: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f1230)
Location: fs/aio.c:1621
Inline: True
```
**Symbols:**

```
ffffffff814f1230-ffffffff814f12fa: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff815285b0)
Location: fs/aio.c:1613
Inline: True
```
**Symbols:**

```
ffffffff815285b0-ffffffff81528681: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155d630)
Location: fs/aio.c:1656
Inline: True
```
**Symbols:**

```
ffffffff8155d630-ffffffff8155d701: aio_fsync (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa630)
Location: fs/aio.c:1597
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffff8000103fa630-ffff8000103fa6e4: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cea68)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
c05cea68-c05ceb10: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000503df0)
Location: fs/aio.c:1597
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
c000000000503df0-c000000000503ed4: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9d70)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffe0002a9d70-ffffffe0002a9e06: aio_fsync (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333e90)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffff81333e90-ffffffff81333f18: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324b00)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffff81324b00-ffffffff81324b88: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331960)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffff81331960-ffffffff813319e8: aio_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int aio_fsync(struct fsync_iocb *req, const struct iocb *iocb, bool datasync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813445c0)
Location: fs/aio.c:1597
Inline: True
```
**Symbols:**

```
ffffffff813445c0-ffffffff81344648: aio_fsync (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
