# Function: <code>_ext4_fiemap</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81394a20)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff81394a20-ffffffff81394c45: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010467740)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffff800010467740-ffff800010467970: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0628364)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
c0628364-c0628660: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000585ba0)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
c000000000585ba0-c000000000585ea0: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f55d0)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffe0002f55d0-ffffffe0002f57a0: _ext4_fiemap (STB_LOCAL)
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
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138d000)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8138d000-ffffffff8138d225: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137da90)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8137da90-ffffffff8137dcb5: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138a960)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8138a960-ffffffff8138ab85: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _ext4_fiemap(struct inode *inode, struct fiemap_extent_info *fieinfo, __u64 start, __u64 len, int (*fill)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139e6a0)
Location: fs/ext4/extents.c:5102
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8139e6a0-ffffffff8139e8c5: _ext4_fiemap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
