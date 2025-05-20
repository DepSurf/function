# Function: <code>folio_set_readahead</code>

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
In mm/readahead.c (ffffffff81301dbb)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/migrate.c (ffffffff813b0997)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/readahead.c (ffffffff8136c545)
Location: include/linux/page-flags.h:525
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/migrate.c (ffffffff81431520)
Location: include/linux/page-flags.h:525
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/readahead.c (ffffffff8139e768)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/migrate.c (ffffffff81466ea0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/readahead.c (ffffffff813c8339)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap_state.c (ffffffff81466125)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/migrate.c (ffffffff814960fa)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
