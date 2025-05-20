# Function: <code>set_page_writeback_keepwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812a0009)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812ce8be)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812e46b2)
Location: include/linux/page-flags.h:484
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8131e395)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813429b5)
Location: include/linux/page-flags.h:488
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81370829)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff81388cb6)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813b2dc4)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813cbe46)
Location: include/linux/page-flags.h:545
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
In fs/iomap/buffered-io.c (ffffffff813ab9a4)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/page-io.c (ffffffff81417ff7)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff8142baf4)
Location: include/linux/page-flags.h:565
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff814327bb)
Location: include/linux/page-flags.h:565
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff8148607b)
Location: include/linux/page-flags.h:585
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff81509399)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff815a407a)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffff8000104a3ff8)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (c0665cd8)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (c0000000005d0f10)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffe000325526)
Location: include/linux/page-flags.h:545
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c4426)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813b4ea6)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813c18b6)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813d6a16)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
</ul>

## Differences
