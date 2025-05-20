# Function: <code>current_is_kswapd</code>

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
In mm/vmscan.c (ffffffff811a2dc1)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
```
In mm/compaction.c (ffffffff811b75f7)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In fs/inode.c (ffffffff812281d6)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff811badc5)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff81250906)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff811cb455)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812639a6)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8144a92a)
Location: include/linux/swap.h:31
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
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
In mm/vmscan.c (ffffffff811d4603)
Location: include/linux/swap.h:32
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff81271371)
Location: include/linux/swap.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff81458bc6)
Location: include/linux/swap.h:32
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
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
In mm/vmscan.c (ffffffff811e9b53)
Location: include/linux/swap.h:33
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff81293c91)
Location: include/linux/swap.h:33
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff81484926)
Location: include/linux/swap.h:33
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
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
In mm/vmscan.c (ffffffff8120b455)
Location: include/linux/swap.h:33
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812b9fc0)
Location: include/linux/swap.h:33
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff814b9738)
Location: include/linux/swap.h:33
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
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
In mm/vmscan.c (ffffffff8121e14f)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812cefb7)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff814ccfd7)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff8122d6f0)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812ebee0)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff814fb83e)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff8123b9e3)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812fda37)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8151978e)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff81268c11)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff81336e91)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff81579fc6)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff812736cd)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff813427d1)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff81596ed6)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff812789f5)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff8134895f)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8159da7d)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff812b675c)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff813965e8)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff81606164)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff81311bf5)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_throttle
```
```
In fs/inode.c (ffffffff81417b17)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff816ba2e2)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff813851b3)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:set_mm_walk
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:demote_folio_list
  - mm/vmscan.c:reclaim_throttle
```
```
In fs/inode.c (ffffffff814a32b7)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8177a851)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff813b8278)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:set_mm_walk
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:demote_folio_list
  - mm/vmscan.c:reclaim_throttle
```
```
In fs/inode.c (ffffffff814d8407)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff817ba0ef)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff813e1465)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:should_abort_scan
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:set_mm_walk
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:demote_folio_list
  - mm/vmscan.c:reclaim_throttle
```
```
In fs/inode.c (ffffffff8150abe7)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff817fe85c)
Location: include/linux/swap.h:37
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffff8000102cca60)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffff8000103af160)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffff800010620cc0)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (c04f688c)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (c058e6a4)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (c07c8c68)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (c00000000038a27c)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (c0000000004a989c)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (c0000000007c1114)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffe0001eb478)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffe000272f46)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffe000453750)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff81234033)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812f6017)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff81511d6e)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff812270a3)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812e6c37)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8150208e)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff81231dd3)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff812f3e27)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8150ddfe)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
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
In mm/vmscan.c (ffffffff81241233)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In fs/inode.c (ffffffff813051d8)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In block/blk-wbt.c (ffffffff8152741e)
Location: include/linux/swap.h:35
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
```
</details>
</li>
</ul>

## Differences
