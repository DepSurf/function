# Function: <code>cpuset_node_allowed</code>

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
In mm/oom_kill.c (ffffffff81191103)
Location: include/linux/cpuset.h:53
Inline: True
```
```
In mm/page_alloc.c (ffffffff81196007)
Location: include/linux/cpuset.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811a2a33)
Location: include/linux/cpuset.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff811dca48)
Location: include/linux/cpuset.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff811eaaf3)
Location: include/linux/cpuset.h:53
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81234c70)
Location: kernel/cgroup/cpuset.c:4067
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff81234c70-ffffffff81234d75: cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8124e890)
Location: kernel/cgroup/cpuset.c:4908
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/slub.c:get_any_partial
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
**Symbols:**

```
ffffffff8124e890-ffffffff8124e995: cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
