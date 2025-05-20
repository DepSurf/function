# Function: <code>__pci_enable_msix_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1060)
Location: drivers/pci/msi.c:1113
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff814a1060-ffffffff814a112f: __pci_enable_msix_range (STB_LOCAL)
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
In drivers/pci/msi.c (ffffffff814c31c5)
Location: drivers/pci/msi.c:1130
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
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
In drivers/pci/msi.c (ffffffff814cd665)
Location: drivers/pci/msi.c:1082
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
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
In drivers/pci/msi.c (ffffffff8150dba5)
Location: drivers/pci/msi.c:1082
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
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
In drivers/pci/msi.c (ffffffff81542ac7)
Location: drivers/pci/msi.c:1081
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81559450)
Location: drivers/pci/msi.c:1087
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff81559450-ffffffff815599a0: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1115
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff81589510-ffffffff81589a53: __pci_enable_msix_range (STB_LOCAL)
ffffffff8158a963-ffffffff8158a980: __pci_enable_msix_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff815ab520-ffffffff815aba50: __pci_enable_msix_range (STB_LOCAL)
ffffffff815ac2d7-ffffffff815ac2f4: __pci_enable_msix_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654aa5)
Location: drivers/pci/msi.c:1116
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_enable_msix_range
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff81654780-ffffffff8165492b: __pci_enable_msix_range.part.0 (STB_LOCAL)
ffffffff81655430-ffffffff8165544e: __pci_enable_msix_range.part.0.cold (STB_LOCAL)
ffffffff81654930-ffffffff8165495b: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e035)
Location: drivers/pci/msi.c:1140
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_enable_msix_range
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff8165de50-ffffffff8165dffb: __pci_enable_msix_range.part.0 (STB_LOCAL)
ffffffff81bf8ea3-ffffffff81bf8ec1: __pci_enable_msix_range.part.0.cold (STB_LOCAL)
ffffffff8165e000-ffffffff8165e02b: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640215)
Location: drivers/pci/msi.c:1146
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_enable_msix_range
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff81640030-ffffffff816401db: __pci_enable_msix_range.part.0 (STB_LOCAL)
ffffffff81beacfd-ffffffff81bead1b: __pci_enable_msix_range.part.0.cold (STB_LOCAL)
ffffffff816401e0-ffffffff8164020b: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b156a)
Location: drivers/pci/msi.c:1054
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
  - drivers/pci/msi.c:pci_enable_msix_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4a30)
Location: drivers/pci/msi/msi.c:921
Inline: True
Direct callers:
  - drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff817d4860-ffffffff817d4a28: __pci_enable_msix_range.part.0 (STB_LOCAL)
ffffffff81eac653-ffffffff81eac66b: __pci_enable_msix_range.part.0.cold (STB_LOCAL)
ffffffff817d4a30-ffffffff817d4b20: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f5be0)
Location: drivers/pci/msi/msi.c:775
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/api.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff818f5be0-ffffffff818f6158: __pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81939010)
Location: drivers/pci/msi/msi.c:770
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/api.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff81939010-ffffffff819395b3: __pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981e70)
Location: drivers/pci/msi/msi.c:772
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/api.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff81981e70-ffffffff81982413: __pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (ffff800010714d78)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffff800010714d78-ffff80001071531c: __pci_enable_msix_range.part.0 (STB_LOCAL)
ffff800010715320-ffff8000107153a8: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089f6b4)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
c089f6b4-c089fc48: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000884800)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
c000000000884800-c000000000884f64: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de686)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffe0004de686-ffffffe0004deaec: __pci_enable_msix_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff8159ecf0-ffffffff8159f218: __pci_enable_msix_range (STB_LOCAL)
ffffffff8159faa7-ffffffff8159fac4: __pci_enable_msix_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff8158de80-ffffffff8158e3b0: __pci_enable_msix_range (STB_LOCAL)
ffffffff8158ec37-ffffffff8158ec54: __pci_enable_msix_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff8159f270-ffffffff8159f7a0: __pci_enable_msix_range (STB_LOCAL)
ffffffff815a0027-ffffffff815a0044: __pci_enable_msix_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec, struct irq_affinity *affd, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1116
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
```
**Symbols:**

```
ffffffff815b96a0-ffffffff815b9bd0: __pci_enable_msix_range (STB_LOCAL)
ffffffff815ba457-ffffffff815ba474: __pci_enable_msix_range.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity *affd</code> ➡️ <code>struct irq_affinity *affd</code>
</li>
</ul>
</details>
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
