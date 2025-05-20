# Function: <code>lruvec_page_state</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8123863b)
Location: include/linux/memcontrol.h:635
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b4e7c)
Location: include/linux/memcontrol.h:631
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c696c)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
In mm/swap.c (ffffffff8125fbfb)
Location: include/linux/memcontrol.h:644
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81269b83)
Location: include/linux/memcontrol.h:644
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff81286829)
Location: include/linux/memcontrol.h:644
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memcontrol.c (ffffffff812f7688)
Location: include/linux/memcontrol.h:644
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff8126a1bb)
Location: include/linux/memcontrol.h:931
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81274676)
Location: include/linux/memcontrol.h:931
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff81290bc4)
Location: include/linux/memcontrol.h:931
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memcontrol.c (ffffffff81301e6e)
Location: include/linux/memcontrol.h:931
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff8126f2d4)
Location: include/linux/memcontrol.h:976
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81279969)
Location: include/linux/memcontrol.h:976
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff8129610b)
Location: include/linux/memcontrol.h:976
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memcontrol.c (ffffffff81308201)
Location: include/linux/memcontrol.h:976
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff812ac454)
Location: include/linux/memcontrol.h:972
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff812b7839)
Location: include/linux/memcontrol.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff812d6812)
Location: include/linux/memcontrol.h:972
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memcontrol.c (ffffffff813539fa)
Location: include/linux/memcontrol.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff81306594)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813126ad)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff81336061)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memcontrol.c (ffffffff813cba3e)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff8137064d)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813859ca)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff813ad2b9)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memcontrol.c (ffffffff81450746)
Location: include/linux/memcontrol.h:989
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff813a27fd)
Location: include/linux/memcontrol.h:1005
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813b8e32)
Location: include/linux/memcontrol.h:1005
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff813e16a9)
Location: include/linux/memcontrol.h:1005
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
```
```
In mm/memcontrol.c (ffffffff814861a6)
Location: include/linux/memcontrol.h:1005
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff813cc47d)
Location: include/linux/memcontrol.h:1024
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813e1e32)
Location: include/linux/memcontrol.h:1024
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
```
```
In mm/workingset.c (ffffffff8140be76)
Location: include/linux/memcontrol.h:1024
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
```
```
In mm/memcontrol.c (ffffffff814b59c2)
Location: include/linux/memcontrol.h:1024
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103696e8)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000457f7c)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bef4c)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b003c)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bcd5c)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd54c)
Location: include/linux/memcontrol.h:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
</ul>

## Differences
