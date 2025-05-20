# Function: <code>cancel_dirty_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cancel_dirty_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119b920)
Location: mm/page-writeback.c:2611
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8119b920-ffffffff8119ba01: cancel_dirty_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cancel_dirty_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811b09e0)
Location: mm/page-writeback.c:2656
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff811b09e0-ffffffff811b0ad9: cancel_dirty_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cancel_dirty_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c0fc0)
Location: mm/page-writeback.c:2623
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff811c0fc0-ffffffff811c10b9: cancel_dirty_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cancel_dirty_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c9200)
Location: mm/page-writeback.c:2626
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff811c9200-ffffffff811c92f1: cancel_dirty_page (STB_GLOBAL)
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
In mm/truncate.c (ffffffff811e1be8)
Location: include/linux/mm.h:1483
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff812afa2c)
Location: include/linux/mm.h:1483
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
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
In mm/truncate.c (ffffffff812032c4)
Location: include/linux/mm.h:1570
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff812d78ac)
Location: include/linux/mm.h:1570
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
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
In mm/truncate.c (ffffffff81215c64)
Location: include/linux/mm.h:1640
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff812ecd0c)
Location: include/linux/mm.h:1640
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap.c (ffffffff81325ad4)
Location: include/linux/mm.h:1640
Inline: True
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
In mm/truncate.c (ffffffff81225647)
Location: include/linux/mm.h:1652
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff8130e4c0)
Location: include/linux/mm.h:1652
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134cca0)
Location: include/linux/mm.h:1652
Inline: True
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
In mm/truncate.c (ffffffff81233497)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff813214e0)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81364f70)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (ffffffff81260c77)
Location: include/linux/mm.h:1811
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff8135bc24)
Location: include/linux/mm.h:1811
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813ac0ff)
Location: include/linux/mm.h:1811
Inline: True
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
In mm/truncate.c (ffffffff8126b057)
Location: include/linux/mm.h:1856
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff8136a1c4)
Location: include/linux/mm.h:1856
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813bdfa0)
Location: include/linux/mm.h:1856
Inline: True
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
In mm/truncate.c (ffffffff8127018f)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff81370de3)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813c5160)
Location: include/linux/mm.h:1864
Inline: True
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
In mm/truncate.c (ffffffff812ad41f)
Location: include/linux/mm.h:1893
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff813bfa82)
Location: include/linux/mm.h:1893
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81414b9d)
Location: include/linux/mm.h:1893
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c3a50)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffff8000103d88a8)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffff80001042aa28)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (c04ee56c)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (c05b32bc)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (c05f4c90)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (c00000000037deb4)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (c0000000004deb80)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (c00000000053c3b0)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (ffffffe0001e460e)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffe000292f18)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8b9e)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (ffffffff8122bae7)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff81319ac0)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8135d550)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (ffffffff8121ebd7)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff8130a680)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134e1f0)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (ffffffff81229887)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff81317590)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8135b020)
Location: include/linux/mm.h:1624
Inline: True
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
In mm/truncate.c (ffffffff81238c97)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In fs/buffer.c (ffffffff8132917d)
Location: include/linux/mm.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8136e7a0)
Location: include/linux/mm.h:1624
Inline: True
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
</ul>
