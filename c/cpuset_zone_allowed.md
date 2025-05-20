# Function: <code>cpuset_zone_allowed</code>

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
Location: include/linux/cpuset.h:58
Inline: True
```
```
In mm/page_alloc.c (ffffffff81196007)
Location: include/linux/cpuset.h:58
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811a2a33)
Location: include/linux/cpuset.h:58
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff811dca48)
Location: include/linux/cpuset.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff811eaaf3)
Location: include/linux/cpuset.h:58
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff811a5929)
Location: include/linux/cpuset.h:65
Inline: True
```
```
In mm/vmscan.c (ffffffff811b90f3)
Location: include/linux/cpuset.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff811facd6)
Location: include/linux/cpuset.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff8120a091)
Location: include/linux/cpuset.h:65
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff811b5ddf)
Location: include/linux/cpuset.h:65
Inline: True
```
```
In mm/vmscan.c (ffffffff811c9733)
Location: include/linux/cpuset.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8120b7d6)
Location: include/linux/cpuset.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff8121c101)
Location: include/linux/cpuset.h:65
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff811bd963)
Location: include/linux/cpuset.h:84
Inline: True
```
```
In mm/vmscan.c (ffffffff811d21e2)
Location: include/linux/cpuset.h:84
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff812144ce)
Location: include/linux/cpuset.h:84
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81227b74)
Location: include/linux/cpuset.h:84
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/oom_kill.c (ffffffff811d25a3)
Location: include/linux/cpuset.h:79
Inline: True
```
```
In mm/vmscan.c (ffffffff811e7682)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8122f06a)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81243cb1)
Location: include/linux/cpuset.h:79
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
In mm/oom_kill.c (ffffffff811f34de)
Location: include/linux/cpuset.h:79
Inline: True
```
```
In mm/vmscan.c (ffffffff81208bf9)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff81251823)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812663d2)
Location: include/linux/cpuset.h:79
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
In mm/oom_kill.c (ffffffff812054de)
Location: include/linux/cpuset.h:79
Inline: True
```
```
In mm/vmscan.c (ffffffff8121b898)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff81265c23)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8127b10d)
Location: include/linux/cpuset.h:79
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
In mm/oom_kill.c (ffffffff8121c494)
Location: include/linux/cpuset.h:79
Inline: True
```
```
In mm/vmscan.c (ffffffff8122b524)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8128112a)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81296b5a)
Location: include/linux/cpuset.h:79
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
In mm/oom_kill.c (ffffffff81229e64)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (ffffffff812393f4)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff81290dba)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812a6920)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff81255776)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8126a994)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_zones
```
```
In mm/hugetlb.c (ffffffff812c3662)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812db039)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff812603f6)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff812753f4)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_zones
```
```
In mm/hugetlb.c (ffffffff812cf656)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812e7928)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff812650e6)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8127a714)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff812d6838)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ef098)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff812a1916)
Location: include/linux/cpuset.h:82
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff812b8777)
Location: include/linux/cpuset.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8131c5d7)
Location: include/linux/cpuset.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813373a8)
Location: include/linux/cpuset.h:82
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
In mm/oom_kill.c (ffffffff812f97d6)
Location: include/linux/cpuset.h:97
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813141ac)
Location: include/linux/cpuset.h:97
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/hugetlb.c (ffffffff81387769)
Location: include/linux/cpuset.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813a8ca9)
Location: include/linux/cpuset.h:97
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
In mm/oom_kill.c (ffffffff813633b6)
Location: include/linux/cpuset.h:97
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8138826c)
Location: include/linux/cpuset.h:97
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/hugetlb.c (ffffffff81405b95)
Location: include/linux/cpuset.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81429d95)
Location: include/linux/cpuset.h:97
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
In mm/oom_kill.c (ffffffff81395806)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813ba54c)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/hugetlb.c (ffffffff814390d2)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/slub.c (ffffffff8145f185)
Location: include/linux/cpuset.h:92
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
In mm/oom_kill.c (ffffffff813bf5c6)
Location: include/linux/cpuset.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813e366c)
Location: include/linux/cpuset.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/slub.c (ffffffff8145a2f2)
Location: include/linux/cpuset.h:93
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472c02)
Location: include/linux/cpuset.h:93
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
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
In mm/oom_kill.c (ffff8000102b7d88)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (ffff8000102ca2d0)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffff80001032d8a0)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffff800010347c08)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f4120)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/oom_kill.c (c00000000036fc60)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (c000000000386c40)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (c000000000405eec)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (c000000000425f0c)
Location: include/linux/cpuset.h:81
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
In mm/vmscan.c (ffffffe0001e93e8)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffe00022c0b6)
Location: include/linux/cpuset.h:81
Inline: True
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
In mm/oom_kill.c (ffffffff812224b4)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (ffffffff81231a44)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8128939a)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129ef00)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff81215664)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (ffffffff81224b04)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8127b23a)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81290a40)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff81220254)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (ffffffff8122f7e4)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff812871aa)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129cd10)
Location: include/linux/cpuset.h:81
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
In mm/oom_kill.c (ffffffff8122f374)
Location: include/linux/cpuset.h:81
Inline: True
```
```
In mm/vmscan.c (ffffffff8123ec14)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8129792a)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812acd77)
Location: include/linux/cpuset.h:81
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
