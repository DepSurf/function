# Function: <code>page_referenced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cc220)
Location: mm/rmap.c:928
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811cc220-ffffffff811cc356: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e9160)
Location: mm/rmap.c:968
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811e9160-ffffffff811e92cd: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811fa4b0)
Location: mm/rmap.c:967
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811fa4b0-ffffffff811fa61d: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812051a0)
Location: mm/rmap.c:834
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812051a0-ffffffff8120530a: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121e150)
Location: mm/rmap.c:835
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8121e150-ffffffff8121e2ba: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81240010)
Location: mm/rmap.c:836
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81240010-ffffffff81240179: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81254710)
Location: mm/rmap.c:836
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81254710-ffffffff81254879: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812669c0)
Location: mm/rmap.c:836
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812669c0-ffffffff81266b29: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812752e0)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812752e0-ffffffff81275449: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a6710)
Location: mm/rmap.c:850
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff812a6710-ffffffff812a6875: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1bb0)
Location: mm/rmap.c:850
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff812b1bb0-ffffffff812b1d15: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b7280)
Location: mm/rmap.c:854
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b7280-ffffffff812b73e5: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f96a0)
Location: mm/rmap.c:855
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812f96a0-ffffffff812f9817: page_referenced (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030b1a8)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffff80001030b1a8-ffff80001030b350: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c05275d0)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c05275d0-c05277bc: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003db210)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c0000000003db210-c0000000003db460: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000214bba)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffe000214bba-ffffffe000214d52: page_referenced (STB_GLOBAL)
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
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126d930)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8126d930-ffffffff8126da99: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125f960)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8125f960-ffffffff8125fac9: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b6d0)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8126b6d0-ffffffff8126b839: page_referenced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_referenced(struct page *page, int is_locked, struct mem_cgroup *memcg, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127b060)
Location: mm/rmap.c:837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8127b060-ffffffff8127b1c9: page_referenced (STB_GLOBAL)
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
