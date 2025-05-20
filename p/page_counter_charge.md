# Function: <code>page_counter_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff811f9310)
Location: mm/page_counter.c:36
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff811f9310-ffffffff811f933e: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8121ce90)
Location: mm/page_counter.c:36
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff8121ce90-ffffffff8121cebe: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8122f490)
Location: mm/page_counter.c:36
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff8122f490-ffffffff8122f4be: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8123acd0)
Location: mm/page_counter.c:36
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff8123acd0-ffffffff8123acfe: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8125a560)
Location: mm/page_counter.c:37
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff8125a560-ffffffff8125a590: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8127e340)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff8127e340-ffffffff8127e397: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81292a30)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff81292a30-ffffffff81292a87: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ad3f0)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812ad3f0-ffffffff812ad447: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812bef40)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812bef40-ffffffff812bef97: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812f4230)
Location: mm/page_counter.c:67
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812f4230-ffffffff812f427f: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ffb20)
Location: mm/page_counter.c:67
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812ffb20-ffffffff812ffb6f: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813067e0)
Location: mm/page_counter.c:71
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff813067e0-ffffffff8130682f: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81350630)
Location: mm/page_counter.c:71
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff81350630-ffffffff8135067f: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813c8900)
Location: mm/page_counter.c:71
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff813c8900-ffffffff813c8963: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8144cfe0)
Location: mm/page_counter.c:70
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff8144cfe0-ffffffff8144d046: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814828a0)
Location: mm/page_counter.c:70
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff814828a0-ffffffff81482906: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814b1c20)
Location: mm/page_counter.c:70
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff814b1c20-ffffffff814b1c86: page_counter_charge (STB_GLOBAL)
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
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffff800010360af8)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffff800010360af8-ffff800010360b70: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c0553270)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c0553270-c05532dc: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c00000000044bc70)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
c00000000044bc70-c00000000044bd10: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffe000240372)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffe000240372-ffffffe0002403c6: page_counter_charge (STB_GLOBAL)
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
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b7520)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812b7520-ffffffff812b7577: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812a86f0)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812a86f0-ffffffff812a8747: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b5330)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812b5330-ffffffff812b5387: page_counter_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812c5870)
Location: mm/page_counter.c:72
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
**Symbols:**

```
ffffffff812c5870-ffffffff812c58c7: page_counter_charge (STB_GLOBAL)
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
