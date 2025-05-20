# Function: <code>lruvec_page_state_local</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228d35)
Location: include/linux/memcontrol.h:649
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/workingset.c (ffffffff81249de0)
Location: include/linux/memcontrol.h:649
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812adc2b)
Location: include/linux/memcontrol.h:649
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffff81236bd5)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/workingset.c (ffffffff81258230)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812bf77b)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/workingset.c (ffffffff812866ed)
Location: include/linux/memcontrol.h:662
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812f76ce)
Location: include/linux/memcontrol.h:662
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
In mm/workingset.c (ffffffff81290a80)
Location: include/linux/memcontrol.h:949
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff81302cc4)
Location: include/linux/memcontrol.h:949
Inline: True
Inline callers:
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
In mm/workingset.c (ffffffff81295fcb)
Location: include/linux/memcontrol.h:994
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff81309249)
Location: include/linux/memcontrol.h:994
Inline: True
Inline callers:
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
In mm/workingset.c (ffffffff812d6683)
Location: include/linux/memcontrol.h:984
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff81352ca8)
Location: include/linux/memcontrol.h:984
Inline: True
Inline callers:
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
In mm/workingset.c (ffffffff81335ed3)
Location: include/linux/memcontrol.h:1007
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff813cd139)
Location: include/linux/memcontrol.h:1007
Inline: True
Inline callers:
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
In mm/workingset.c (ffffffff813ad10b)
Location: include/linux/memcontrol.h:1007
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff814518dc)
Location: include/linux/memcontrol.h:1007
Inline: True
Inline callers:
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
In mm/workingset.c (ffffffff813e14fb)
Location: include/linux/memcontrol.h:1023
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff81486e3c)
Location: include/linux/memcontrol.h:1023
Inline: True
Inline callers:
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
In mm/workingset.c (ffffffff8140bdce)
Location: include/linux/memcontrol.h:1042
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff814b559f)
Location: include/linux/memcontrol.h:1042
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffff8000102c644c)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
```
```
In mm/workingset.c (ffff8000102efe1c)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffff8000103614d4)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (c04f1dc8)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/workingset.c (c051371c)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
In mm/vmscan.c (c0000000003830c4)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
```
```
In mm/workingset.c (c0000000003b490c)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (c00000000044d0b0)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffe0001e73ca)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
```
```
In mm/workingset.c (ffffffe000203844)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
In mm/vmscan.c (ffffffff8122f225)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/workingset.c (ffffffff81250880)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812b7d5b)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffff812222e5)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/workingset.c (ffffffff81243800)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812a8f2b)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffff8122cfc5)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/workingset.c (ffffffff8124e620)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812b5b6b)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffff8123c405)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/workingset.c (ffffffff8125df90)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/memcontrol.c (ffffffff812c608b)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
</details>
</li>
</ul>

## Differences
