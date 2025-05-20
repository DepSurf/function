# Function: <code>wbc_init_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244a64)
Location: include/linux/writeback.h:258
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8124dc1b)
Location: include/linux/writeback.h:258
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff812a012f)
Location: include/linux/writeback.h:258
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126cfba)
Location: include/linux/writeback.h:258
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81276381)
Location: include/linux/writeback.h:258
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff812ceabf)
Location: include/linux/writeback.h:258
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128024a)
Location: include/linux/writeback.h:271
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8128a009)
Location: include/linux/writeback.h:271
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff812e48ba)
Location: include/linux/writeback.h:271
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8128db2a)
Location: include/linux/writeback.h:272
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81296df7)
Location: include/linux/writeback.h:272
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff8131e534)
Location: include/linux/writeback.h:272
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812b06ea)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff812ba132)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff81342b54)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812d84db)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff812e2afb)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff81370977)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812eda69)
Location: include/linux/writeback.h:252
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff812f775c)
Location: include/linux/writeback.h:252
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff81388e6e)
Location: include/linux/writeback.h:252
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130f239)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81317da9)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813b2f76)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81322196)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8132ac1f)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813cbff8)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813597c9)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81364ac3)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813aa1bb)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
```
```
In fs/ext4/page-io.c (ffffffff81417488)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/ext4/page-io.c:io_submit_init_bio
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
In fs/buffer.c (ffffffff8136755c)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81371a95)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813bb80e)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
```
```
In fs/ext4/page-io.c (ffffffff8142ae9b)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/ext4/page-io.c:io_submit_init_bio
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
In fs/buffer.c (ffffffff8136df91)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81378d65)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c29d7)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/ext4/page-io.c (ffffffff8143275f)
Location: include/linux/writeback.h:282
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813bcc91)
Location: include/linux/writeback.h:283
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff813c574b)
Location: include/linux/writeback.h:283
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8141293c)
Location: include/linux/writeback.h:283
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/ext4/page-io.c (ffffffff8148601f)
Location: include/linux/writeback.h:283
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81443048)
Location: include/linux/writeback.h:287
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8144c5a5)
Location: include/linux/writeback.h:287
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff81489596)
Location: include/linux/writeback.h:287
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/ext4/page-io.c (ffffffff81509585)
Location: include/linux/writeback.h:287
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff814d2305)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff814da9cb)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8151cf51)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/ext4/page-io.c (ffffffff815a4173)
Location: include/linux/writeback.h:279
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81508bc8)
Location: include/linux/writeback.h:274
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8150eef9)
Location: include/linux/writeback.h:274
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff81555100)
Location: include/linux/writeback.h:274
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/ext4/page-io.c (ffffffff815dabf3)
Location: include/linux/writeback.h:274
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffffffff8153da5a)
Location: include/linux/writeback.h:273
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8154378b)
Location: include/linux/writeback.h:273
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8158b3d2)
Location: include/linux/writeback.h:273
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/ext4/page-io.c (ffffffff8161341a)
Location: include/linux/writeback.h:273
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffff8000103daec4)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffff8000103e6290)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffff8000104a41e8)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c05b42a0)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (c05bdff8)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (c0665f14)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c0000000004e0160)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (c0000000004ec580)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (c0000000005d13ac)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffe0002938da)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffe00029b830)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffe000325660)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8131a776)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff813231ff)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813c45d8)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130b316)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81313d9f)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813b5058)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81318246)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81320ccf)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813c1a68)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81329e66)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff813329ef)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813d6bc8)
Location: include/linux/writeback.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
</ul>

## Differences
