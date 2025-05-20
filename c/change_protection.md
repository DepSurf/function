# Function: <code>change_protection</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811c8c80)
Location: mm/mprotect.c:243
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff811c8c80-ffffffff811c8c9d: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811e4f40)
Location: mm/mprotect.c:247
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff811e4f40-ffffffff811e4f5d: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811f4f90)
Location: mm/mprotect.c:261
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff811f4f90-ffffffff811f4fad: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811ffdc0)
Location: mm/mprotect.c:264
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff811ffdc0-ffffffff811ffddd: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81218560)
Location: mm/mprotect.c:281
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff81218560-ffffffff8121857d: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81239960)
Location: mm/mprotect.c:295
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff81239960-ffffffff81239f1e: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8124e070)
Location: mm/mprotect.c:296
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff8124e070-ffffffff8124e08d: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812603c0)
Location: mm/mprotect.c:297
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff812603c0-ffffffff812603dd: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8126ebe0)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff8126ebe0-ffffffff8126ebfd: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8129f190)
Location: mm/mprotect.c:354
Inline: True
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff8129f190-ffffffff8129f1bb: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812aa550)
Location: mm/mprotect.c:354
Inline: True
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff812aa550-ffffffff812aa57b: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812af990)
Location: mm/mprotect.c:354
Inline: True
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff812af990-ffffffff812af9bb: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812f11e0)
Location: mm/mprotect.c:364
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff812f11e0-ffffffff812f120b: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int change_protection(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81354e00)
Location: mm/mprotect.c:454
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
```
**Symbols:**

```
ffffffff81354e00-ffffffff81354e6e: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int change_protection(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813cf310)
Location: mm/mprotect.c:510
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
```
**Symbols:**

```
ffffffff813cf310-ffffffff813cf37e: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int change_protection(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81403ca0)
Location: mm/mprotect.c:513
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
```
**Symbols:**

```
ffffffff81403ca0-ffffffff81403d1c: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int change_protection(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff814301f0)
Location: mm/mprotect.c:515
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
```
**Symbols:**

```
ffffffff814301f0-ffffffff8143026c: change_protection (STB_GLOBAL)
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
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffff8000103056f0)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffff8000103056f0-ffff800010305784: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c05237d4)
Location: mm/mprotect.c:331
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
c0523694-c05236c8: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c0000000003d2bf0)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
c0000000003d2bf0-c0000000003d2c34: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffe000211500)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffe000211500-ffffffe00021156e: change_protection (STB_GLOBAL)
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
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81267230)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff81267230-ffffffff8126724d: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81259580)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff81259580-ffffffff8125959d: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81264fd0)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff81264fd0-ffffffff81264fed: change_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int change_protection(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81274980)
Location: mm/mprotect.c:331
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:change_prot_numa
```
**Symbols:**

```
ffffffff81274980-ffffffff8127499d: change_protection (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cp_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int dirty_accountable</code>
</li>
<li>
<b>Param removed. </b>
<code>int prot_numa</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_gather *tlb</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, start, end, newprot, cp_flags</code> ➡️ <code>tlb, vma, start, end, newprot, cp_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t newprot</code>
</li>
<li>
<b>Param reordered. </b>
<code>tlb, vma, start, end, newprot, cp_flags</code> ➡️ <code>tlb, vma, start, end, cp_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
