# Function: <code>page_counter_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff811f93e0)
Location: mm/page_counter.c:116
Inline: False
Direct callers:
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - net/core/sock.c:__sk_mem_schedule
```
**Symbols:**

```
ffffffff811f93e0-ffffffff811f9411: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8121cf60)
Location: mm/page_counter.c:116
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff8121cf60-ffffffff8121cf91: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8122f560)
Location: mm/page_counter.c:116
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff8122f560-ffffffff8122f591: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8123adb0)
Location: mm/page_counter.c:116
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff8123adb0-ffffffff8123ade2: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8125a640)
Location: mm/page_counter.c:117
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff8125a640-ffffffff8125a672: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8127e470)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff8127e470-ffffffff8127e4a1: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81292b60)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff81292b60-ffffffff81292b91: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ad500)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff812ad500-ffffffff812ad531: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812bf050)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff812bf050-ffffffff812bf081: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812f4330)
Location: mm/page_counter.c:151
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:drain_stock
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff812f4330-ffffffff812f4387: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ffc20)
Location: mm/page_counter.c:151
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:obj_cgroup_release
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff812ffc20-ffffffff812ffc77: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813068e0)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:drain_stock
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff813068e0-ffffffff81306911: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81350730)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff81350730-ffffffff81350761: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813c8a40)
Location: mm/page_counter.c:154
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff813c8a40-ffffffff813c8a81: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8144d140)
Location: mm/page_counter.c:153
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff8144d140-ffffffff8144d184: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81482a00)
Location: mm/page_counter.c:153
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff81482a00-ffffffff81482a44: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814b1d80)
Location: mm/page_counter.c:153
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
```
**Symbols:**

```
ffffffff814b1d80-ffffffff814b1dc4: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffff800010360c90)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffff800010360c90-ffff800010360cd0: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c05533b8)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:drain_stock
```
**Symbols:**

```
c05533b8-c05533f4: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c00000000044be60)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
c00000000044be60-c00000000044bec0: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffe000240464)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffe000240464-ffffffe00024049c: page_counter_uncharge (STB_GLOBAL)
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
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b7630)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff812b7630-ffffffff812b7661: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812a8800)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff812a8800-ffffffff812a8831: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b5440)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff812b5440-ffffffff812b5471: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812c5980)
Location: mm/page_counter.c:155
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
```
**Symbols:**

```
ffffffff812c5980-ffffffff812c59b1: page_counter_uncharge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
