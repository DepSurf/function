# Function: <code>memalloc_noreclaim_restore</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c2ee7)
Location: include/linux/sched/mm.h:201
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811d53d3)
Location: include/linux/sched/mm.h:201
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff817b330f)
Location: include/linux/sched/mm.h:201
Inline: True
```
```
In net/core/dev.c (ffffffff817cf1ab)
Location: include/linux/sched/mm.h:201
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
In mm/page_alloc.c (ffffffff811d7d14)
Location: include/linux/sched/mm.h:210
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811ea903)
Location: include/linux/sched/mm.h:210
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff8182b6d5)
Location: include/linux/sched/mm.h:210
Inline: True
```
```
In net/core/dev.c (ffffffff81848aeb)
Location: include/linux/sched/mm.h:210
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
In mm/page_alloc.c (ffffffff811f8f21)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff8120c05e)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff81875c0f)
Location: include/linux/sched/mm.h:246
Inline: True
```
```
In net/core/dev.c (ffffffff81892b4b)
Location: include/linux/sched/mm.h:246
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
In mm/page_alloc.c (ffffffff8120b4b6)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff8121ed68)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff818963ff)
Location: include/linux/sched/mm.h:246
Inline: True
```
```
In net/core/dev.c (ffffffff818b8047)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
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
In mm/vmscan.c (ffffffff8122e434)
Location: include/linux/sched/mm.h:279
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81271727)
Location: include/linux/sched/mm.h:279
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff818e073f)
Location: include/linux/sched/mm.h:279
Inline: True
```
```
In net/core/dev.c (ffffffff819042b2)
Location: include/linux/sched/mm.h:279
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
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
In mm/vmscan.c (ffffffff8123c5c4)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812805ae)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8191297f)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff81935401)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff81269534)
Location: include/linux/sched/mm.h:283
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812b24ed)
Location: include/linux/sched/mm.h:283
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff819e4daf)
Location: include/linux/sched/mm.h:283
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81a09ff6)
Location: include/linux/sched/mm.h:283
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list
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
In mm/vmscan.c (ffffffff81274065)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812bdfcd)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff819e462f)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81a0b596)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list
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
In mm/vmscan.c (ffffffff81278ea8)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812c32ef)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff819ca54f)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff819f1bce)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff812b6cb4)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff8130701f)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81a79aef)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81aa34ee)
Location: include/linux/sched/mm.h:273
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff81312bc0)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff8136f145)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81bebdf0)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81c1bc03)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff8138600e)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff813eb6b5)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81d9ab90)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81dccbd3)
Location: include/linux/sched/mm.h:346
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff813b92db)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff814206d5)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81e09310)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81e3d733)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff813e22e0)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff8144d495)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81ec5d00)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81efbfd3)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffff8000102cd7d0)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffff800010318394)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffff800010baa240)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffff800010bd3734)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (c04f77a4)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (c0532b2c)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (c0cc8d9c)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (c0cee3e4)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (c00000000038b218)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (c0000000003eaaec)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (c000000000c7ddf0)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (c000000000cb22f0)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffe0001ebce2)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffe00021e2a4)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffe00073dada)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffffffe00075d846)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff81234c14)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81278bfe)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff818b297f)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff818d53d5)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff81227c84)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff8126aaee)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8186c8cf)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff8188f245)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff812329b4)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff8127699e)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8190397f)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff81926401)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/vmscan.c (ffffffff81241e6f)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81286559)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8192497f)
Location: include/linux/sched/mm.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff819479a6)
Location: include/linux/sched/mm.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
</details>
</li>
</ul>

## Differences
