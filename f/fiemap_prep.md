# Function: <code>fiemap_prep</code>

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
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132b200)
Location: fs/ioctl.c:164
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff8132b200-ffffffff8132b285: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff813367c0)
Location: fs/ioctl.c:164
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff813367c0-ffffffff81336845: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133cb00)
Location: fs/ioctl.c:167
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff8133cb00-ffffffff8133cb7c: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138a800)
Location: fs/ioctl.c:167
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff8138a800-ffffffff8138a87c: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140b990)
Location: fs/ioctl.c:167
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff8140b990-ffffffff8140ba81: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496360)
Location: fs/ioctl.c:167
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff81496360-ffffffff81496451: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb260)
Location: fs/ioctl.c:167
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff814cb260-ffffffff814cb351: fiemap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fiemap_prep(struct inode *inode, struct fiemap_extent_info *fieinfo, u64 start, u64 *len, u32 supported_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fdb10)
Location: fs/ioctl.c:168
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff814fdb10-ffffffff814fdc01: fiemap_prep (STB_GLOBAL)
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
