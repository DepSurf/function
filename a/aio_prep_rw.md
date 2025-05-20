# Function: <code>aio_prep_rw</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f2650)
Location: fs/aio.c:1412
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812f2650-ffffffff812f27dd: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307050)
Location: fs/aio.c:1443
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81307050-ffffffff81307223: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328620)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81328620-ffffffff813287f4: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b3d0)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff8133b3d0-ffffffff8133b5a4: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81374fb0)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81374fb0-ffffffff81375162: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81382e80)
Location: fs/aio.c:1447
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81382e80-ffffffff8138301d: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81389ef0)
Location: fs/aio.c:1444
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81389ef0-ffffffff8138a08a: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d71d0)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff813d71d0-ffffffff813d736a: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81460de0)
Location: fs/aio.c:1471
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81460de0-ffffffff81460f54: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f0db0)
Location: fs/aio.c:1472
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff814f0db0-ffffffff814f0ebf: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81527bc0)
Location: fs/aio.c:1464
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81527bc0-ffffffff81527ccf: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155c950)
Location: fs/aio.c:1516
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff8155c950-ffffffff8155cae2: aio_prep_rw (STB_LOCAL)
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
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa090)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffff8000103fa090-ffff8000103fa254: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05ce258)
Location: fs/aio.c:1445
Inline: False
```
**Symbols:**

```
c05ce258-c05ce410: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c0000000005036e0)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
c0000000005036e0-c000000000503940: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9a46)
Location: fs/aio.c:1445
Inline: False
```
**Symbols:**

```
ffffffe0002a9a46-ffffffe0002a9bc8: aio_prep_rw (STB_LOCAL)
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
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813339b0)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff813339b0-ffffffff81333b84: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324620)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81324620-ffffffff813247f4: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331480)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81331480-ffffffff81331654: aio_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aio_prep_rw(struct kiocb *req, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81344070)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81344070-ffffffff81344244: aio_prep_rw (STB_LOCAL)
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
