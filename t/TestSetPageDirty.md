# Function: <code>TestSetPageDirty</code>

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
In mm/page-writeback.c (ffffffff81198af1)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff81242965)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty
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
In mm/page-writeback.c (ffffffff811ad92d)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8126ada6)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
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
In mm/page-writeback.c (ffffffff811bde8d)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8127ded6)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
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
In mm/page-writeback.c (ffffffff811c603d)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8128ba94)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
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
In mm/page-writeback.c (ffffffff811dae50)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff812ae64a)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
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
In mm/page-writeback.c (ffffffff811fbf50)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff812d622b)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
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
In mm/page-writeback.c (ffffffff8120e830)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff812eb5fb)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap.c (ffffffff81323794)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/iomap.c:iomap_set_page_dirty
  - fs/iomap.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff8121e346)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8130ccfb)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134b304)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff8122bde6)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff81321277)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813635b4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff81258778)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8135a02b)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813a9eb4)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff81262d88)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff81368149)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813bb504)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff812677a8)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8136ec09)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813c2624)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff812a430d)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
```
```
In fs/buffer.c (ffffffff813bc746)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
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
In fs/buffer.c (ffffffff81446417)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
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
In fs/buffer.c (ffffffff814d54f7)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
</details>
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
In mm/page-writeback.c (ffff8000102bc2f4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffff8000103da830)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffff80001042a294)
Location: include/linux/page-flags.h:318
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
In mm/page-writeback.c (c04e6a10)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (c05b1430)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (c05f2ea4)
Location: include/linux/page-flags.h:318
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
In mm/page-writeback.c (c000000000373070)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (c0000000004dc398)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (c00000000053ab84)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffe0001dda54)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffe000292a54)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffe0002c849a)
Location: include/linux/page-flags.h:318
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
In mm/page-writeback.c (ffffffff81224436)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff81319857)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8135bb94)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff812175e6)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff8130a417)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134c834)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff812221d6)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff81317327)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81359664)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
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
In mm/page-writeback.c (ffffffff81231626)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In fs/buffer.c (ffffffff81327969)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8136cd64)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
</details>
</li>
</ul>

## Differences
