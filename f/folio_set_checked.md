# Function: <code>folio_set_checked</code>

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
In mm/migrate.c (ffffffff813b08f0)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff814dfde0)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
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
In mm/migrate.c (ffffffff81431464)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff815790b0)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
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
In mm/migrate.c (ffffffff81466de4)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff815b04f4)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
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
In mm/migrate.c (ffffffff81496047)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff815e92e1)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
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
