# Function: <code>folio_set_swapcache</code>

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
In mm/migrate.c (ffffffff813b2271)
Location: include/linux/page-flags.h:571
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
In mm/shmem.c (ffffffff8138ab6e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/swap_state.c (ffffffff813f87c1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81431d1c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
In mm/shmem.c (ffffffff813bd09f)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/swap_state.c (ffffffff8142b583)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8146796c)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
In mm/shmem.c (ffffffff813e7f0f)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/swap_state.c (ffffffff81464d71)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81496c35)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
