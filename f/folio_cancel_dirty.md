# Function: <code>folio_cancel_dirty</code>

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
In mm/truncate.c (ffffffff81307bb1)
Location: include/linux/pagemap.h:1064
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/buffer.c (ffffffff81443976)
Location: include/linux/pagemap.h:1064
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81489c55)
Location: include/linux/pagemap.h:1064
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
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
In mm/truncate.c (ffffffff81371dd9)
Location: include/linux/pagemap.h:1056
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/buffer.c (ffffffff814d21d6)
Location: include/linux/pagemap.h:1056
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8151db53)
Location: include/linux/pagemap.h:1056
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
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
In mm/truncate.c (ffffffff813a3f87)
Location: include/linux/pagemap.h:1067
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/buffer.c (ffffffff81509be6)
Location: include/linux/pagemap.h:1067
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81555568)
Location: include/linux/pagemap.h:1067
Inline: True
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
In mm/truncate.c (ffffffff813cdb06)
Location: include/linux/pagemap.h:1154
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In fs/buffer.c (ffffffff8153ea16)
Location: include/linux/pagemap.h:1154
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8158b7ba)
Location: include/linux/pagemap.h:1154
Inline: True
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
