# Function: <code>page_counter_set_max</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8127e4b0)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8127e4b0-ffffffff8127e503: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81292ba0)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81292ba0-ffffffff81292c0c: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ad540)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812ad540-ffffffff812ad59d: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812bf090)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812bf090-ffffffff812bf0ed: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812f4390)
Location: mm/page_counter.c:169
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812f4390-ffffffff812f43ed: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ffc80)
Location: mm/page_counter.c:169
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812ffc80-ffffffff812ffcdd: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81306920)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81306920-ffffffff8130697d: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81350770)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81350770-ffffffff813507cd: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813c8a90)
Location: mm/page_counter.c:172
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813c8a90-ffffffff813c8b11: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8144d1a0)
Location: mm/page_counter.c:171
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8144d1a0-ffffffff8144d22c: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81482a60)
Location: mm/page_counter.c:171
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81482a60-ffffffff81482aec: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814b1de0)
Location: mm/page_counter.c:171
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff814b1de0-ffffffff814b1e6c: page_counter_set_max (STB_GLOBAL)
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
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffff800010360cd0)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffff800010360cd0-ffff800010360d60: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c05533f4)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
```
**Symbols:**

```
c05533f4-c0553470: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c00000000044bec0)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
c00000000044bec0-c00000000044bf98: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffe00024049c)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffe00024049c-ffffffe0002404fe: page_counter_set_max (STB_GLOBAL)
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
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b7670)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812b7670-ffffffff812b76cd: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812a8840)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812a8840-ffffffff812a889d: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b5480)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812b5480-ffffffff812b54dd: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_counter_set_max(struct page_counter *counter, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812c59c0)
Location: mm/page_counter.c:173
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812c59c0-ffffffff812c59fc: page_counter_set_max (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
