# Function: <code>SetPageSwapCache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a8e17)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff811d2736)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff811f1752)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c0395)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff811f03be)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81210d32)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d096d)
Location: include/linux/page-flags.h:332
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff81200d6e)
Location: include/linux/page-flags.h:332
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812230fc)
Location: include/linux/page-flags.h:332
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d8f70)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff8120bab9)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8122eb14)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ee1f0)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff812250aa)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8124ac61)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120eb27)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff81247669)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8126ea94)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81221eb5)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff8125bbcb)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8128251d)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812333f4)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff81276d89)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e816)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812415f0)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff81286867)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ae0b5)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/shmem.c (ffffffff8126d3bd)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff81291ae8)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812b8e05)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e4bcf)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81277bad)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff8129c3e9)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812c4578)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef5bb)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127c90d)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff812cb1fd)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f6251)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812baa6d)
Location: include/linux/page-flags.h:418
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff813101f8)
Location: include/linux/page-flags.h:418
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81340832)
Location: include/linux/page-flags.h:418
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131811e)
Location: include/linux/page-flags.h:571
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff8137ac8d)
Location: include/linux/page-flags.h:571
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d3978)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffff800010321018)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff800010350018)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fbcb4)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (c0539960)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c0551224)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000392bc8)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (c0000000003f64e0)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c0000000004335ac)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001efa36)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffe0002224ba)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffe00023ecec)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81239c40)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8127eeb7)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a6695)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122cc5c)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff81270ce7)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129813f)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812379e0)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8127cc57)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a44a5)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81246f77)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8128c827)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b3c13)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
</ul>

## Differences
