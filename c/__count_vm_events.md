# Function: <code>__count_vm_events</code>

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
In mm/page_alloc.c (ffffffff811943ec)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/swap.c (ffffffff8119dc03)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff811a22a0)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In fs/inode.c (ffffffff812281e5)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/page_alloc.c (ffffffff811a98c0)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811b2e53)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff811bcc86)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In fs/inode.c (ffffffff81250915)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/page_alloc.c (ffffffff811b9dff)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811c34c3)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff811cd363)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In fs/inode.c (ffffffff812639b5)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/page_alloc.c (ffffffff811c1d95)
Location: include/linux/vmstat.h:43
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811cb933)
Location: include/linux/vmstat.h:43
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff811d5e2a)
Location: include/linux/vmstat.h:43
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In fs/inode.c (ffffffff81271380)
Location: include/linux/vmstat.h:43
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/page_alloc.c (ffffffff811d62f7)
Location: include/linux/vmstat.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811e0d23)
Location: include/linux/vmstat.h:54
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff811eb34a)
Location: include/linux/vmstat.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In fs/inode.c (ffffffff81293ca0)
Location: include/linux/vmstat.h:54
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/page_alloc.c (ffffffff811f76ed)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff812025b3)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff8120cd25)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In fs/inode.c (ffffffff812b9fcf)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/page_alloc.c (ffffffff8120a0c4)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff81214f33)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff8121f9e2)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In fs/inode.c (ffffffff812cefc6)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff812241e3)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff8122f357)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff8126f17b)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff812ebef3)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff81231f73)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff8123d4e7)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff8127dfbb)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff812fda4a)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff8125f5ea)
Location: include/linux/vmstat.h:73
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81265a9d)
Location: include/linux/vmstat.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812b0c35)
Location: include/linux/vmstat.h:73
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff81336ea4)
Location: include/linux/vmstat.h:73
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff81269c9c)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff8127023b)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/mlock.c (0)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff812bca48)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff813427e4)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff8126d88a)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff81276044)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/mlock.c (0)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff812c4731)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff81348972)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff812a9efb)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff812b269c)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mlock.c (0)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff81308874)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff813965fb)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff813033c0)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:pagevec_move_tail_fn
```
```
In mm/vmscan.c (ffffffff8130f70b)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mlock.c (ffffffff8134c275)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_alloc.c (ffffffff81370c67)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff81417b26)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff813701ac)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff8137e9c9)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:demote_folio_list
```
```
In mm/mlock.c (ffffffff813c4df5)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_alloc.c (ffffffff813ed10a)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff814a32c6)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff813a232c)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813b00b0)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:demote_folio_list
```
```
In mm/mlock.c (ffffffff813f9363)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/page_alloc.c (ffffffff81422068)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff814d8416)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff813cbfa4)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813d9598)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/mlock.c (ffffffff81424f10)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/page_alloc.c (ffffffff8144ee9a)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff8150abf6)
Location: include/linux/vmstat.h:74
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffff8000102c1d10)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffff8000102ce6dc)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffff800010315a10)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffff8000103af164)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (c04ecf00)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (c04f8678)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (c05307f0)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (c058e6c4)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (c00000000037bbf0)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (c00000000038c6d8)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (c0000000003e7a40)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (c0000000004a98a4)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffe0001e303e)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffe0001ec9f6)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffe00021b042)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffe000272f4a)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff8122a5c3)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff81235b37)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff8127660b)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff812f602a)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff8121d6e3)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff81228ba1)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff81268553)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff812e6c4a)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff81228363)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff812338d7)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812743ab)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff812f3e3a)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
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
In mm/swap.c (ffffffff812376a3)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/swap.c:pagevec_move_tail
```
```
In mm/vmscan.c (ffffffff81242e0e)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff81284477)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_pages_ok
```
```
In fs/inode.c (ffffffff813051eb)
Location: include/linux/vmstat.h:65
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
```
</details>
</li>
</ul>

## Differences
