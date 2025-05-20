# Function: <code>__count_vm_event</code>

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
In mm/page_alloc.c (ffffffff81194bfd)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
```
In mm/swap.c (ffffffff8119ce70)
Location: include/linux/vmstat.h:34
Inline: True
```
```
In mm/mlock.c (ffffffff811c2f9e)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/hugetlb.c (ffffffff811dadfa)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/balloon_compaction.c (ffffffff81207401)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c3845)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff811a8db3)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
```
In mm/swap.c (ffffffff811b23bd)
Location: include/linux/vmstat.h:34
Inline: True
```
```
In mm/mlock.c (ffffffff811dea21)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/hugetlb.c (ffffffff811f8f71)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/balloon_compaction.c (ffffffff8122cf9c)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513f12)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff811b9350)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
```
In mm/swap.c (ffffffff811c2a3b)
Location: include/linux/vmstat.h:34
Inline: True
```
```
In mm/mlock.c (ffffffff811ee841)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/hugetlb.c (ffffffff81209b61)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/balloon_compaction.c (ffffffff8123f4bc)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81540342)
Location: include/linux/vmstat.h:34
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff811c13d2)
Location: include/linux/vmstat.h:33
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
```
In mm/swap.c (ffffffff811cb1d2)
Location: include/linux/vmstat.h:33
Inline: True
```
```
In mm/mlock.c (ffffffff811f97d1)
Location: include/linux/vmstat.h:33
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/hugetlb.c (ffffffff81214396)
Location: include/linux/vmstat.h:33
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/balloon_compaction.c (ffffffff8124adc3)
Location: include/linux/vmstat.h:33
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81554191)
Location: include/linux/vmstat.h:33
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff811d4bd3)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/swap.c (ffffffff811e0112)
Location: include/linux/vmstat.h:44
Inline: True
```
```
In mm/mlock.c (ffffffff81211c01)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/hugetlb.c (ffffffff8122ef56)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/balloon_compaction.c (ffffffff8126b033)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7bd1)
Location: include/linux/vmstat.h:44
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff811f6025)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/swap.c (ffffffff81201a70)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff81232941)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/hugetlb.c (ffffffff81252628)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff8128f9fa)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f010b)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff812082f5)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/swap.c (ffffffff81213cd0)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff81246181)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/hugetlb.c (ffffffff81266888)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812a491a)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a6eb)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffff81223738)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff81258181)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff8126e6f5)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff81281cb5)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812bfcc2)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e43d)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffff812311d6)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff81266651)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff8127d535)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff812916ef)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812d1c12)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816609a7)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/mlock.c (ffffffff81296c2f)
Location: include/linux/vmstat.h:63
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/page_alloc.c (ffffffff812af3d8)
Location: include/linux/vmstat.h:63
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff812c4944)
Location: include/linux/vmstat.h:63
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff81307b41)
Location: include/linux/vmstat.h:63
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710688)
Location: include/linux/vmstat.h:63
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff812bb028)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff812d05e4)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff81313871)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d268)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff812c02bb)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff812d6e2d)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/balloon_compaction.c (ffffffff81319a01)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710fd5)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff81302fd2)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/hugetlb.c (ffffffff8131ccfd)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/balloon_compaction.c (ffffffff813661f1)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178daef)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/page_alloc.c (ffffffff81369cf1)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff813887fb)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/balloon_compaction.c (ffffffff813e31d2)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c62a9)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/hugetlb.c (ffffffff81408264)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/balloon_compaction.c (ffffffff8146ab51)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16bd8)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/hugetlb.c (ffffffff8143b173)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/balloon_compaction.c (ffffffff8149f9e1)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fc68)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/hugetlb.c (ffffffff81474f63)
Location: include/linux/vmstat.h:64
Inline: True
```
```
In mm/balloon_compaction.c (ffffffff814cf131)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2478)
Location: include/linux/vmstat.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffff8000102c2098)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffff8000102fd5d8)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/page_alloc.c (ffff800010314df8)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffff80001032f51c)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffff800010377a64)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b12c)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (c04ec4a8)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (c051cc5c)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/page_alloc.c (c052f3f8)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/balloon_compaction.c (c056342c)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (c09475ec)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (c00000000037a1c0)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (c0000000003c8c3c)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/page_alloc.c (c0000000003e6b04)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (c0000000004079d4)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (c00000000046a090)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d66e4)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffe0001e2764)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffe00020c0d8)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021b8d2)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffe00022c694)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffe00024f6b6)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fcf6)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffff81229826)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff8125eca1)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff81275b85)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff81289ccf)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812ca1f2)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626817)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffff8121c946)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff812510d1)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff81267ad5)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff8127baff)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812bb232)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ae97)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffff812275c6)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff8125ca41)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff81273925)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff81287adf)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812c8002)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816547e7)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/swap.c (ffffffff812368f6)
Location: include/linux/vmstat.h:55
Inline: True
```
```
In mm/mlock.c (ffffffff8126c421)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolation_failed
```
```
In mm/page_alloc.c (ffffffff81283425)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_commit
```
```
In mm/hugetlb.c (ffffffff81298077)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/balloon_compaction.c (ffffffff812d8d12)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f267)
Location: include/linux/vmstat.h:55
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
</details>
</li>
</ul>

## Differences
