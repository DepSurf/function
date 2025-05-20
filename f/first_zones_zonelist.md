# Function: <code>first_zones_zonelist</code>

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
In mm/oom_kill.c (ffffffff811910e9)
Location: include/linux/mmzone.h:940
Inline: True
```
```
In mm/page_alloc.c (ffffffff81191ab6)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811a0e64)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811b8039)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/hugetlb.c (ffffffff811dca1a)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e1d35)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff811eaa8e)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff81242bfc)
Location: include/linux/mmzone.h:940
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
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
Location: include/linux/mmzone.h:1008
Inline: True
```
```
In mm/page_alloc.c (ffffffff811a65d0)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
```
```
In mm/vmscan.c (ffffffff811b8437)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811d20fd)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff811fac84)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff81201766)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8120a04c)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8126af6f)
Location: include/linux/mmzone.h:1008
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
Location: include/linux/mmzone.h:986
Inline: True
```
```
In mm/page_alloc.c (ffffffff811b6940)
Location: include/linux/mmzone.h:986
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff811c8a72)
Location: include/linux/mmzone.h:986
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811e2031)
Location: include/linux/mmzone.h:986
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8120b784)
Location: include/linux/mmzone.h:986
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff81213256)
Location: include/linux/mmzone.h:986
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8121c0bc)
Location: include/linux/mmzone.h:986
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8127e0ad)
Location: include/linux/mmzone.h:986
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
Location: include/linux/mmzone.h:1006
Inline: True
```
```
In mm/page_alloc.c (ffffffff811be800)
Location: include/linux/mmzone.h:1006
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff811d11f1)
Location: include/linux/mmzone.h:1006
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff811ebe33)
Location: include/linux/mmzone.h:1006
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8121449b)
Location: include/linux/mmzone.h:1006
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8121e574)
Location: include/linux/mmzone.h:1006
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81227b26)
Location: include/linux/mmzone.h:1006
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8128bc0d)
Location: include/linux/mmzone.h:1006
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
Location: include/linux/mmzone.h:1009
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d3570)
Location: include/linux/mmzone.h:1009
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff811e66c1)
Location: include/linux/mmzone.h:1009
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff812021a3)
Location: include/linux/mmzone.h:1009
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8123098b)
Location: include/linux/mmzone.h:1009
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812397a1)
Location: include/linux/mmzone.h:1009
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81243c63)
Location: include/linux/mmzone.h:1009
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff811f34b3)
Location: include/linux/mmzone.h:1008
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f4807)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff81207cb7)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81223563)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff8125255a)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8125cd57)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8126639b)
Location: include/linux/mmzone.h:1008
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff812054b6)
Location: include/linux/mmzone.h:1016
Inline: True
```
```
In mm/page_alloc.c (ffffffff81206c40)
Location: include/linux/mmzone.h:1016
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/vmscan.c (ffffffff8121a837)
Location: include/linux/mmzone.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff812365c3)
Location: include/linux/mmzone.h:1016
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/hugetlb.c (ffffffff812667ba)
Location: include/linux/mmzone.h:1016
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81271637)
Location: include/linux/mmzone.h:1016
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8127b0d6)
Location: include/linux/mmzone.h:1016
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff8121c464)
Location: include/linux/mmzone.h:1056
Inline: True
```
```
In mm/vmscan.c (ffffffff8122a062)
Location: include/linux/mmzone.h:1056
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81247ad6)
Location: include/linux/mmzone.h:1056
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8126cc77)
Location: include/linux/mmzone.h:1056
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81281a8c)
Location: include/linux/mmzone.h:1056
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8128cc52)
Location: include/linux/mmzone.h:1056
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81296b16)
Location: include/linux/mmzone.h:1056
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff81229e34)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (ffffffff81237ee2)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81255f36)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8127ba87)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8129149f)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8129c882)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812a68d9)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff8125574a)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81266f30)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_zones
```
```
In mm/compaction.c (ffffffff81284626)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812b419f)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff812c3631)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812d04ce)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812db00b)
Location: include/linux/mmzone.h:1046
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff812603ce)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81271980)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_zones
```
```
In mm/compaction.c (ffffffff8128e925)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812bfc1f)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff812cf5af)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812dbfee)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812e78fb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff812650be)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81276c70)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81293fb5)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812c537d)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff812d678a)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812e3864)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812ef06b)
Location: include/linux/mmzone.h:1148
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff812a18ee)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff812b45a0)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff812d4556)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff813098dd)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8131c51e)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8132aa1a)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8133737b)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
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
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff812f97ae)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8131057b)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81333501)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81372138)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81387699)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8139a41b)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff813a8c7b)
Location: include/linux/mmzone.h:1209
Inline: True
Inline callers:
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
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8136338e)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81383beb)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff813aa20d)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff813ef968)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81405ac9)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8141a43b)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff81429d54)
Location: include/linux/mmzone.h:1525
Inline: True
Inline callers:
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
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813957de)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813b569b)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff813dd4a1)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff814234da)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81439003)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff8144d9ec)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8145f137)
Location: include/linux/mmzone.h:1650
Inline: True
Inline callers:
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
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813bf59e)
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813de68b)
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81407401)
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8145040a)
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/slub.c (ffffffff8145a2a5)
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472b33)
Location: include/linux/mmzone.h:1660
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff8148763b)
Location: include/linux/mmzone.h:1660
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
In mm/oom_kill.c (ffff8000102b7d68)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (ffff8000102c8c4c)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffff8000102ed4e8)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffff800010313c30)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffff80001032e5ec)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffff80001033b81c)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffff800010347be4)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
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
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (c0511274)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (c052dcf8)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
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
In mm/oom_kill.c (c00000000036fc28)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (c000000000384e30)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (c0000000003b123c)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (c0000000003ec880)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:local_memory_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (c000000000407620)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (c0000000004165e8)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (c000000000425ee8)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffe0001e81b6)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffe000201b34)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffe00021a408)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffe00022c5be)
Location: include/linux/mmzone.h:1063
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
In mm/oom_kill.c (ffffffff81222484)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (ffffffff81230532)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff8124e586)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812740d7)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81289a7f)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81294e62)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8129eeb9)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff81215634)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (ffffffff812235f2)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff81241526)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81266047)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8127b8af)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81286a72)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812909f9)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff81220224)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (ffffffff8122e2d2)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff8124c326)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81271e77)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff8128788f)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81292c72)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff8129ccc9)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
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
In mm/oom_kill.c (ffffffff8122f344)
Location: include/linux/mmzone.h:1063
Inline: True
```
```
In mm/vmscan.c (ffffffff8123d6d2)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/compaction.c (ffffffff8125bc86)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812818d7)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/hugetlb.c (ffffffff81297e2c)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812a2a62)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff812acd30)
Location: include/linux/mmzone.h:1063
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
