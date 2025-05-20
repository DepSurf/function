# Function: <code>__readahead_batch</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int __readahead_batch(struct readahead_control *rac, struct page **array, unsigned int array_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81475d40)
Location: include/linux/pagemap.h:738
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81475d40-ffffffff81475f30: __readahead_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int __readahead_batch(struct readahead_control *rac, struct page **array, unsigned int array_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81491270)
Location: include/linux/pagemap.h:893
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81491270-ffffffff814914bd: __readahead_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int __readahead_batch(struct readahead_control *rac, struct page **array, unsigned int array_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814963c0)
Location: include/linux/pagemap.h:935
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff814963c0-ffffffff81496614: __readahead_batch (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff814eef53)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In fs/fuse/file.c (ffffffff8157ecd8)
Location: include/linux/pagemap.h:1313
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int __readahead_batch(struct readahead_control *rac, struct page **array, unsigned int array_sz);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff815edf50)
Location: include/linux/pagemap.h:1289
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In fs/fuse/file.c (ffffffff81624998)
Location: include/linux/pagemap.h:1289
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff815edf50-ffffffff815ee1cf: __readahead_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int __readahead_batch(struct readahead_control *rac, struct page **array, unsigned int array_sz);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81625f10)
Location: include/linux/pagemap.h:1292
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In fs/fuse/file.c (ffffffff8165cd6f)
Location: include/linux/pagemap.h:1292
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81625f10-ffffffff81626150: __readahead_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int __readahead_batch(struct readahead_control *rac, struct page **array, unsigned int array_sz);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8165f050)
Location: include/linux/pagemap.h:1379
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In fs/fuse/file.c (ffffffff81696acf)
Location: include/linux/pagemap.h:1379
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff8165f050-ffffffff8165f28d: __readahead_batch (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
