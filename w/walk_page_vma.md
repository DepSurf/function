# Function: <code>walk_page_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff811d02f0)
Location: mm/pagewalk.c:288
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff811d02f0-ffffffff811d0350: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff811ed4a0)
Location: mm/pagewalk.c:288
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff811ed4a0-ffffffff811ed4f5: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff811f7890)
Location: mm/pagewalk.c:288
Inline: False
```
**Symbols:**

```
ffffffff811f7890-ffffffff811f78e5: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812029e0)
Location: mm/pagewalk.c:333
Inline: False
```
**Symbols:**

```
ffffffff812029e0-ffffffff81202a35: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8121b750)
Location: mm/pagewalk.c:338
Inline: False
```
**Symbols:**

```
ffffffff8121b750-ffffffff8121b7a5: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8123d530)
Location: mm/pagewalk.c:342
Inline: False
```
**Symbols:**

```
ffffffff8123d530-ffffffff8123d584: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81251a80)
Location: mm/pagewalk.c:342
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:smap_gather_stats
```
**Symbols:**

```
ffffffff81251a80-ffffffff81251ad4: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81263d50)
Location: mm/pagewalk.c:342
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:smap_gather_stats
```
**Symbols:**

```
ffffffff81263d50-ffffffff81263da8: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81272590)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff81272590-ffffffff81272617: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a3160)
Location: mm/pagewalk.c:461
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:smap_gather_stats
  - fs/proc/task_mmu.c:smap_gather_stats
```
**Symbols:**

```
ffffffff812a3160-ffffffff812a3233: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812aea80)
Location: mm/pagewalk.c:461
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff812aea80-ffffffff812aeb53: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3f00)
Location: mm/pagewalk.c:461
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff812b3f00-ffffffff812b3fd3: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812f5ae0)
Location: mm/pagewalk.c:509
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff812f5ae0-ffffffff812f5bb3: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff813599f0)
Location: mm/pagewalk.c:509
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff813599f0-ffffffff81359ad7: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff813d4410)
Location: mm/pagewalk.c:540
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff813d4410-ffffffff813d448c: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81408e70)
Location: mm/pagewalk.c:585
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff81408e70-ffffffff81408f24: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81435590)
Location: mm/pagewalk.c:612
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff81435590-ffffffff81435644: walk_page_vma (STB_GLOBAL)
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
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffff800010307db8)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffff800010307db8-ffff800010307e5c: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (c0525320)
Location: mm/pagewalk.c:356
Inline: False
```
**Symbols:**

```
c0525320-c05253c4: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (c0000000003d6f20)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
c0000000003d6f20-c0000000003d7010: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffe000212cac)
Location: mm/pagewalk.c:356
Inline: False
```
**Symbols:**

```
ffffffe000212cac-ffffffe000212d34: walk_page_vma (STB_GLOBAL)
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
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8126abe0)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff8126abe0-ffffffff8126ac67: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8125cd40)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff8125cd40-ffffffff8125cdc7: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81268980)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff81268980-ffffffff81268a07: walk_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_page_vma(struct vm_area_struct *vma, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81278310)
Location: mm/pagewalk.c:356
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff81278310-ffffffff81278397: walk_page_vma (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mm_walk_ops *ops</code>
</li>
<li>
<b>Param added. </b>
<code>void *private</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_walk *walk</code>
</li>
</ul>
</details>
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
