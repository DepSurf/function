# Function: <code>folio_test_set_dirty</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fc6a8)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In fs/buffer.c (ffffffff81442b1e)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/buffer.c:block_dirty_folio
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
In mm/page-writeback.c (ffffffff813669c8)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/shmem.c (ffffffff8138f78c)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In fs/buffer.c (ffffffff814d1b2e)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/buffer.c:block_dirty_folio
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
In mm/page-writeback.c (ffffffff81399035)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/shmem.c (ffffffff813bf636)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In fs/buffer.c (ffffffff81508365)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
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
In mm/page-writeback.c (ffffffff813c2e35)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/shmem.c (ffffffff813ea66e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In fs/buffer.c (ffffffff8153d115)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
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
