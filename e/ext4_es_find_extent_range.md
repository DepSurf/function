# Function: <code>ext4_es_find_extent_range</code>

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
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135a810)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8135a810-ffffffff8135a915: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383850)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81383850-ffffffff81383955: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139c2e0)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8139c2e0-ffffffff8139c3e5: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e7a00)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff813e7a00-ffffffff813e7b01: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f9cc0)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff813f9cc0-ffffffff813f9d9f: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400080)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff81400080-ffffffff8140015f: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814526a0)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff814526a0-ffffffff81452779: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cf990)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff814cf990-ffffffff814cfac4: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81568290)
Location: fs/ext4/extents_status.c:307
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff81568290-ffffffff815683c4: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159fe30)
Location: fs/ext4/extents_status.c:307
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff8159fe30-ffffffff8159ff64: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d8ae0)
Location: fs/ext4/extents_status.c:308
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_determine_insert_hole
```
**Symbols:**

```
ffffffff815d8ae0-ffffffff815d8c14: ext4_es_find_extent_range (STB_GLOBAL)
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
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046ef58)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffff80001046ef58-ffff80001046f104: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0630600)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
c0630600-c0630784: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058f3a0)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
c00000000058f3a0-c00000000058f550: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fbd44)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffe0002fbd44-ffffffe0002fbe5c: ext4_es_find_extent_range (STB_GLOBAL)
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
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813948c0)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813948c0-ffffffff813949c5: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81385350)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81385350-ffffffff81385455: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81392220)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81392220-ffffffff81392325: ext4_es_find_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6100)
Location: fs/ext4/extents_status.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813a6100-ffffffff813a6224: ext4_es_find_extent_range (STB_GLOBAL)
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
