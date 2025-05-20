# Function: <code>intel_change_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8153ba80)
Location: drivers/iommu/intel-svm.c:211
Inline: False
```
**Symbols:**

```
ffffffff8153ba80-ffffffff8153ba9d: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815905c0)
Location: drivers/iommu/intel-svm.c:211
Inline: False
```
**Symbols:**

```
ffffffff815905c0-ffffffff815905dd: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815bde50)
Location: drivers/iommu/intel-svm.c:217
Inline: False
```
**Symbols:**

```
ffffffff815bde50-ffffffff815bde6d: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815d3f10)
Location: drivers/iommu/intel-svm.c:218
Inline: False
```
**Symbols:**

```
ffffffff815d3f10-ffffffff815d3f2d: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8163ac60)
Location: drivers/iommu/intel-svm.c:222
Inline: False
```
**Symbols:**

```
ffffffff8163ac60-ffffffff8163ac7d: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81676250)
Location: drivers/iommu/intel-svm.c:234
Inline: False
```
**Symbols:**

```
ffffffff81676250-ffffffff8167626d: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_change_pte(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81695780)
Location: drivers/iommu/intel-svm.c:183
Inline: False
```
**Symbols:**

```
ffffffff81695780-ffffffff816957e1: intel_change_pte (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
