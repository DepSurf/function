# Function: <code>to_iomap_page</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813235b5)
Location: include/linux/iomap.h:115
Inline: True
Inline callers:
  - fs/iomap.c:iomap_is_partially_uptodate
  - fs/iomap.c:iomap_read_end_io
  - fs/iomap.c:iomap_set_range_uptodate
  - fs/iomap.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b275)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363525)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ab691)
Location: fs/iomap/buffered-io.c:35
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bc05a)
Location: fs/iomap/buffered-io.c:35
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3537)
Location: fs/iomap/buffered-io.c:35
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81412536)
Location: fs/iomap/buffered-io.c:35
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_create
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
In fs/iomap/buffered-io.c (ffffffff81488570)
Location: fs/iomap/buffered-io.c:37
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_create
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
In fs/iomap/buffered-io.c (ffffffff8151c3e6)
Location: fs/iomap/buffered-io.c:37
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_create
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
In fs/iomap/buffered-io.c (ffffffff815545f3)
Location: fs/iomap/buffered-io.c:37
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_create
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff800010429f0c)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f26dc)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a168)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7958)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135bb05)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c7a5)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813595d5)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136ccd5)
Location: include/linux/iomap.h:145
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
</details>
</li>
</ul>

## Differences
