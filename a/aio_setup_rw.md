# Function: <code>aio_setup_rw</code>

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
int aio_setup_rw(int rw, struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297e30)
Location: fs/aio.c:1440
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81297e30-ffffffff81297e7e: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a5cb0)
Location: fs/aio.c:1445
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812a5cb0-ffffffff812a5cfe: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c91e0)
Location: fs/aio.c:1459
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812c91e0-ffffffff812c922e: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f2160)
Location: fs/aio.c:1447
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812f2160-ffffffff812f21ae: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81306b30)
Location: fs/aio.c:1478
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81306b30-ffffffff81306b7e: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813280d0)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff813280d0-ffffffff81328123: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133ae70)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff8133ae70-ffffffff8133aec3: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff813751d0)
Location: fs/aio.c:1480
Inline: True
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff813751d0-ffffffff81375224: aio_setup_rw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813830f9)
Location: fs/aio.c:1482
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a178)
Location: fs/aio.c:1479
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7488)
Location: fs/aio.c:1480
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814610ca)
Location: fs/aio.c:1505
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f105a)
Location: fs/aio.c:1506
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff815283bd)
Location: fs/aio.c:1498
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155d43d)
Location: fs/aio.c:1550
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
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
In fs/aio.c (ffff8000103fa278)
Location: fs/aio.c:1480
Inline: True
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffff8000103fa278-ffff8000103fa344: aio_setup_rw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05ceb7c)
Location: fs/aio.c:1480
Inline: True
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
In fs/aio.c (c000000000503940)
Location: fs/aio.c:1480
Inline: True
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
c000000000503940-c0000000005039fc: aio_setup_rw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9c80)
Location: fs/aio.c:1480
Inline: True
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
ssize_t aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333450)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81333450-ffffffff813334a3: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813240c0)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff813240c0-ffffffff81324113: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81330f20)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81330f20-ffffffff81330f73: aio_setup_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb *iocb, struct iovec **iovec, bool vectored, bool compat, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81343a90)
Location: fs/aio.c:1480
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81343a90-ffffffff81343ae3: aio_setup_rw (STB_LOCAL)
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
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
