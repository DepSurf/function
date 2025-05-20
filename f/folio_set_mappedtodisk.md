# Function: <code>folio_set_mappedtodisk</code>

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
In mm/migrate.c (ffffffff813b0901)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff81446139)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
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
In mm/migrate.c (ffffffff81431475)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff814d50ce)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/mpage.c (ffffffff814da00a)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
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
In mm/migrate.c (ffffffff81466df5)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff8150b22c)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/mpage.c (ffffffff8150df45)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff815dbd1d)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff81496058)
Location: include/linux/page-flags.h:515
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff8153ff99)
Location: include/linux/page-flags.h:515
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/mpage.c (ffffffff81542b52)
Location: include/linux/page-flags.h:515
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff816145e5)
Location: include/linux/page-flags.h:515
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
