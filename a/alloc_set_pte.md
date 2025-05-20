# Function: <code>alloc_set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_set_pte(struct fault_env *fe, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da1d0)
Location: mm/memory.c:2998
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811da1d0-ffffffff811da7d3: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e9d00)
Location: mm/memory.c:3036
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff811e9d00-ffffffff811ea2f7: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f4e00)
Location: mm/memory.c:3232
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff811f4e00-ffffffff811f5344: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120cf00)
Location: mm/memory.c:3401
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff8120cf00-ffffffff8120d45d: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122dac0)
Location: mm/memory.c:3446
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff8122dac0-ffffffff8122e03e: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812410f0)
Location: mm/memory.c:3207
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff812410f0-ffffffff81241691: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812533d0)
Location: mm/memory.c:3259
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff812533d0-ffffffff812539d3: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81261930)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff81261930-ffffffff81261f33: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81291bb0)
Location: mm/memory.c:3649
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff81291bb0-ffffffff81291d69: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129c480)
Location: mm/memory.c:3809
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff8129c480-ffffffff8129c630: alloc_set_pte (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f8be8)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffff8000102f8be8-ffff8000102f91f4: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051b2e0)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
c051b2e0-c051b604: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c22d0)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
c0000000003c22d0-c0000000003c2d50: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000208f26)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffe000208f26-ffffffe0002091d4: alloc_set_pte (STB_GLOBAL)
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
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259f80)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff81259f80-ffffffff8125a583: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124c3b0)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff8124c3b0-ffffffff8124c9a9: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257d20)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff81257d20-ffffffff81258323: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault *vmf, struct mem_cgroup *memcg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81267710)
Location: mm/memory.c:3284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff81267710-ffffffff81267d02: alloc_set_pte (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env *fe</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param reordered. </b>
<code>vmf, memcg, page</code> ➡️ <code>vmf, page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
