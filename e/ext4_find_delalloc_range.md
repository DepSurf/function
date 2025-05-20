# Function: <code>ext4_find_delalloc_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode *inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c7880)
Location: fs/ext4/extents.c:3832
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_find_delalloc_cluster
```
**Symbols:**

```
ffffffff812c7880-ffffffff812c78f4: ext4_find_delalloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode *inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f70a0)
Location: fs/ext4/extents.c:3846
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_find_delalloc_cluster
```
**Symbols:**

```
ffffffff812f70a0-ffffffff812f7114: ext4_find_delalloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode *inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d0b0)
Location: fs/ext4/extents.c:3838
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_find_delalloc_cluster
```
**Symbols:**

```
ffffffff8130d0b0-ffffffff8130d124: ext4_find_delalloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode *inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812eb840)
Location: fs/ext4/extents.c:3833
Inline: False
Direct callers:
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_find_delalloc_cluster
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff812eb840-ffffffff812eb8b5: ext4_find_delalloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode *inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813102f0)
Location: fs/ext4/extents.c:3833
Inline: False
Direct callers:
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_find_delalloc_cluster
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813102f0-ffffffff81310365: ext4_find_delalloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode *inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133e180)
Location: fs/ext4/extents.c:3827
Inline: False
Direct callers:
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_find_delalloc_cluster
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8133e180-ffffffff8133e1f5: ext4_find_delalloc_range (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
