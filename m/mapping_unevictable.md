# Function: <code>mapping_unevictable</code>

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
In mm/vmscan.c (ffffffff811a2c62)
Location: include/linux/pagemap.h:50
Inline: True
```
```
In mm/shmem.c (ffffffff811ab501)
Location: include/linux/pagemap.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff811b9322)
Location: include/linux/pagemap.h:50
Inline: True
```
```
In mm/shmem.c (ffffffff811c3d91)
Location: include/linux/pagemap.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff811c9962)
Location: include/linux/pagemap.h:51
Inline: True
```
```
In mm/shmem.c (ffffffff811d3dc1)
Location: include/linux/pagemap.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff811d23f2)
Location: include/linux/pagemap.h:70
Inline: True
```
```
In mm/shmem.c (ffffffff811dc581)
Location: include/linux/pagemap.h:70
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff811e7892)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In mm/shmem.c (ffffffff811f23fd)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff81208e22)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff81213895)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff8121bb02)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff812267d5)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff8122b7a2)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff812366b8)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff81239672)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff812448f8)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/swap.c (ffffffff8125f45c)
Location: include/linux/pagemap.h:76
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812658b0)
Location: include/linux/pagemap.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812725a1)
Location: include/linux/pagemap.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812966d2)
Location: include/linux/pagemap.h:76
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
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
In mm/swap.c (ffffffff81269a5a)
Location: include/linux/pagemap.h:78
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812701fd)
Location: include/linux/pagemap.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127ca61)
Location: include/linux/pagemap.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812a1646)
Location: include/linux/pagemap.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
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
In mm/swap.c (ffffffff8126d84a)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81276005)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81281c37)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812a73ba)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff812a9eba)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812b265a)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812bfb77)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812e89f7)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81303270)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8130f441)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8131c462)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8134ac67)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
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
In mm/swap.c (ffffffff8136ea66)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff8137e754)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:should_skip_vma
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff81390052)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff813c385c)
Location: include/linux/pagemap.h:247
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
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
In mm/swap.c (ffffffff813a0b96)
Location: include/linux/pagemap.h:251
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813afe3e)
Location: include/linux/pagemap.h:251
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:should_skip_vma
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813c29b2)
Location: include/linux/pagemap.h:251
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff813f8b6f)
Location: include/linux/pagemap.h:251
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
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
In mm/swap.c (ffffffff813ca813)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813d932b)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:should_skip_vma
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813ed652)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8142472c)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
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
In mm/vmscan.c (ffff8000102ca588)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffff8000102d6e60)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (c04f43c4)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (c04fed5c)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (c00000000038705c)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (c000000000397000)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffe0001e963e)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffe0001f2230)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff81231cc2)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff8123cf48)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff81224d82)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff8122ff48)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff8122fa62)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff8123ace8)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
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
In mm/vmscan.c (ffffffff8123eeac)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
```
```
In mm/shmem.c (ffffffff8124a3f1)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
</details>
</li>
</ul>

## Differences
