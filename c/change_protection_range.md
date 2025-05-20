# Function: <code>change_protection_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811c8450)
Location: mm/mprotect.c:213
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff811c8450-ffffffff811c8c7e: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811e45e0)
Location: mm/mprotect.c:217
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff811e45e0-ffffffff811e4f40: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811f4600)
Location: mm/mprotect.c:231
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff811f4600-ffffffff811f4f83: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811ff5a0)
Location: mm/mprotect.c:234
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff811ff5a0-ffffffff811ffdbc: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81217b80)
Location: mm/mprotect.c:251
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81217b80-ffffffff81218560: change_protection_range (STB_LOCAL)
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
In mm/mprotect.c (ffffffff812399c3)
Location: mm/mprotect.c:265
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8124d2a0)
Location: mm/mprotect.c:266
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff8124d2a0-ffffffff8124dd7b: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8125fa90)
Location: mm/mprotect.c:267
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff8125fa90-ffffffff812600d6: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8126e350)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff8126e350-ffffffff8126e9a7: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8129eff0)
Location: mm/mprotect.c:324
Inline: False
```
**Symbols:**

```
ffffffff8129eff0-ffffffff8129f18f: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812aa3b0)
Location: mm/mprotect.c:324
Inline: False
```
**Symbols:**

```
ffffffff812aa3b0-ffffffff812aa54f: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812af7f0)
Location: mm/mprotect.c:324
Inline: False
```
**Symbols:**

```
ffffffff812af7f0-ffffffff812af98f: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:334
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff812f1020-ffffffff812f11d7: change_protection_range (STB_LOCAL)
ffffffff81cbc9c0-ffffffff81cbca59: change_protection_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int change_protection_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:428
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81354790-ffffffff81354e00: change_protection_range (STB_LOCAL)
ffffffff81e6e5a9-ffffffff81e6e627: change_protection_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int change_protection_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:484
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff813cecc0-ffffffff813cf2f8: change_protection_range (STB_LOCAL)
ffffffff820644b1-ffffffff82064538: change_protection_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int change_protection_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:483
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81403920-ffffffff81403c85: change_protection_range (STB_LOCAL)
ffffffff820e3b8f-ffffffff820e3c13: change_protection_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int change_protection_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:485
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff8142fea0-ffffffff814301de: change_protection_range (STB_LOCAL)
ffffffff821c0738-ffffffff821c07bc: change_protection_range.cold (STB_LOCAL)
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
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffff800010304e98)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffff800010304e98-ffff8000103056ec: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c0523198)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
c0523198-c0523694: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c0000000003d1d00)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
c0000000003d1d00-c0000000003d2be4: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffe00021106c)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffe00021106c-ffffffe000211500: change_protection_range (STB_LOCAL)
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
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812669a0)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff812669a0-ffffffff81266ff7: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81258860)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81258860-ffffffff812592eb: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81264740)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81264740-ffffffff81264d97: change_protection_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int change_protection_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81274100)
Location: mm/mprotect.c:301
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81274100-ffffffff81274750: change_protection_range (STB_LOCAL)
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
<code>vma, addr, end, newprot, cp_flags</code> ➡️ <code>tlb, vma, addr, end, newprot, cp_flags</code>
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
