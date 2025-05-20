# Function: <code>page_counter_try_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff811f9340)
Location: mm/page_counter.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff811f9340-ffffffff811f93e0: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8121cec0)
Location: mm/page_counter.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff8121cec0-ffffffff8121cf60: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8122f4c0)
Location: mm/page_counter.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff8122f4c0-ffffffff8122f560: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8123ad00)
Location: mm/page_counter.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff8123ad00-ffffffff8123ada1: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8125a590)
Location: mm/page_counter.c:63
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff8125a590-ffffffff8125a631: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8127e3a0)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff8127e3a0-ffffffff8127e463: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81292a90)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff81292a90-ffffffff81292b53: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ad450)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812ad450-ffffffff812ad4fd: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812befa0)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812befa0-ffffffff812bf04d: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812f4280)
Location: mm/page_counter.c:94
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812f4280-ffffffff812f432f: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ffb70)
Location: mm/page_counter.c:94
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812ffb70-ffffffff812ffc1f: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81306830)
Location: mm/page_counter.c:98
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff81306830-ffffffff813068df: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81350680)
Location: mm/page_counter.c:98
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff81350680-ffffffff8135072f: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813c8970)
Location: mm/page_counter.c:98
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff813c8970-ffffffff813c8a32: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8144d060)
Location: mm/page_counter.c:97
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff8144d060-ffffffff8144d12b: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81482920)
Location: mm/page_counter.c:97
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff81482920-ffffffff814829eb: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814b1ca0)
Location: mm/page_counter.c:97
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff814b1ca0-ffffffff814b1d6b: page_counter_try_charge (STB_GLOBAL)
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
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffff800010360b70)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffff800010360b70-ffff800010360c8c: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c05532dc)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c05532dc-c05533b8: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c00000000044bd10)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
c00000000044bd10-c00000000044be60: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffe0002403c6)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffe0002403c6-ffffffe000240464: page_counter_try_charge (STB_GLOBAL)
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
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b7580)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812b7580-ffffffff812b762d: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812a8750)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812a8750-ffffffff812a87fd: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b5390)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812b5390-ffffffff812b543d: page_counter_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter *counter, long unsigned int nr_pages, struct page_counter **fail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812c58d0)
Location: mm/page_counter.c:99
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
**Symbols:**

```
ffffffff812c58d0-ffffffff812c597d: page_counter_try_charge (STB_GLOBAL)
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
