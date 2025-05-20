# Function: <code>follow_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bc3c3)
Location: mm/memory.c:3563
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_phys
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd84f)
Location: mm/memory.c:3758
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed37f)
Location: mm/memory.c:3822
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f838f)
Location: mm/memory.c:4111
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff8121053f)
Location: mm/memory.c:4289
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff81230f43)
Location: mm/memory.c:4334
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff8124470e)
Location: mm/memory.c:4124
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff812566cc)
Location: mm/memory.c:4175
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff81264c5c)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129502b)
Location: mm/memory.c:4565
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129fe9b)
Location: mm/memory.c:4809
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff8129fd90-ffffffff8129fdab: follow_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5795)
Location: mm/memory.c:4836
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff812a55f0-ffffffff812a560b: follow_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6c81)
Location: mm/memory.c:4982
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff812e6ae0-ffffffff812e6afb: follow_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5257
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
**Symbols:**

```
ffffffff81e6de75-ffffffff81e6de8e: follow_pte.cold (STB_LOCAL)
ffffffff8133d6f0-ffffffff8133d94c: follow_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5337
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
**Symbols:**

```
ffffffff82063eb9-ffffffff82063ed2: follow_pte.cold (STB_LOCAL)
ffffffff813b6710-ffffffff813b6970: follow_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5529
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
**Symbols:**

```
ffffffff820e3583-ffffffff820e359c: follow_pte.cold (STB_LOCAL)
ffffffff813eb130-ffffffff813eb327: follow_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int follow_pte(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5755
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
**Symbols:**

```
ffffffff821bff9c-ffffffff821bffb5: follow_pte.cold (STB_LOCAL)
ffffffff81415150-ffffffff81415341: follow_pte (STB_GLOBAL)
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
In mm/memory.c (ffff8000102f482c)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
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
In mm/memory.c (c05169b4)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
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
In mm/memory.c (c0000000003c690c)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffe0002068d8)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff8125d2ac)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff8124f70b)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff8125b04c)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
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
In mm/memory.c (ffffffff8126aa1e)
Location: mm/memory.c:4200
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
