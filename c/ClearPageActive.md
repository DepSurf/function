# Function: <code>ClearPageActive</code>

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
In mm/filemap.c (ffffffff8118df70)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8119d0fc)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811a355f)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_active_list
```
```
In mm/memory-failure.c (ffffffff81201911)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/filemap.c (ffffffff811a100e)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811b3723)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_file
```
```
In mm/vmscan.c (ffffffff811babb0)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812120cf)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8121b123)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8122663a)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/filemap.c (ffffffff811b0c0e)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811c3da7)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_file
```
```
In mm/vmscan.c (ffffffff811cb240)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81224248)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122c837)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81238c0a)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/filemap.c (ffffffff811b813e)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811cc197)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff811d3dd4)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff8122f95f)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81239042)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8124506b)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/filemap.c (ffffffff811cc82e)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811e1187)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff811e9324)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff8124d601)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81257747)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81264f5f)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/filemap.c (ffffffff811ed60f)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81201fea)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff8120a876)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81271119)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127b8b3)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8128927f)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff8121496a)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff8121d566)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81285725)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8128fcb2)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8129e1cf)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff81224627)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff8122cf0c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff8129fdd7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812aad4f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff812b9395)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff812323b7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff8123a4c2)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812b1177)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812bc320)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812cb285)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff8125f471)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff8126a14d)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812e65ce)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812f185c)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff81301595)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff81269a74)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff81274bfb)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812f19e2)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812fddb1)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8130d665)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff8126d85c)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff81279efb)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812f7d6f)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff81304f20)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813139a5)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff812a9ecf)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff812b7f1c)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff813423df)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff8134ecb3)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8135ec95)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff81305d17)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff81313a74)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/mlock.c (ffffffff8134b3a9)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/mlock.c:__mlock_page
```
```
In mm/migrate.c (ffffffff813b462e)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff813c58e4)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813d928f)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/mlock.c (ffffffff813c426d)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/mlock.c:__mlock_page
```
```
In mm/khugepaged.c (ffffffff8144a246)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8145f54f)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/khugepaged.c (ffffffff8148048b)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8149576a)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814ae59a)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
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
In mm/swap.c (ffff8000102c1094)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffff8000102cb42c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffff800010351730)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffff80001035d498)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffff80001036e6a0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (c04ed4d8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (c04f5474)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (c0552c10)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/swap.c (c00000000037c128)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (c000000000388420)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (c000000000437cd0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (c000000000448f94)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (c00000000045fab8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffe0001e35ba)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffe0001ea2ac)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffe00023fd96)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/swap.c (ffffffff8122aa07)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff81232b12)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812a9757)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b4900)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812c3865)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff8121db27)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff81225bb2)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff8129b0b7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a5962)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812b48a5)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff812287a7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff812308b2)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812a7567)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b2710)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812c1675)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/swap.c (ffffffff81237b17)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
```
In mm/vmscan.c (ffffffff8123fd02)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff812b786d)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c2de4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812d2135)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
</details>
</li>
</ul>

## Differences
