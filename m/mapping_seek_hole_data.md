# Function: <code>mapping_seek_hole_data</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t mapping_seek_hole_data(struct address_space *mapping, loff_t start, loff_t end, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812631c0)
Location: mm/filemap.c:2763
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff812631c0-ffffffff8126372a: mapping_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
loff_t mapping_seek_hole_data(struct address_space *mapping, loff_t start, loff_t end, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2844
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
**Symbols:**

```
ffffffff81cba009-ffffffff81cba0ad: mapping_seek_hole_data.cold (STB_LOCAL)
ffffffff8129f8f0-ffffffff8129fee3: mapping_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
loff_t mapping_seek_hole_data(struct address_space *mapping, loff_t start, loff_t end, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2896
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
**Symbols:**

```
ffffffff81e6b69e-ffffffff81e6b7b9: mapping_seek_hole_data.cold (STB_LOCAL)
ffffffff812f6910-ffffffff812f6fe6: mapping_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
loff_t mapping_seek_hole_data(struct address_space *mapping, loff_t start, loff_t end, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2903
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
**Symbols:**

```
ffffffff820622d9-ffffffff820623f4: mapping_seek_hole_data.cold (STB_LOCAL)
ffffffff81360230-ffffffff8136081f: mapping_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
loff_t mapping_seek_hole_data(struct address_space *mapping, loff_t start, loff_t end, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:3047
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
**Symbols:**

```
ffffffff820e1ab2-ffffffff820e1bcf: mapping_seek_hole_data.cold (STB_LOCAL)
ffffffff813927c0-ffffffff81392dc9: mapping_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
loff_t mapping_seek_hole_data(struct address_space *mapping, loff_t start, loff_t end, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2994
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
**Symbols:**

```
ffffffff821be4e7-ffffffff821be5f4: mapping_seek_hole_data.cold (STB_LOCAL)
ffffffff813bc480-ffffffff813bca7d: mapping_seek_hole_data (STB_GLOBAL)
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
