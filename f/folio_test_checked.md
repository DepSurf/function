# Function: <code>folio_test_checked</code>

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
In mm/migrate.c (ffffffff813b08e8)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff814e099a)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_release_folio
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
In mm/migrate.c (ffffffff8143145c)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff81579eca)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_release_folio
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
In mm/migrate.c (ffffffff81466ddc)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff815b1a6a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
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
In mm/migrate.c (ffffffff8149603f)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/ext4/inode.c (ffffffff815ea68a)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
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
