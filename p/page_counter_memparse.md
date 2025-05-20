# Function: <code>page_counter_memparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff811f9480)
Location: mm/page_counter.c:175
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
```
**Symbols:**

```
ffffffff811f9480-ffffffff811f9510: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8121d000)
Location: mm/page_counter.c:175
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff8121d000-ffffffff8121d090: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8122f600)
Location: mm/page_counter.c:175
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff8122f600-ffffffff8122f690: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8123ae50)
Location: mm/page_counter.c:175
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff8123ae50-ffffffff8123aee2: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8125a6e0)
Location: mm/page_counter.c:176
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff8125a6e0-ffffffff8125a772: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8127e570)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff8127e570-ffffffff8127e600: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81292c70)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff81292c70-ffffffff81292d00: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ad600)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff812ad600-ffffffff812ad690: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812bf150)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff812bf150-ffffffff812bf1e0: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812f4470)
Location: mm/page_counter.c:244
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812f4470-ffffffff812f4500: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ffd60)
Location: mm/page_counter.c:244
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812ffd60-ffffffff812ffdf0: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81306a00)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff81306a00-ffffffff81306a90: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81350850)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff81350850-ffffffff813508e0: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813c8bc0)
Location: mm/page_counter.c:247
Inline: False
Direct callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff813c8bc0-ffffffff813c8c62: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8144d300)
Location: mm/page_counter.c:246
Inline: False
Direct callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff8144d300-ffffffff8144d3a2: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81482bc0)
Location: mm/page_counter.c:246
Inline: False
Direct callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff81482bc0-ffffffff81482c64: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814b1f40)
Location: mm/page_counter.c:246
Inline: False
Direct callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff814b1f40-ffffffff814b1fe4: page_counter_memparse (STB_GLOBAL)
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
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffff800010360df0)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffff800010360df0-ffff800010360ea0: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c05534f0)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
c05534f0-c05535ac: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c00000000044c060)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
c00000000044c060-c00000000044c2b4: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffe000240576)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffe000240576-ffffffe0002405f4: page_counter_memparse (STB_GLOBAL)
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
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b7730)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff812b7730-ffffffff812b77c0: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812a8900)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff812a8900-ffffffff812a8990: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b5540)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff812b5540-ffffffff812b55d0: page_counter_memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_counter_memparse(const char *buf, const char *max, long unsigned int *nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812c5a60)
Location: mm/page_counter.c:248
Inline: False
Direct callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
**Symbols:**

```
ffffffff812c5a60-ffffffff812c5af0: page_counter_memparse (STB_GLOBAL)
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
