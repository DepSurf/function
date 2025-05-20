# Function: <code>shmem_getpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a9d26)
Location: mm/shmem.c:131
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_follow_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c3104)
Location: mm/shmem.c:124
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811c3900-ffffffff811c392e: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d3190)
Location: mm/shmem.c:120
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811d3970-ffffffff811d3997: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811da811)
Location: mm/shmem.c:131
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811dc100-ffffffff811dc11f: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f05a1)
Location: mm/shmem.c:132
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811f1fd0-ffffffff811f1ff2: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81211d1d)
Location: mm/shmem.c:132
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81213470-ffffffff81213492: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81223bba)
Location: mm/shmem.c:134
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff812263b0-ffffffff812263cf: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812353ea)
Location: mm/shmem.c:139
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81236280-ffffffff8123629f: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124362a)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff812444c0-ffffffff812444df: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126f7ea)
Location: mm/shmem.c:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81272140-ffffffff8127215f: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127ab5a)
Location: mm/shmem.c:152
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8127c5f0-ffffffff8127c60f: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127fccc)
Location: mm/shmem.c:152
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff812817c0-ffffffff812817df: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bdfdc)
Location: mm/shmem.c:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/userfaultfd.c:mcopy_continue
```
**Symbols:**

```
ffffffff812bd8c0-ffffffff812bd8df: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131a883)
Location: mm/shmem.c:146
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/userfaultfd.c:mcopy_continue
```
**Symbols:**

```
ffffffff8131bf50-ffffffff8131bf81: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d58e0)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff8000102d68c8-ffff8000102d6928: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fda8c)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c04fe894-c04fe8d4: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003957c4)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
c000000000396940-c000000000396968: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f1368)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffe0001f1dee-ffffffe0001f1e3a: shmem_getpage (STB_GLOBAL)
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
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123bc7a)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8123cb10-ffffffff8123cb2f: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122ec7a)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8122fb10-ffffffff8122fb2f: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81239a1a)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8123a8b0-ffffffff8123a8cf: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int shmem_getpage(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124910a)
Location: mm/shmem.c:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81249fb0-ffffffff81249fcf: shmem_getpage (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
