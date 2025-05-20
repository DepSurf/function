# Function: <code>fiemap_fill_next_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8121f940)
Location: fs/ioctl.c:85
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff8121f940-ffffffff8121fa42: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812471b0)
Location: fs/ioctl.c:85
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812471b0-ffffffff812472af: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8125a1a0)
Location: fs/ioctl.c:85
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff8125a1a0-ffffffff8125a29f: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81266b60)
Location: fs/ioctl.c:87
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff81266b60-ffffffff81266c6f: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81289400)
Location: fs/ioctl.c:88
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff81289400-ffffffff8128950f: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812af7a0)
Location: fs/ioctl.c:88
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812af7a0-ffffffff812af8ad: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812c4960)
Location: fs/ioctl.c:89
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812c4960-ffffffff812c4a6d: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e13a0)
Location: fs/ioctl.c:89
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812e13a0-ffffffff812e14ad: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812f2e70)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812f2e70-ffffffff812f2f7d: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132b0e0)
Location: fs/ioctl.c:112
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff8132b0e0-ffffffff8132b1f2: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff813366a0)
Location: fs/ioctl.c:112
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff813366a0-ffffffff813367b2: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133c980)
Location: fs/ioctl.c:115
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff8133c980-ffffffff8133ca8f: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138a680)
Location: fs/ioctl.c:115
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff8138a680-ffffffff8138a78f: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140b6b0)
Location: fs/ioctl.c:115
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff8140b6b0-ffffffff8140b7e5: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496040)
Location: fs/ioctl.c:115
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff81496040-ffffffff81496175: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb080)
Location: fs/ioctl.c:115
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff814cb080-ffffffff814cb1b5: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fd930)
Location: fs/ioctl.c:112
Inline: False
Direct callers:
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
**Symbols:**

```
ffffffff814fd930-ffffffff814fda65: fiemap_fill_next_extent (STB_GLOBAL)
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
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039db00)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffff80001039db00-ffff80001039dd20: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0582dcc)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
c0582dcc-c0582f1c: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c000000000498320)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
c000000000498320-c000000000498480: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffe00026955a)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffe00026955a-ffffffe000269630: fiemap_fill_next_extent (STB_GLOBAL)
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
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812eb450)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812eb450-ffffffff812eb55d: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812dc080)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812dc080-ffffffff812dc18d: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e9260)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812e9260-ffffffff812e936d: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fiemap_fill_next_extent(struct fiemap_extent_info *fieinfo, u64 logical, u64 phys, u64 len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812fa260)
Location: fs/ioctl.c:90
Inline: False
Direct callers:
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/iomap/fiemap.c:iomap_to_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fill_es_cache_info
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inline.c:ext4_inline_data_fiemap
```
**Symbols:**

```
ffffffff812fa260-ffffffff812fa36d: fiemap_fill_next_extent (STB_GLOBAL)
```
</details>
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
