# Function: <code>memalloc_noreclaim_save</code>

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
In mm/page_alloc.c (ffffffff811c2dcd)
Location: include/linux/sched/mm.h:194
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811d536d)
Location: include/linux/sched/mm.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff817b32f5)
Location: include/linux/sched/mm.h:194
Inline: True
```
```
In net/core/dev.c (ffffffff817cf186)
Location: include/linux/sched/mm.h:194
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
In mm/page_alloc.c (ffffffff811d7cdb)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811ea89d)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff8182b6b5)
Location: include/linux/sched/mm.h:203
Inline: True
```
```
In net/core/dev.c (ffffffff81848ac6)
Location: include/linux/sched/mm.h:203
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
In mm/page_alloc.c (ffffffff811f8ed3)
Location: include/linux/sched/mm.h:239
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff8120bff5)
Location: include/linux/sched/mm.h:239
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff81875be5)
Location: include/linux/sched/mm.h:239
Inline: True
```
```
In net/core/dev.c (ffffffff81892b26)
Location: include/linux/sched/mm.h:239
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
In mm/page_alloc.c (ffffffff8120b461)
Location: include/linux/sched/mm.h:239
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff8121ed00)
Location: include/linux/sched/mm.h:239
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In net/core/sock.c (ffffffff818963d5)
Location: include/linux/sched/mm.h:239
Inline: True
```
```
In net/core/dev.c (ffffffff818b7fd2)
Location: include/linux/sched/mm.h:239
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff8122e3d6)
Location: include/linux/sched/mm.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812716eb)
Location: include/linux/sched/mm.h:272
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff818e070e)
Location: include/linux/sched/mm.h:272
Inline: True
```
```
In net/core/dev.c (ffffffff81904229)
Location: include/linux/sched/mm.h:272
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff8123c566)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81280572)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8191294e)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffffffff81935378)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff812694d9)
Location: include/linux/sched/mm.h:276
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812b24a5)
Location: include/linux/sched/mm.h:276
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff819e4d7e)
Location: include/linux/sched/mm.h:276
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81a09f71)
Location: include/linux/sched/mm.h:276
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff8127400a)
Location: include/linux/sched/mm.h:262
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812bdf85)
Location: include/linux/sched/mm.h:262
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff819e45fe)
Location: include/linux/sched/mm.h:262
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81a0b511)
Location: include/linux/sched/mm.h:262
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81278e4d)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812c32bb)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff819ca51e)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff819f1b55)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff812b6c38)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff81306feb)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81a79abe)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81aa3475)
Location: include/linux/sched/mm.h:266
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81312b43)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/page_alloc.c (ffffffff8136f101)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81bebdbe)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81c1bb7a)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81385f91)
Location: include/linux/sched/mm.h:339
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
In mm/page_alloc.c (ffffffff813eb671)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81d9ab5e)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81dccb4a)
Location: include/linux/sched/mm.h:339
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff813b925e)
Location: include/linux/sched/mm.h:371
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
In mm/page_alloc.c (ffffffff81420691)
Location: include/linux/sched/mm.h:371
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81e092de)
Location: include/linux/sched/mm.h:371
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81e3d6aa)
Location: include/linux/sched/mm.h:371
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff813e2263)
Location: include/linux/sched/mm.h:371
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
In mm/page_alloc.c (ffffffff8144d451)
Location: include/linux/sched/mm.h:371
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff81ec5cce)
Location: include/linux/sched/mm.h:371
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (ffffffff81efbf4a)
Location: include/linux/sched/mm.h:371
Inline: True
Inline callers:
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
In mm/vmscan.c (ffff8000102cd774)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffff800010318360)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffff800010baa21c)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffff800010bd3690)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (c04f7744)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (c0532ae4)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (c0cc8d70)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (c0cee3c4)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (c00000000038b1c4)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (c0000000003eaab8)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (c000000000c7ddcc)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/dev.c (c000000000cb227c)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffe0001ebcb6)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffe00021e278)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffe00073dab8)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffffffe00075d848)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81234bb6)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81278bc2)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff818b294e)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffffffff818d534c)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81227c26)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff8126aab2)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8186c89e)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffffffff8188f1bc)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81232956)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81276962)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8190394e)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffffffff81926378)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff81241e11)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff8128651d)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In net/core/sock.c (ffffffff8192494e)
Location: include/linux/sched/mm.h:274
Inline: True
```
```
In net/core/dev.c (ffffffff8194791d)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
</details>
</li>
</ul>

## Differences
