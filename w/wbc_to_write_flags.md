# Function: <code>wbc_to_write_flags</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812009d2)
Location: include/linux/writeback.h:106
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff81280352)
Location: include/linux/writeback.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81289bbc)
Location: include/linux/writeback.h:106
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8120b63d)
Location: include/linux/writeback.h:106
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8128dc2f)
Location: include/linux/writeback.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812968a9)
Location: include/linux/writeback.h:106
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81224b23)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff812b081f)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812b9b09)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81246e77)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff812d85f5)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812e26d0)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8125b29b)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff812edac5)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812f7331)
Location: include/linux/writeback.h:85
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812763dc)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8130f295)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8131794b)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81285ecc)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff813221f5)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8132a7cb)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812b81ec)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8135c455)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81364486)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813aa17c)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812c3897)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8136a8d5)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81371488)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813bb7cf)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812ca617)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8136ffe5)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81378758)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c2995)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8130f614)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff813beb65)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813c5054)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff814128fa)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81379a17)
Location: include/linux/writeback.h:104
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff814472b5)
Location: include/linux/writeback.h:104
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8144c52e)
Location: include/linux/writeback.h:104
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff81489531)
Location: include/linux/writeback.h:104
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff813f77eb)
Location: include/linux/writeback.h:96
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff814d5ef5)
Location: include/linux/writeback.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff814da954)
Location: include/linux/writeback.h:96
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8151ceec)
Location: include/linux/writeback.h:96
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8142a9f0)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
```
```
In fs/buffer.c (ffffffff8150b355)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/mpage.c (ffffffff8150ee76)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff815550a7)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81464176)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
```
```
In fs/buffer.c (ffffffff815401b5)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/mpage.c (ffffffff81543723)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8158b379)
Location: include/linux/writeback.h:94
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffff800010320470)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffff8000103dafcc)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffff8000103e5fd0)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0538f70)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (c05b4350)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (c05bdae0)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0000000003f55c4)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (c0000000004e0258)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (c0000000004ec14c)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffe000221c00)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffe000293966)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffe00029b384)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127e51c)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8131a7d5)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81322dab)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127034c)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8130b375)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8131394b)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127c2bc)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff813182a5)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8132087b)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8128be8c)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff81329ec5)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8133259b)
Location: include/linux/writeback.h:97
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
</ul>

## Differences
