# Function: <code>folio_clear_mappedtodisk</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81307bb8)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
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
In mm/truncate.c (ffffffff81371de0)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/fuse/dev.c (ffffffff8161af39)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/truncate.c (ffffffff813a3f8e)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/fuse/dev.c (ffffffff816530a9)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/truncate.c (ffffffff813cdb0d)
Location: include/linux/page-flags.h:515
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/fuse/dev.c (ffffffff8168c6b6)
Location: include/linux/page-flags.h:515
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
