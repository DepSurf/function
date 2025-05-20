# Function: <code>next_zones_zonelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct zoneref *next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811ac3b0)
Location: mm/mmzone.c:55
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mpol_misplaced
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811ac3b0-ffffffff811ac3f2: next_zones_zonelist (STB_GLOBAL)
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
In mm/oom_kill.c (ffffffff811a58f6)
Location: include/linux/mmzone.h:987
Inline: True
```
```
In mm/page_alloc.c (ffffffff811a65d0)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811b8437)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811d20fd)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff811fac84)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff81201766)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8120a04c)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8126af6f)
Location: include/linux/mmzone.h:987
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
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
In mm/oom_kill.c (ffffffff811b5da2)
Location: include/linux/mmzone.h:961
Inline: True
```
```
In mm/page_alloc.c (ffffffff811b6940)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff811c8a72)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811e2031)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8120b784)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff81213256)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8121c0bc)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8127e0ad)
Location: include/linux/mmzone.h:961
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
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
In mm/oom_kill.c (ffffffff811bd937)
Location: include/linux/mmzone.h:981
Inline: True
```
```
In mm/page_alloc.c (ffffffff811be800)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff811d11fe)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811ebe33)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8121449b)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8121e574)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81227b26)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8128bc0d)
Location: include/linux/mmzone.h:981
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
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
In mm/oom_kill.c (ffffffff811d2577)
Location: include/linux/mmzone.h:984
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d3570)
Location: include/linux/mmzone.h:984
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff811e66ce)
Location: include/linux/mmzone.h:984
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff812021a3)
Location: include/linux/mmzone.h:984
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8123098b)
Location: include/linux/mmzone.h:984
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812397a1)
Location: include/linux/mmzone.h:984
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81243c63)
Location: include/linux/mmzone.h:984
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff811f34ba)
Location: include/linux/mmzone.h:983
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f4817)
Location: include/linux/mmzone.h:983
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff81207cb7)
Location: include/linux/mmzone.h:983
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81223563)
Location: include/linux/mmzone.h:983
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8125255a)
Location: include/linux/mmzone.h:983
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8125cd5e)
Location: include/linux/mmzone.h:983
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8126639e)
Location: include/linux/mmzone.h:983
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff812054bd)
Location: include/linux/mmzone.h:991
Inline: True
```
```
In mm/page_alloc.c (ffffffff81206c47)
Location: include/linux/mmzone.h:991
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff8121a837)
Location: include/linux/mmzone.h:991
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff812365c3)
Location: include/linux/mmzone.h:991
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff812667ba)
Location: include/linux/mmzone.h:991
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8127163e)
Location: include/linux/mmzone.h:991
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8127b0d9)
Location: include/linux/mmzone.h:991
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff8121c46c)
Location: include/linux/mmzone.h:1031
Inline: True
```
```
In mm/vmscan.c (ffffffff8122a062)
Location: include/linux/mmzone.h:1031
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81247ad6)
Location: include/linux/mmzone.h:1031
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8126cc86)
Location: include/linux/mmzone.h:1031
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81281a8c)
Location: include/linux/mmzone.h:1031
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8128cc59)
Location: include/linux/mmzone.h:1031
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81296b16)
Location: include/linux/mmzone.h:1031
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff81229e3c)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (ffffffff81237ee2)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81255f36)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8127ba96)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8129149f)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8129c889)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812a68d9)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff81255751)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81266f30)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_zones
```
```
In mm/compaction.c (ffffffff81284626)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812b419f)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff812c3631)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812d04d5)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812db00e)
Location: include/linux/mmzone.h:1021
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In mm/oom_kill.c (ffffffff812603d1)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81271980)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_zones
```
```
In mm/compaction.c (ffffffff8128e925)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812bfc1f)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff812cf5af)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812dbff5)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812e78fe)
Location: include/linux/mmzone.h:1059
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In mm/oom_kill.c (ffffffff812650c1)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81276c70)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81293fb5)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812c537d)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff812d678a)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812e386b)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812ef06e)
Location: include/linux/mmzone.h:1122
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In mm/oom_kill.c (ffffffff812a18f1)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff812b45a0)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff812d4556)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff813098dd)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8131c51e)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8132aa21)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8133737e)
Location: include/linux/mmzone.h:1162
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In kernel/cgroup/cpuset.c (ffffffff811d892b)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff812f97b1)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8131057b)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81333501)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81372138)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81387699)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8139a422)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff813a8c7e)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In kernel/cgroup/cpuset.c (ffffffff8121d8ae)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff81363391)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81383beb)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff813aa20d)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff813ef968)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81405ac9)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8141a442)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81429d54)
Location: include/linux/mmzone.h:1499
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In kernel/cgroup/cpuset.c (ffffffff81233967)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813957e1)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813b569b)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff813dd4a1)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff814234da)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81439006)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff8144d9f3)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8145f137)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
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
In kernel/cgroup/cpuset.c (ffffffff8124d762)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813bf5a1)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813de68b)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81407401)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8145040a)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/slub.c (ffffffff8145a2a5)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472b36)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff81487642)
Location: include/linux/mmzone.h:1634
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/oom_kill.c (ffff8000102b7d70)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (ffff8000102c8c4c)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffff8000102ed4f0)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffff800010313c38)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffff80001032e5ec)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffff80001033b824)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffff800010347be4)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/vmscan.c (c04f7084)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (c0511454)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (c052dcf8)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
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
In mm/oom_kill.c (c00000000036fc34)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (c000000000384e30)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (c0000000003b124c)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (c0000000003ec888)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:local_memory_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (c000000000407624)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (c0000000004165ec)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (c000000000425ee8)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/vmscan.c (ffffffe0001e81b8)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffe000201b3a)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffe00021a408)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffe00022c5be)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/oom_kill.c (ffffffff8122248c)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (ffffffff81230532)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff8124e586)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812740e6)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81289a7f)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81294e69)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8129eeb9)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff8121563c)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (ffffffff812235f2)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81241526)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81266056)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8127b8af)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81286a79)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812909f9)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff8122022c)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (ffffffff8122e2d2)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff8124c326)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81271e86)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8128788f)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81292c79)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8129ccc9)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff8122f34c)
Location: include/linux/mmzone.h:1038
Inline: True
```
```
In mm/vmscan.c (ffffffff8123d6d2)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff8125bc86)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812818e6)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81297e2c)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812a2a69)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812acd30)
Location: include/linux/mmzone.h:1038
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
