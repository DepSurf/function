# Function: <code>__cpuset_node_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111d710)
Location: kernel/cpuset.c:2527
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8111d710-ffffffff8111d7e7: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff811255b0)
Location: kernel/cpuset.c:2548
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811255b0-ffffffff811256a6: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112efa0)
Location: kernel/cpuset.c:2548
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8112efa0-ffffffff8112f08a: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81130630)
Location: kernel/cgroup/cpuset.c:2548
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81130630-ffffffff8113070e: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113d560)
Location: kernel/cgroup/cpuset.c:2552
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8113d560-ffffffff8113d63e: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8114be80)
Location: kernel/cgroup/cpuset.c:2553
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8114be80-ffffffff8114bf70: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81158ad0)
Location: kernel/cgroup/cpuset.c:3361
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81158ad0-ffffffff81158bc0: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811651c0)
Location: kernel/cgroup/cpuset.c:3329
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811651c0-ffffffff81165298: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811710a0)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811710a0-ffffffff81171182: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81182db0)
Location: kernel/cgroup/cpuset.c:3419
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_zones
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff81182db0-ffffffff81182e9a: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117fd10)
Location: kernel/cgroup/cpuset.c:3442
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_zones
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff8117fd10-ffffffff8117fe08: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811807f0)
Location: kernel/cgroup/cpuset.c:3442
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff811807f0-ffffffff811808e8: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a85e0)
Location: kernel/cgroup/cpuset.c:3524
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff811a85e0-ffffffff811a86d8: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d9760)
Location: kernel/cgroup/cpuset.c:3570
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff811d9760-ffffffff811d9865: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121eb80)
Location: kernel/cgroup/cpuset.c:3875
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:wakeup_kswapd
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff8121eb80-ffffffff8121ec85: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e4660)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffff8000101e4660-ffff8000101e47d4: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c042552c)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
c042552c-c0425638: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000254df0)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
c000000000254df0-c000000000254f3c: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe00015a90e)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffe00015a90e-ffffffe00015a9fc: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811696c0)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811696c0-ffffffff811697a2: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8115c8c0)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8115c8c0-ffffffff8115c9a2: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81167490)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81167490-ffffffff81167572: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81174b00)
Location: kernel/cgroup/cpuset.c:3417
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81174b00-ffffffff81174bf5: __cpuset_node_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
