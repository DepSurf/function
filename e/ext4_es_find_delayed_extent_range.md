# Function: <code>ext4_es_find_delayed_extent_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812dbb00)
Location: fs/ext4/extents_status.c:244
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:ext4_find_delalloc_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff812dbb00-ffffffff812dbcd4: ext4_es_find_delayed_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8130b470)
Location: fs/ext4/extents_status.c:244
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_find_delalloc_range
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
```
**Symbols:**

```
ffffffff8130b470-ffffffff8130b61c: ext4_es_find_delayed_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81321470)
Location: fs/ext4/extents_status.c:244
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_find_delalloc_range
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
```
**Symbols:**

```
ffffffff81321470-ffffffff8132161c: ext4_es_find_delayed_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812f0400)
Location: fs/ext4/extents_status.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_find_delalloc_range
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_get_next_extent
```
**Symbols:**

```
ffffffff812f0400-ffffffff812f059c: ext4_es_find_delayed_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81314f10)
Location: fs/ext4/extents_status.c:245
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_find_delalloc_range
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81314f10-ffffffff813150b2: ext4_es_find_delayed_extent_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81342d40)
Location: fs/ext4/extents_status.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_find_delalloc_range
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81342d40-ffffffff81342ec6: ext4_es_find_delayed_extent_range (STB_GLOBAL)
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
