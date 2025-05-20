# Function: <code>mmu_notifier_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3c80)
Location: mm/mmu_notifier.c:315
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff811e3c80-ffffffff811e3c95: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202720)
Location: mm/mmu_notifier.c:315
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81202720-ffffffff81202735: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81214560)
Location: mm/mmu_notifier.c:315
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81214560-ffffffff81214575: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121f9e0)
Location: mm/mmu_notifier.c:296
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8121f9e0-ffffffff8121f9f5: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123abf0)
Location: mm/mmu_notifier.c:303
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8123abf0-ffffffff8123ac05: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125e280)
Location: mm/mmu_notifier.c:334
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8125e280-ffffffff8125e295: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81272b00)
Location: mm/mmu_notifier.c:305
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81272b00-ffffffff81272b15: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128e0f0)
Location: mm/mmu_notifier.c:303
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8128e0f0-ffffffff8128e105: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129dd10)
Location: mm/mmu_notifier.c:333
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8129dd10-ffffffff8129dd52: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d2556)
Location: mm/mmu_notifier.c:706
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff812d24a0-ffffffff812d24e2: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812ddec0)
Location: mm/mmu_notifier.c:722
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff812ddec0-ffffffff812ddf50: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5470)
Location: mm/mmu_notifier.c:722
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff812e5470-ffffffff812e54fd: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132d060)
Location: mm/mmu_notifier.c:722
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8132d060-ffffffff8132d0db: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139d310)
Location: mm/mmu_notifier.c:722
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8139d310-ffffffff8139d392: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141c790)
Location: mm/mmu_notifier.c:722
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8141c790-ffffffff8141c812: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8144fd40)
Location: mm/mmu_notifier.c:722
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8144fd40-ffffffff8144fdd4: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81489a70)
Location: mm/mmu_notifier.c:714
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff81489a70-ffffffff81489b04: mmu_notifier_register (STB_GLOBAL)
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
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033d128)
Location: mm/mmu_notifier.c:333
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_create_vm
```
**Symbols:**

```
ffff80001033d128-ffff80001033d180: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c05435f4)
Location: mm/mmu_notifier.c:333
Inline: False
```
**Symbols:**

```
c05435f4-c054363c: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c0000000004182a0)
Location: mm/mmu_notifier.c:333
Inline: False
```
**Symbols:**

```
c0000000004182a0-c00000000041831c: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe000232828)
Location: mm/mmu_notifier.c:333
Inline: False
```
**Symbols:**

```
ffffffe000232828-ffffffe00023287a: mmu_notifier_register (STB_GLOBAL)
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
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812962f0)
Location: mm/mmu_notifier.c:333
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff812962f0-ffffffff81296332: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81287f00)
Location: mm/mmu_notifier.c:333
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81287f00-ffffffff81287f42: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81294100)
Location: mm/mmu_notifier.c:333
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81294100-ffffffff81294142: mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a3f30)
Location: mm/mmu_notifier.c:333
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff812a3f30-ffffffff812a3f72: mmu_notifier_register (STB_GLOBAL)
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
<code>struct mmu_notifier *subscription</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mmu_notifier *mn</code>
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
