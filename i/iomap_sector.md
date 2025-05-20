# Function: <code>iomap_sector</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130e2ae)
Location: fs/iomap.c:101
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323ad9)
Location: fs/iomap.c:102
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
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
In fs/iomap/buffered-io.c (ffffffff8134bf34)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134d9f2)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (ffffffff81364204)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff81365cb0)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/dax.c (ffffffff8138fbe9)
Location: include/linux/iomap.h:93
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_zero
```
```
In fs/iomap/buffered-io.c (ffffffff813a9f90)
Location: include/linux/iomap.h:93
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813ad100)
Location: include/linux/iomap.h:93
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/dax.c (0)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_zero
```
```
In fs/iomap/buffered-io.c (ffffffff813bb5e0)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813be7f0)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/dax.c (0)
Location: include/linux/iomap.h:95
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_zero
```
```
In fs/iomap/buffered-io.c (ffffffff813c2703)
Location: include/linux/iomap.h:95
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813c5db8)
Location: include/linux/iomap.h:95
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/dax.c (0)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_zero
```
```
In fs/iomap/buffered-io.c (ffffffff814127e5)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81415778)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/iomap/fiemap.c (ffffffff81416327)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
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
In fs/iomap/buffered-io.c (ffffffff81489445)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8148cfb5)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/iomap/fiemap.c (ffffffff8148dbf4)
Location: include/linux/iomap.h:94
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
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
In fs/iomap/buffered-io.c (ffffffff8151ce05)
Location: include/linux/iomap.h:104
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff815204c2)
Location: include/linux/iomap.h:104
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/iomap/fiemap.c (ffffffff815213d4)
Location: include/linux/iomap.h:104
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
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
In fs/iomap/buffered-io.c (ffffffff81554fe4)
Location: include/linux/iomap.h:104
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81558480)
Location: include/linux/iomap.h:104
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/iomap/fiemap.c (ffffffff81559414)
Location: include/linux/iomap.h:104
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
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
In fs/iomap/buffered-io.c (ffffffff8158b2b4)
Location: include/linux/iomap.h:108
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8158eb7f)
Location: include/linux/iomap.h:108
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/iomap/fiemap.c (ffffffff8158fba4)
Location: include/linux/iomap.h:108
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
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
In fs/iomap/buffered-io.c (ffff80001042b524)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffff80001042cb50)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (c05f3f70)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c05f57dc)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (c00000000053c5cc)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c00000000053e254)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (ffffffe0002c8dd2)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffe0002c9f2c)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (ffffffff8135c7e4)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135e290)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (ffffffff8134d484)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134ef30)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (ffffffff8135a2b4)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135bd60)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
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
In fs/iomap/buffered-io.c (ffffffff8136d9f8)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8136f4b0)
Location: include/linux/iomap.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
</details>
</li>
</ul>

## Differences
