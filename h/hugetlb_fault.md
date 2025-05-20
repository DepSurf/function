# Function: <code>hugetlb_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dec00)
Location: mm/hugetlb.c:3684
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff811dec00-ffffffff811df3ad: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fd070)
Location: mm/hugetlb.c:3699
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff811fd070-ffffffff811fd9e9: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120db50)
Location: mm/hugetlb.c:3813
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff8120db50-ffffffff8120e4c4: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81219970)
Location: mm/hugetlb.c:3831
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81219970-ffffffff81219e71: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812349b0)
Location: mm/hugetlb.c:3852
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff812349b0-ffffffff81234f39: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81257920)
Location: mm/hugetlb.c:3882
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81257920-ffffffff81257e8c: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126bfe0)
Location: mm/hugetlb.c:3922
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff8126bfe0-ffffffff8126c546: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287310)
Location: mm/hugetlb.c:4002
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81287310-ffffffff81287900: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81296f20)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81296f20-ffffffff81297510: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812ca570)
Location: mm/hugetlb.c:4538
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff812ca570-ffffffff812caaf5: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d61a0)
Location: mm/hugetlb.c:4528
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff812d61a0-ffffffff812d671f: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dd340)
Location: mm/hugetlb.c:4769
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff812dd340-ffffffff812dd8c6: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5074
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81cc001e-ffffffff81cc0171: hugetlb_fault.cold (STB_LOCAL)
ffffffff813244c0-ffffffff81324a81: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5701
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81e723d0-ffffffff81e7259b: hugetlb_fault.cold (STB_LOCAL)
ffffffff813928e0-ffffffff8139325a: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5982
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff82066daa-ffffffff82066e71: hugetlb_fault.cold (STB_LOCAL)
ffffffff81411290-ffffffff814119da: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6081
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff820e65f6-ffffffff820e66ad: hugetlb_fault.cold (STB_LOCAL)
ffffffff81444710-ffffffff81444e64: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6349
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff821c3801-ffffffff821c393a: hugetlb_fault.cold (STB_LOCAL)
ffffffff8147e7d0-ffffffff8147f0e1: hugetlb_fault (STB_GLOBAL)
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
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010334d20)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffff800010334d20-ffff800010335334: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/hugetlb.h:216
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040e3e0)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
c00000000040e3e0-c00000000040eca8: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000231504)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffe000231504-ffffffe0002319ec: hugetlb_fault (STB_GLOBAL)
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
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128f500)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff8128f500-ffffffff8128faf0: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812811d0)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff812811d0-ffffffff812817a5: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d310)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff8128d310-ffffffff8128d900: hugetlb_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t hugetlb_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129d0d0)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff8129d0d0-ffffffff8129d6a8: hugetlb_fault (STB_GLOBAL)
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
