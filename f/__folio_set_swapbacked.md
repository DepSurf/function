# Function: <code>__folio_set_swapbacked</code>

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
In mm/shmem.c (ffffffff81316e61)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/migrate.c (ffffffff813b1f8b)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
In mm/shmem.c (ffffffff81390403)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/memory.c (ffffffff813bc334)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff813f9753)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81431abd)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
In mm/shmem.c (ffffffff813c2d50)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/memory.c (ffffffff813f0c02)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8140c677)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8142c4f4)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff814676df)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
In mm/shmem.c (ffffffff813ed9c8)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
```
```
In mm/memory.c (ffffffff814206ee)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81438efd)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81465c2c)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81496b9c)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
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
