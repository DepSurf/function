# Function: <code>filemap_range_has_page</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b5f90)
Location: mm/filemap.c:391
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff811b5f90-ffffffff811b604b: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ce8f0)
Location: mm/filemap.c:491
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff811ce8f0-ffffffff811ce9b7: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0490)
Location: mm/filemap.c:491
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff811f0490-ffffffff811f0561: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fbf10)
Location: mm/filemap.c:457
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff811fbf10-ffffffff811fbfb8: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213480)
Location: mm/filemap.c:466
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81213480-ffffffff81213528: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220c40)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81220c40-ffffffff81220ce8: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124dfd0)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff8124dfd0-ffffffff8124e077: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258520)
Location: mm/filemap.c:473
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81258520-ffffffff812585d4: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125cb00)
Location: mm/filemap.c:464
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8125cb00-ffffffff8125cbb4: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812989c0)
Location: mm/filemap.c:482
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff812989c0-ffffffff81298a74: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812eeff0)
Location: mm/filemap.c:470
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff812eeff0-ffffffff812ef0be: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81359ad0)
Location: mm/filemap.c:470
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81359ad0-ffffffff81359b9e: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b410)
Location: mm/filemap.c:475
Inline: False
Direct callers:
  - mm/filemap.c:kiocb_invalidate_pages
```
**Symbols:**

```
ffffffff8138b410-ffffffff8138b4de: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b4f30)
Location: mm/filemap.c:470
Inline: False
Direct callers:
  - mm/filemap.c:kiocb_invalidate_pages
```
**Symbols:**

```
ffffffff813b4f30-ffffffff813b4ffe: filemap_range_has_page (STB_GLOBAL)
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
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102adc38)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffff8000102adc38-ffff8000102adcf4: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dab40)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
c04dab40-c04dac14: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362470)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
c000000000362470-c000000000362570: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4446)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffe0001d4446-ffffffe0001d44ce: filemap_range_has_page (STB_GLOBAL)
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
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219290)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81219290-ffffffff81219338: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c4a0)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff8120c4a0-ffffffff8120c548: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217030)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81217030-ffffffff812170d8: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812260b0)
Location: mm/filemap.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff812260b0-ffffffff8122616b: filemap_range_has_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
