# Function: <code>page_ref_count</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9dc1)
Location: include/linux/page_ref.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In mm/debug.c (ffffffff811d44c1)
Location: include/linux/page_ref.h:64
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In net/core/sock.c (ffffffff8176892c)
Location: include/linux/page_ref.h:64
Inline: True
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
In mm/page_alloc.c (ffffffff811ba320)
Location: include/linux/page_ref.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In mm/debug.c (ffffffff811e4516)
Location: include/linux/page_ref.h:64
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In net/core/sock.c (ffffffff8179583c)
Location: include/linux/page_ref.h:64
Inline: True
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
In mm/page_alloc.c (ffffffff811c22b6)
Location: include/linux/page_ref.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In mm/debug.c (ffffffff811ee972)
Location: include/linux/page_ref.h:64
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In net/core/sock.c (ffffffff817b350a)
Location: include/linux/page_ref.h:64
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff811691f1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/page_alloc.c (ffffffff811d6b12)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In mm/debug.c (ffffffff81204de2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In net/core/sock.c (ffffffff8182b8ca)
Location: include/linux/page_ref.h:65
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff8117b391)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/page_alloc.c (ffffffff811fa32e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In mm/debug.c (ffffffff81225d25)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In fs/dax.c (ffffffff812f5d1d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff818771ea)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff818bdac5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
  - net/core/page_pool.c:__page_pool_empty_ring
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
In kernel/trace/ring_buffer.c (ffffffff811856d1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/page_alloc.c (ffffffff8120ca8a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In mm/debug.c (ffffffff812393e9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In fs/dax.c (ffffffff8130e75e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff8189671a)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff818e4ea5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
  - net/core/page_pool.c:__page_pool_empty_ring
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
In kernel/trace/ring_buffer.c (ffffffff81192a11)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff8124a449)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8124aedf)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffffffff81272e64)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffff812d542b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff81334e8d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff818e0ada)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff819347d8)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_request_shutdown
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
In kernel/trace/ring_buffer.c (ffffffff8119e691)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff81258870)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812593cf)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffffffff81281cc9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffff812e6f9b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff81348a6d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff81912caa)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81967587)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (ffffffff811b5c01)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff81287202)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8128766e)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b40a3)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:check_free_page_bad
```
```
In fs/pipe.c (ffffffff8131e80b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff8138dd97)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff819e483c)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81a3a9d2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
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
In kernel/trace/ring_buffer.c (ffffffff811b34e1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/vmscan.c (ffffffff81271155)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81be7474)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812914ae)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In mm/memory.c (ffffffff81299ecf)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/page_alloc.c (ffffffff812bfb2e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:check_free_page_bad
```
```
In mm/huge_memory.c (ffffffff812f7ec2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/pipe.c (ffffffff81329d6b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff8139f08a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c7feb)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In net/core/sock.c (ffffffff819e408a)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81a3cef2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In kernel/trace/ring_buffer.c (ffffffff811b56e4)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/vmscan.c (ffffffff81275cb2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff812968bd)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8129753d)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In mm/memory.c (ffffffff8129ec40)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/page_alloc.c (ffffffff812c528e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:check_free_page_bad
```
```
In mm/hugetlb.c (ffffffff812dcec2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812fe48f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/pipe.c (ffffffff8132fd2b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff813a684a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff813cf01b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In net/core/sock.c (ffffffff819ca11a)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81a23d40)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In kernel/trace/ring_buffer.c (ffffffff811df804)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/vmscan.c (ffffffff812b39a6)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff812d70fa)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812d7ef1)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In mm/memory.c (ffffffff812dfe8b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/page_alloc.c (ffffffff813097db)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:check_free_page_bad
```
```
In mm/hugetlb.c (ffffffff813240a6)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81348037)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/pipe.c (ffffffff8137d4eb)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff813f62ec)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff81420502)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In net/core/sock.c (ffffffff81a7968a)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81ad83eb)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In kernel/trace/ring_buffer.c (ffffffff812135e4)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/filemap.c (ffffffff81e6b4a1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff81307eff)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8130e94a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff8133115b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81336acb)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81338425)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_get_folio
```
```
In mm/memory.c (ffffffff81344203)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81353fc3)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135e7b1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8137293b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:check_free_page_bad
```
```
In mm/memory_hotplug.c (ffffffff81f1bd23)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8138ee45)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff813a06fe)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b3957)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff813b68f0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c3f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c5f5e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff813da519)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff813deb3a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff813e9682)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff813fe2b7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8146372c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff8146864a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff8149a907)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff814b1589)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff818c7ec7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81be78ed)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/sock.c (ffffffff81bed21c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
```
```
In net/core/page_pool.c (ffffffff81c591f2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
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
In kernel/trace/ring_buffer.c (ffffffff8125cda9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/filemap.c (ffffffff81359a43)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff813712ec)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813808ae)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff813a7e17)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff813adc26)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813afc1a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813bbfd0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff813ce407)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813d99d3)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff813f00ab)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_page_is_bad_report
```
```
In mm/memory_hotplug.c (ffffffff820c3b05)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8140d92e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81417bcb)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8141fee5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff814347c5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8143826a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443de4)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144aaac)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81461c8f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff814657fa)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff81471654)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff81487f17)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff814f281c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff814f90da)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152ee27)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81547f1b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff81a19487)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81d940fd)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/sock.c (ffffffff81d994dc)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
```
```
In net/core/page_pool.c (ffffffff81e0f162)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
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
In kernel/trace/ring_buffer.c (ffffffff81273d99)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/filemap.c (ffffffff8138b390)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff813a34bc)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813b1955)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff813db203)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff813e1fb7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e7e23)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f0a01)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81402cb5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140dea9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81423c28)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_page_is_bad_report
```
```
In mm/memory_hotplug.c (ffffffff82147a8a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff81440ce1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff8144b163)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81454afc)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81469fd5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8146df3a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147932c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81480ba2)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81497422)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff8149b1f3)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff814a5b95)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff814bcdf7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8152943f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff815306aa)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff81567137)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8157fb1d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff815b04ea)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
```
In drivers/xen/grant-table.c (ffffffff81a623a7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/core/sock.c (ffffffff81e077fc)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
```
```
In net/core/skbuff.c (ffffffff81e14c20)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
```
```
In net/core/page_pool.c (ffffffff81e82922)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
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
In kernel/trace/ring_buffer.c (ffffffff8128e3ac)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/filemap.c (ffffffff813b4eb7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff813ce72c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813daec1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff814052be)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff8140c7ca)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81412a90)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81420273)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff8142f41d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8143a55b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450b65)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_page_is_bad_report
```
```
In mm/memory_hotplug.c (ffffffff8222a13e)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8147ae11)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81484b15)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff8148fce8)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81498fa5)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8149e901)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8892)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814aeb7f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff814c671d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:has_extra_refcount
```
```
In mm/page_isolation.c (ffffffff814ca8d3)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/userfaultfd.c (ffffffff814cff0f)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In mm/memfd.c (ffffffff814d6b42)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff814ef2a7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8155e313)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff8156558a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/proc/task_mmu.c (ffffffff8159ccc7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b852d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff815e92d7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
```
In drivers/xen/grant-table.c (ffffffff81ab4bd7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/core/sock.c (ffffffff81ec423c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
```
```
In net/core/skbuff.c (ffffffff81ed2219)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
```
```
In net/core/page_pool.c (ffffffff81f44ab3)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
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
In kernel/trace/ring_buffer.c (ffff800010217f60)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffff8000102f07c4)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffff8000102f1180)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffff80001031a418)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffff80001038fd34)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffff800010408ec0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffff800010bac694)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffff800010c0cb48)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (c0458618)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (c0513d30)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0514a6c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (c05349c8)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (c05766b0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In net/core/sock.c (c0cc8f24)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (c0d25258)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (c00000000029e664)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (c0000000003b513c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0000000003b7820)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (c0000000003ed620)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (c0000000004872f8)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (c0000000005151d4)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (c000000000c82708)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (c000000000cf8470)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (ffffffe000176f26)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffe000203fd0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffe000204892)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021fc10)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffe00025f57a)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffe0002b328c)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffe00073ddb2)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffe000789cba)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (ffffffff81196cb1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff81250ec0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81251a1f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffffffff8127a319)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffff812df57b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff8134104d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff818b2caa)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81907557)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (ffffffff81189fa1)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff81243e00)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812448c9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffffffff8126c209)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffff812d01bb)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff81331a2d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff8186cbfa)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff818c1367)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (ffffffff81194a81)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff8124ec60)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8124f7bf)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffffffff812780b9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffff812dd38b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff8133eb1d)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff81903caa)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff81958587)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
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
In kernel/trace/ring_buffer.c (ffffffff811a2691)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In mm/debug.c (ffffffff8125e5e0)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125f12f)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/page_alloc.c (ffffffff81287ca9)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pages_check_bad
```
```
In fs/pipe.c (ffffffff812ee31b)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dax.c (ffffffff813519ed)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
```
```
In net/core/sock.c (ffffffff81924caa)
Location: include/linux/page_ref.h:65
Inline: True
```
```
In net/core/page_pool.c (ffffffff8197a6b7)
Location: include/linux/page_ref.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
</ul>

## Differences
