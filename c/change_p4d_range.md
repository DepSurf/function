# Function: <code>change_p4d_range</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811ff622)
Location: mm/mprotect.c:214
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81217c0b)
Location: mm/mprotect.c:231
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81239a65)
Location: mm/mprotect.c:245
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8124d380)
Location: mm/mprotect.c:246
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8125fb82)
Location: mm/mprotect.c:247
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8126e442)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int change_p4d_range(struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8129edb0)
Location: mm/mprotect.c:304
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff8129edb0-ffffffff8129efef: change_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int change_p4d_range(struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812aa170)
Location: mm/mprotect.c:304
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812aa170-ffffffff812aa3b0: change_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int change_p4d_range(struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812af5f0)
Location: mm/mprotect.c:304
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812af5f0-ffffffff812af7ea: change_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int change_p4d_range(struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812f0e20)
Location: mm/mprotect.c:314
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812f0e20-ffffffff812f101c: change_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81354958)
Location: mm/mprotect.c:407
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813ceea2)
Location: mm/mprotect.c:463
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int change_p4d_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81403590)
Location: mm/mprotect.c:460
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81403590-ffffffff81403902: change_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int change_p4d_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8142fb10)
Location: mm/mprotect.c:462
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff8142fb10-ffffffff8142fe82: change_p4d_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffff800010304f94)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mprotect.c (c0523290)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c0000000003d1ee8)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffe0002110e4)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81266a92)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8125894b)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81264832)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812741f2)
Location: mm/mprotect.c:281
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
