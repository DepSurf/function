# Function: <code>page_counter_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int page_counter_limit(struct page_counter *counter, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff811f9420)
Location: mm/page_counter.c:134
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_activate_kmem
  - mm/memcontrol.c:memcg_update_kmem_limit
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
```
**Symbols:**

```
ffffffff811f9420-ffffffff811f9473: page_counter_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int page_counter_limit(struct page_counter *counter, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8121cfa0)
Location: mm/page_counter.c:134
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8121cfa0-ffffffff8121cff3: page_counter_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int page_counter_limit(struct page_counter *counter, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8122f5a0)
Location: mm/page_counter.c:134
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8122f5a0-ffffffff8122f5f3: page_counter_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int page_counter_limit(struct page_counter *counter, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8123adf0)
Location: mm/page_counter.c:134
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8123adf0-ffffffff8123ae43: page_counter_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_counter_limit(struct page_counter *counter, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8125a680)
Location: mm/page_counter.c:135
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8125a680-ffffffff8125a6d3: page_counter_limit (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
