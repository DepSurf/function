# Function: <code>filemap_range_has_writeback</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool filemap_range_has_writeback(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f02c0)
Location: mm/filemap.c:630
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff812f02c0-ffffffff812f0569: filemap_range_has_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool filemap_range_has_writeback(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135b0b0)
Location: mm/filemap.c:627
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff8135b0b0-ffffffff8135b261: filemap_range_has_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool filemap_range_has_writeback(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138c810)
Location: mm/filemap.c:634
Inline: False
Direct callers:
  - mm/filemap.c:kiocb_write_and_wait
```
**Symbols:**

```
ffffffff8138c810-ffffffff8138c9cc: filemap_range_has_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool filemap_range_has_writeback(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b6370)
Location: mm/filemap.c:629
Inline: False
Direct callers:
  - mm/filemap.c:kiocb_write_and_wait
```
**Symbols:**

```
ffffffff813b6370-ffffffff813b652b: filemap_range_has_writeback (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
