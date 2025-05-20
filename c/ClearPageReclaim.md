# Function: <code>ClearPageReclaim</code>

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
In mm/filemap.c (ffffffff8118d715)
Location: include/linux/page-flags.h:246
Inline: True
```
```
In mm/page-writeback.c (ffffffff81198ae0)
Location: include/linux/page-flags.h:246
Inline: True
```
```
In mm/vmscan.c (ffffffff811a0ab7)
Location: include/linux/page-flags.h:246
Inline: True
```
```
In mm/page_io.c (ffffffff811d1ee8)
Location: include/linux/page-flags.h:246
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:__swap_writepage
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
In mm/filemap.c (ffffffff811a02b6)
Location: include/linux/page-flags.h:301
Inline: True
```
```
In mm/page-writeback.c (ffffffff811ad8fe)
Location: include/linux/page-flags.h:301
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811b6ed3)
Location: include/linux/page-flags.h:301
Inline: True
```
```
In mm/page_io.c (ffffffff811eff93)
Location: include/linux/page-flags.h:301
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff811af436)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811bde5e)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811c74d3)
Location: include/linux/page-flags.h:311
Inline: True
```
```
In mm/page_io.c (ffffffff81200942)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff811b6336)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811c600e)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811cfb90)
Location: include/linux/page-flags.h:311
Inline: True
```
```
In mm/page_io.c (ffffffff8120b59b)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff811ca646)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811dae21)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811e4ff8)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/page_io.c (ffffffff81224a7d)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff811eb6f6)
Location: include/linux/page-flags.h:319
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811fbf21)
Location: include/linux/page-flags.h:319
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81206738)
Location: include/linux/page-flags.h:319
Inline: True
```
```
In mm/page_io.c (ffffffff812470b4)
Location: include/linux/page-flags.h:319
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff811fc236)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff8120e801)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff812192fa)
Location: include/linux/page-flags.h:331
Inline: True
```
```
In mm/page_io.c (ffffffff8125b50c)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff81213ba7)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121e315)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81228aec)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffff81276675)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff81221377)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122bdb5)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8123698c)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffff81286165)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff8124ed57)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff81258747)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81265c3a)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/page_io.c (ffffffff812b846f)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff81259ce7)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff81262d57)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81270605)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/page_io.c (ffffffff812c3b3c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff8125df27)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff81267777)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81274ba8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/page_io.c (ffffffff812ca8f3)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff8129a647)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff812a42dc)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff812b1e4e)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/page_io.c (ffffffff8130f8f6)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81379267)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff813f6c27)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81429b29)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff814631db)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:sio_write_complete
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
In mm/filemap.c (ffff8000102af2c4)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffff8000102bc278)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffff8000102c86b0)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffff80001032067c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (c04db5a0)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (c04e69c4)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (c04f4dfc)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/page_io.c (c0539178)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (c0000000003631b4)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (c000000000373000)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (c0000000003846d4)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (c0000000003f586c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffe0001d4b62)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffe0001dda1a)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffe0001e70b6)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffe000221e08)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff812199c7)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff81224405)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8122efdc)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffff8127e7b5)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff8120cbd7)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff812175b5)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8122209c)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffff812705e5)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff81217767)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff812221a5)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8122cd7c)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffff8127c555)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
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
In mm/filemap.c (ffffffff81226817)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff812315f5)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8123c1ac)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page_io.c (ffffffff8128c125)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
</ul>

## Differences
