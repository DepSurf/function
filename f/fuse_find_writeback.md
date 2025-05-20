# Function: <code>fuse_find_writeback</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct fuse_req *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:338
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffff8140c890-ffffffff8140c913: fuse_find_writeback (STB_LOCAL)
ffffffff81412930-ffffffff81412953: fuse_find_writeback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81426290)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffff81426290-ffffffff814262f5: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81476dc8)
Location: fs/fuse/file.c:367
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff81491bd8)
Location: fs/fuse/file.c:390
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff81496d28)
Location: fs/fuse/file.c:394
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff814ee608)
Location: fs/fuse/file.c:398
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff8157c7c8)
Location: fs/fuse/file.c:404
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff81622228)
Location: fs/fuse/file.c:404
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff8165a678)
Location: fs/fuse/file.c:405
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
In fs/fuse/file.c (ffffffff81694348)
Location: fs/fuse/file.c:406
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_range_is_writeback
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
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff800010509db8)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffff800010509db8-ffff800010509e70: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c5d04)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
c06c5d04-c06c5db8: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c00000000064f950)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
c00000000064f950-c00000000064f9bc: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003754ce)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffe0003754ce-ffffffe000375534: fuse_find_writeback (STB_LOCAL)
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
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141e870)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffff8141e870-ffffffff8141e8d5: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f2f0)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffff8140f2f0-ffffffff8140f355: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141aa10)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffff8141aa10-ffffffff8141aa75: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_find_writeback(struct fuse_inode *fi, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81431830)
Location: fs/fuse/file.c:366
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_range_is_writeback
```
**Symbols:**

```
ffffffff81431830-ffffffff81431895: fuse_find_writeback (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct fuse_req *</code> ➡️ <code>struct fuse_writepage_args *</code>
</li>
</ul>
</details>
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
