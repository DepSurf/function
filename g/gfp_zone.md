# Function: <code>gfp_zone</code>

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
In kernel/sched/fair.c (0)
Location: include/linux/gfp.h:367
Inline: True
```
```
In mm/oom_kill.c (ffffffff811910d7)
Location: include/linux/gfp.h:367
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/gfp.h:367
Inline: True
```
```
In mm/vmscan.c (ffffffff811a0e52)
Location: include/linux/gfp.h:367
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff811a908f)
Location: include/linux/gfp.h:367
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:367
Inline: True
```
```
In mm/slub.c (ffffffff811ea7bf)
Location: include/linux/gfp.h:367
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:367
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:367
Inline: True
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
In kernel/sched/fair.c (ffffffff810b516f)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff811a58c4)
Location: include/linux/gfp.h:377
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab05b)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811bbfe0)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff811c077c)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/mempolicy.c (ffffffff811ffd7a)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/slub.c (ffffffff81209dd0)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81212a3e)
Location: include/linux/gfp.h:377
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:377
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
In kernel/sched/fair.c (ffffffff810bb638)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff811b5d67)
Location: include/linux/gfp.h:370
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bb6db)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811cc6b0)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff811d0d68)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/mempolicy.c (ffffffff812118a5)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/slub.c (ffffffff8121be40)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81224d39)
Location: include/linux/gfp.h:370
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:370
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
In kernel/sched/fair.c (ffffffff810b5e5f)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff811bd8f8)
Location: include/linux/gfp.h:416
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c39ae)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811d531d)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff811d980c)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/hugetlb.c (ffffffff8121441e)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8121d1c6)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/slub.c (ffffffff812279a0)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81230421)
Location: include/linux/gfp.h:416
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:416
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
In kernel/sched/fair.c (ffffffff810be6ff)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff811d2538)
Location: include/linux/gfp.h:401
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d874b)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811ea84d)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff811ef4dc)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/hugetlb.c (ffffffff8122efde)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812383b6)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/slub.c (ffffffff81243af3)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8124e0ab)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
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
In kernel/sched/fair.c (ffffffff810c6850)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff811f3441)
Location: include/linux/gfp.h:401
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f995f)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff8120bfc8)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff812115a0)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/hugetlb.c (ffffffff8125254a)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8125b933)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/slub.c (ffffffff81266346)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81271be6)
Location: include/linux/gfp.h:401
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:401
Inline: True
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
In kernel/sched/fair.c (ffffffff810cedd0)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff81205444)
Location: include/linux/gfp.h:418
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120bf9e)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff8121eca9)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff8122357e)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/hugetlb.c (ffffffff812667aa)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812701e7)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff8127b081)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81286206)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:418
Inline: True
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
In kernel/sched/fair.c (ffffffff810d76a0)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff8121c3d5)
Location: include/linux/gfp.h:418
Inline: True
```
```
In mm/vmscan.c (ffffffff8122e386)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff812332ba)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff812721b3)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81281a7c)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8128b7f7)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff81296a1d)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812a06e2)
Location: include/linux/gfp.h:418
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:418
Inline: True
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
In kernel/sched/fair.c (ffffffff810e1cb0)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff81229da5)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffffffff8123c516)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff812414bb)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff81281013)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff8129148d)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8129b367)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff812a67d7)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812b1b33)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
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
In mm/oom_kill.c (ffffffff812556c5)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81269483)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_zones
```
```
In mm/shmem.c (ffffffff8126dd4f)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff812b418e)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff812c3631)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812ce76e)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff812daf75)
Location: include/linux/gfp.h:448
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:448
Inline: True
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
In mm/oom_kill.c (ffffffff81260345)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81273fbd)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_zones
```
```
In mm/shmem.c (ffffffff81279a4d)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff812bfc0e)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff812cf5af)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812da0ae)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff812e7865)
Location: include/linux/gfp.h:450
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:450
Inline: True
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
In mm/oom_kill.c (ffffffff81265048)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81278df8)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff8127eb9f)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff812c536a)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff812d678a)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812e190e)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff812eefd5)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:464
Inline: True
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
In mm/oom_kill.c (ffffffff812a1878)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff812b6bde)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff812bc729)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff813098ca)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff8131c51e)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8132934d)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff813372e5)
Location: include/linux/gfp.h:476
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:476
Inline: True
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
In mm/oom_kill.c (ffffffff812f9738)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81312ade)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/shmem.c (ffffffff813186da)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/page_alloc.c (ffffffff81372138)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81387699)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8139866e)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff813a8be5)
Location: include/linux/gfp.h:493
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:493
Inline: True
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
In mm/oom_kill.c (ffffffff8136421a)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81385f21)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/shmem.c (ffffffff8138c637)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/page_alloc.c (ffffffff813ef968)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff81405ac9)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8141848e)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff81429ce2)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:129
Inline: True
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
In mm/oom_kill.c (ffffffff813966ea)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813b91f1)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/shmem.c (ffffffff813bec60)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/page_alloc.c (ffffffff814234d3)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff81439003)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff8144b9de)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:vma_migratable
```
```
In mm/slub.c (ffffffff8145f0c2)
Location: include/linux/gfp.h:129
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:129
Inline: True
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
In mm/oom_kill.c (ffffffff813c0745)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813e21f1)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/shmem.c (ffffffff813e9c94)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/page_alloc.c (ffffffff81450403)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
```
```
In mm/slub.c (ffffffff8145a231)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472b33)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff814826bf)
Location: include/linux/gfp.h:130
Inline: True
Inline callers:
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:vma_migratable
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:130
Inline: True
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
In kernel/sched/fair.c (ffff800010142bd0)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffff8000102b7cf4)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffff8000102cd75c)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffff8000102d3828)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffff800010318ccc)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffff80001032e5ec)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffff80001033a204)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffff800010347ad4)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffff8000103522a0)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
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
In mm/oom_kill.c (0)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (c04f6ffc)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (c04fbb80)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (c05336b0)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In kernel/sched/fair.c (c000000000192988)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (c00000000036fb98)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (c00000000038b198)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (c000000000392a6c)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (c0000000003eb664)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (c000000000407620)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (c000000000414898)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (c000000000425e98)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (c000000000438a10)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
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
In mm/oom_kill.c (0)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffffffe0001eba34)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffe0001ef914)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffe00021ea48)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffe00022c5a2)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In kernel/sched/fair.c (ffffffff810dbe60)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff812223f5)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffffffff81234b66)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff81239b0b)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff81279663)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81289a6d)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81293947)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff8129edb7)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812aa113)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
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
In kernel/sched/fair.c (ffffffff810cae70)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff812155a5)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffffffff81227bd6)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff8122cb27)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff8126b553)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff8127b89d)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81285557)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff812908f7)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8129ba73)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
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
In kernel/sched/fair.c (ffffffff810d81e0)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff81220195)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffffffff81232906)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff812378ab)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff81277403)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff8128787d)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81291757)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff8129cbc7)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812a7f23)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
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
In kernel/sched/fair.c (ffffffff810e3c8f)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff8122f2b5)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/vmscan.c (ffffffff81241dc6)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/shmem.c (ffffffff81246dff)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/page_alloc.c (ffffffff81286ff3)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81297e1c)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812a1567)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/slub.c (ffffffff812acc2b)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812b8223)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/khugepaged.c (0)
Location: include/linux/gfp.h:441
Inline: True
```
</details>
</li>
</ul>

## Differences
