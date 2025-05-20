# Function: <code>PageReclaim</code>

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
In mm/filemap.c (ffffffff8118d69a)
Location: include/linux/page-flags.h:246
Inline: True
```
```
In mm/page-writeback.c (ffffffff81198ab7)
Location: include/linux/page-flags.h:246
Inline: True
```
```
In mm/vmscan.c (ffffffff811a2f93)
Location: include/linux/page-flags.h:246
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811a029a)
Location: include/linux/page-flags.h:301
Inline: True
```
```
In mm/page-writeback.c (ffffffff811ad8c6)
Location: include/linux/page-flags.h:301
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811b972b)
Location: include/linux/page-flags.h:301
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811af41a)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811bde26)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811c9d82)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811b631a)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811c5fd6)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811d27c4)
Location: include/linux/page-flags.h:311
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811ca62a)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811dade6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff811e7cd7)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811eb6d5)
Location: include/linux/page-flags.h:319
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff811fbef9)
Location: include/linux/page-flags.h:319
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8120915f)
Location: include/linux/page-flags.h:319
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811fc215)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff8120e7d9)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8121be3f)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff81213b85)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121e2ec)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8122baa3)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff81221355)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122bd8c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8123996c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff8124ed35)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff8125871c)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff812660ce)
Location: include/linux/page-flags.h:372
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff81259cc5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff81262d2c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81270a83)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff8125df05)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff8126774c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81275584)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff8129a625)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
```
```
In mm/page-writeback.c (ffffffff812a42a8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff812b3182)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffff8000102af2a8)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffff8000102bc26c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffff8000102ca850)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (c04db580)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (c04e69bc)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (c04f46f4)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (c000000000363190)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (c000000000372fb8)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (c000000000387430)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffe0001d4b4e)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffe0001dd9f2)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffe0001e98d4)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff812199a5)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff812243dc)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff81231fbc)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff8120cbb5)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121758c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8122507c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff81217745)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122217c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8122fd5c)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff812267f5)
Location: include/linux/page-flags.h:364
Inline: True
```
```
In mm/page-writeback.c (ffffffff812315cc)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/vmscan.c (ffffffff8123f1a2)
Location: include/linux/page-flags.h:364
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
</ul>

## Differences
