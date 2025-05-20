# Function: <code>vma_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4bc0)
Location: mm/mmap.c:668
Inline: False
Direct callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:copy_vma
```
**Symbols:**

```
ffffffff811c4bc0-ffffffff811c4c7b: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e09e0)
Location: mm/mmap.c:560
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff811e09e0-ffffffff811e0a9b: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f0910)
Location: mm/mmap.c:587
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff811f0910-ffffffff811f09cb: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fb790)
Location: mm/mmap.c:603
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff811fb790-ffffffff811fb84b: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213cd0)
Location: mm/mmap.c:604
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81213cd0-ffffffff81213d8b: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81234be0)
Location: mm/mmap.c:613
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81234be0-ffffffff81234ca1: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81248360)
Location: mm/mmap.c:637
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81248360-ffffffff81248421: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125a5b0)
Location: mm/mmap.c:639
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8125a5b0-ffffffff8125a671: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81268b90)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81268b90-ffffffff81268c51: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81298d70)
Location: mm/mmap.c:643
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81298d70-ffffffff81298f3a: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a3f30)
Location: mm/mmap.c:685
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff812a3f30-ffffffff812a40fa: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a96a0)
Location: mm/mmap.c:689
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff812a96a0-ffffffff812a986a: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eaca0)
Location: mm/mmap.c:686
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff812eaca0-ffffffff812eae6a: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134da00)
Location: mm/mmap.c:692
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8134da00-ffffffff8134dbf0: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vma_link(struct mm_struct *mm, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c7020)
Location: mm/mmap.c:470
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
```
**Symbols:**

```
ffffffff813c7020-ffffffff813c7120: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vma_link(struct mm_struct *mm, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fb380)
Location: mm/mmap.c:407
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
```
**Symbols:**

```
ffffffff813fb380-ffffffff813fb4a0: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vma_link(struct mm_struct *mm, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff814272e0)
Location: mm/mmap.c:395
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
```
**Symbols:**

```
ffffffff814272e0-ffffffff81427486: vma_link (STB_LOCAL)
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
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010300110)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffff800010300110-ffff800010300214: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051ebc4)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
c051ebc4-c051ec80: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cbf60)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
c0000000003cbf60-c0000000003cc0b0: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020dae4)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffe00020dae4-ffffffe00020dba6: vma_link (STB_LOCAL)
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
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812611e0)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff812611e0-ffffffff812612a1: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81253600)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81253600-ffffffff812536c1: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125ef80)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8125ef80-ffffffff8125f041: vma_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_link(struct mm_struct *mm, struct vm_area_struct *vma, struct vm_area_struct *prev, struct rb_node **rb_link, struct rb_node *rb_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126e950)
Location: mm/mmap.c:640
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8126e950-ffffffff8126ea11: vma_link (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rb_node **rb_link</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rb_node *rb_parent</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
