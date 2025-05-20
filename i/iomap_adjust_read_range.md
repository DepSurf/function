# Function: <code>iomap_adjust_read_range</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323330)
Location: fs/iomap.c:149
Inline: False
Direct callers:
  - fs/iomap.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81323330-ffffffff81323421: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b170)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8134b170-ffffffff8134b264: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363420)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81363420-ffffffff81363514: iomap_adjust_read_range (STB_LOCAL)
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
In fs/iomap/buffered-io.c (ffffffff813aa700)
Location: fs/iomap/buffered-io.c:82
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813aa700-ffffffff813aa7e5: iomap_adjust_read_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bbd50)
Location: fs/iomap/buffered-io.c:88
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813bbd50-ffffffff813bbe35: iomap_adjust_read_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3070)
Location: fs/iomap/buffered-io.c:88
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813c3070-ffffffff813c3155: iomap_adjust_read_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:88
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff814126c0-ffffffff814127e0: iomap_adjust_read_range.isra.0 (STB_LOCAL)
ffffffff81cc7789-ffffffff81cc785f: iomap_adjust_read_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:82
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff8148aba0-ffffffff8148ae39: iomap_adjust_read_range.isra.0 (STB_LOCAL)
ffffffff81e7a289-ffffffff81e7a3eb: iomap_adjust_read_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:90
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff8151e3a0-ffffffff8151e57e: iomap_adjust_read_range.isra.0 (STB_LOCAL)
ffffffff8206b1f4-ffffffff8206b356: iomap_adjust_read_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:90
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff81556500-ffffffff815566e1: iomap_adjust_read_range.isra.0 (STB_LOCAL)
ffffffff820eb142-ffffffff820eb2b0: iomap_adjust_read_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:196
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff8158c9d0-ffffffff8158cba6: iomap_adjust_read_range.isra.0 (STB_LOCAL)
ffffffff821c823d-ffffffff821c83a9: iomap_adjust_read_range.isra.0.cold (STB_LOCAL)
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
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff800010429d40)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffff800010429d40-ffff800010429ee8: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f3394)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
c05f3394-c05f360c: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c000000000539f40)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
c000000000539f40-c00000000053a160: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c77c0)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffe0002c77c0-ffffffe0002c793a: iomap_adjust_read_range (STB_LOCAL)
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
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135ba00)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8135ba00-ffffffff8135baf4: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c6a0)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8134c6a0-ffffffff8134c794: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813594d0)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813594d0-ffffffff813595c4: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iomap_adjust_read_range(struct inode *inode, struct iomap_page *iop, loff_t *pos, loff_t length, unsigned int *offp, unsigned int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136cbd0)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8136cbd0-ffffffff8136ccc4: iomap_adjust_read_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
