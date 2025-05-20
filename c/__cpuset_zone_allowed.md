# Function: <code>__cpuset_zone_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a5a4c)
Location: include/linux/cpuset.h:60
Inline: True
```
```
In mm/page_alloc.c (ffffffff811a9a8b)
Location: include/linux/cpuset.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811b91a2)
Location: include/linux/cpuset.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff811fae27)
Location: include/linux/cpuset.h:60
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff8120a0c6)
Location: include/linux/cpuset.h:60
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
In mm/oom_kill.c (ffffffff811b5e05)
Location: include/linux/cpuset.h:60
Inline: True
```
```
In mm/page_alloc.c (ffffffff811b9ff1)
Location: include/linux/cpuset.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811c97e2)
Location: include/linux/cpuset.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8120b927)
Location: include/linux/cpuset.h:60
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff8121c136)
Location: include/linux/cpuset.h:60
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
In mm/oom_kill.c (ffffffff811bdbf3)
Location: include/linux/cpuset.h:79
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c1f51)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811d2248)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff812145b2)
Location: include/linux/cpuset.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81227baf)
Location: include/linux/cpuset.h:79
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
In mm/oom_kill.c (ffffffff811d2877)
Location: include/linux/cpuset.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d64d3)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811e76e8)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff8122f12a)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81243cec)
Location: include/linux/cpuset.h:74
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
In mm/oom_kill.c (ffffffff811f36c6)
Location: include/linux/cpuset.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f78cd)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff81208c80)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff812518bc)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812664a1)
Location: include/linux/cpuset.h:74
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
In mm/oom_kill.c (ffffffff81205688)
Location: include/linux/cpuset.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120a184)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff8121b91b)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff81265cbc)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8127b1dc)
Location: include/linux/cpuset.h:74
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
In mm/oom_kill.c (ffffffff8121c6aa)
Location: include/linux/cpuset.h:74
Inline: True
```
```
In mm/vmscan.c (ffffffff8122b5b0)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff81270ea2)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81281226)
Location: include/linux/cpuset.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81296bc9)
Location: include/linux/cpuset.h:74
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
In mm/oom_kill.c (ffffffff8122a07a)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (ffffffff81239480)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff8127fce5)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81290eb6)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812a6993)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff812557ae)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8126aa0d)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_zones
```
```
In mm/page_alloc.c (ffffffff812b236b)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812c3760)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812db098)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff8126042e)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81275465)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_zones
```
```
In mm/page_alloc.c (ffffffff812bdd87)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812cf6a3)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812e7982)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff8126511e)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8127a785)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff812c4818)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812d68b7)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ef0f2)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff812a194b)
Location: include/linux/cpuset.h:77
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff812b87e5)
Location: include/linux/cpuset.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff813086ac)
Location: include/linux/cpuset.h:77
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8131c685)
Location: include/linux/cpuset.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813373fc)
Location: include/linux/cpuset.h:77
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
In mm/oom_kill.c (ffffffff812f9821)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff81314230)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/page_alloc.c (ffffffff81370a46)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8138783d)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813a8d13)
Location: include/linux/cpuset.h:92
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
In mm/oom_kill.c (ffffffff813633f7)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813882f0)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/page_alloc.c (ffffffff813ecec9)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81405c5f)
Location: include/linux/cpuset.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81429de4)
Location: include/linux/cpuset.h:92
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
In mm/oom_kill.c (ffffffff81395847)
Location: include/linux/cpuset.h:87
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813ba5d0)
Location: include/linux/cpuset.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/page_alloc.c (ffffffff81421e0f)
Location: include/linux/cpuset.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8143919c)
Location: include/linux/cpuset.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/slub.c (ffffffff8145f1d7)
Location: include/linux/cpuset.h:87
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
In mm/oom_kill.c (ffffffff813bf607)
Location: include/linux/cpuset.h:88
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff813e36f0)
Location: include/linux/cpuset.h:88
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
```
```
In mm/page_alloc.c (ffffffff8144ec41)
Location: include/linux/cpuset.h:88
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/slub.c (ffffffff8145a344)
Location: include/linux/cpuset.h:88
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472ccc)
Location: include/linux/cpuset.h:88
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
In mm/oom_kill.c (ffff8000102b7ee4)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (ffff8000102ca344)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffff800010317a28)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffff80001032d994)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffff800010347c48)
Location: include/linux/cpuset.h:76
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
In mm/vmscan.c (c04f4230)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (c0531e48)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/oom_kill.c (c00000000036fee0)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (c000000000386ce0)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (c0000000003e9f64)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (c000000000406080)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (c000000000425fc0)
Location: include/linux/cpuset.h:76
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
In mm/vmscan.c (ffffffe0001e94ce)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffe00021d8f0)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffe00022c138)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff812226ca)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (ffffffff81231ad0)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff81278335)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81289496)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129ef73)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff8121587a)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (ffffffff81224b90)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff8126a225)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8127b336)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81290ab3)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff8122046a)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (ffffffff8122f870)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff812760d5)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812872a6)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129cd83)
Location: include/linux/cpuset.h:76
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
In mm/oom_kill.c (ffffffff8122f594)
Location: include/linux/cpuset.h:76
Inline: True
```
```
In mm/vmscan.c (ffffffff8123eca0)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff81285cb5)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81297a26)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812acdea)
Location: include/linux/cpuset.h:76
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
