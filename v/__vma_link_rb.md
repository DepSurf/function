# Function: <code>__vma_link_rb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4ab0)
Location: mm/mmap.c:616
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff811c4ab0-ffffffff811c4bbc: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e08d0)
Location: mm/mmap.c:508
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff811e08d0-ffffffff811e09dc: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f0800)
Location: mm/mmap.c:535
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff811f0800-ffffffff811f090c: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fb6b0)
Location: mm/mmap.c:551
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff811fb6b0-ffffffff811fb78d: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213be0)
Location: mm/mmap.c:552
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81213be0-ffffffff81213cc1: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81234b00)
Location: mm/mmap.c:561
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81234b00-ffffffff81234bde: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81248280)
Location: mm/mmap.c:585
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81248280-ffffffff8124835e: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125a4d0)
Location: mm/mmap.c:587
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff8125a4d0-ffffffff8125a5a2: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81268a10)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81268a10-ffffffff81268b8d: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81299826)
Location: mm/mmap.c:591
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81299290-ffffffff812993f6: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a498f)
Location: mm/mmap.c:633
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff812a4450-ffffffff812a45b6: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812aa0fe)
Location: mm/mmap.c:637
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff812a9bc0-ffffffff812a9d26: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eb6fe)
Location: mm/mmap.c:636
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff812eb1c0-ffffffff812eb326: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134e50f)
Location: mm/mmap.c:642
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8134df70-ffffffff8134e0fe: __vma_link_rb (STB_GLOBAL)
```
</details>
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
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000102fff78)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffff8000102fff78-ffff800010300110: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051ea20)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
c051ea20-c051ebc4: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cbd70)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
c0000000003cbd70-c0000000003cbf54: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020d9bc)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffe00020d9bc-ffffffe00020dae4: __vma_link_rb (STB_GLOBAL)
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
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261060)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81261060-ffffffff812611dd: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81253480)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81253480-ffffffff812535fd: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125ee00)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff8125ee00-ffffffff8125ef7d: __vma_link_rb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __vma_link_rb(struct mm_struct *mm, struct vm_area_struct *vma, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126e7d0)
Location: mm/mmap.c:588
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff8126e7d0-ffffffff8126e94d: __vma_link_rb (STB_GLOBAL)
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
