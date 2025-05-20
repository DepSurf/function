# Function: <code>wait_for_stable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198b50)
Location: mm/page-writeback.c:2812
Inline: True
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:grab_cache_page_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff81198b50-ffffffff81198bb4: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811adb00)
Location: mm/page-writeback.c:2872
Inline: True
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff811adb00-ffffffff811adb64: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811be060)
Location: mm/page-writeback.c:2839
Inline: True
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff811be060-ffffffff811be0c4: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c6250)
Location: mm/page-writeback.c:2848
Inline: True
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff811c6250-ffffffff811c62b3: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811db060)
Location: mm/page-writeback.c:2831
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff811db060-ffffffff811db0d2: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fc510)
Location: mm/page-writeback.c:2828
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff811fc510-ffffffff811fc582: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120ee00)
Location: mm/page-writeback.c:2811
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8120ee00-ffffffff8120ee72: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121e5b0)
Location: mm/page-writeback.c:2831
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8121e5b0-ffffffff8121e60b: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122c050)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8122c050-ffffffff8122c0ab: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81259d40)
Location: mm/page-writeback.c:2852
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81259d40-ffffffff81259db7: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81263210)
Location: mm/page-writeback.c:2844
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81263210-ffffffff81263240: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81267cc0)
Location: mm/page-writeback.c:2857
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81267cc0-ffffffff81267cf0: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a4730)
Location: mm/page-writeback.c:2912
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff812a4730-ffffffff812a4760: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300c50)
Location: mm/folio-compat.c:36
Inline: False
Direct callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81300c50-ffffffff81300cab: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b4f0)
Location: mm/folio-compat.c:36
Inline: False
Direct callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8136b4f0-ffffffff8136b54b: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d6a0)
Location: mm/folio-compat.c:37
Inline: False
```
**Symbols:**

```
ffffffff8139d6a0-ffffffff8139d70a: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7400)
Location: mm/folio-compat.c:37
Inline: False
```
**Symbols:**

```
ffffffff813c7400-ffffffff813c7467: wait_for_stable_page (STB_GLOBAL)
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
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102badd8)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffff8000102badd8-ffff8000102bae54: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e6d98)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
c04e6d98-c04e6e0c: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003732f0)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
c0000000003732f0-c000000000373390: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001ddbb6)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffe0001ddbb6-ffffffe0001ddc1c: wait_for_stable_page (STB_GLOBAL)
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
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812246a0)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff812246a0-ffffffff812246fb: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81217850)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81217850-ffffffff812178ab: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81222440)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81222440-ffffffff8122249b: wait_for_stable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wait_for_stable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81231a20)
Location: mm/page-writeback.c:2842
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:filemap_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81231a20-ffffffff81231a7b: wait_for_stable_page (STB_GLOBAL)
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
