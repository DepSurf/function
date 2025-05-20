# Function: <code>alloc_irq_index</code>

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
In drivers/iommu/amd_iommu.c (ffffffff81531c01)
Location: drivers/iommu/amd_iommu.c:3623
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff81585d81)
Location: drivers/iommu/amd_iommu.c:3637
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff815b3152)
Location: drivers/iommu/amd_iommu.c:3736
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff815c8924)
Location: drivers/iommu/amd_iommu.c:3876
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff8162f297)
Location: drivers/iommu/amd_iommu.c:3662
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff81669a88)
Location: drivers/iommu/amd_iommu.c:3722
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff81688658)
Location: drivers/iommu/amd_iommu.c:3787
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd_iommu.c (ffffffff816bfc00)
Location: drivers/iommu/amd_iommu.c:3768
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0900)
Location: drivers/iommu/amd_iommu.c:3822
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff816e0900-ffffffff816e0a61: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798460)
Location: drivers/iommu/amd/iommu.c:3238
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81798460-ffffffff817985c1: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a6af0)
Location: drivers/iommu/amd/iommu.c:3329
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff817a6af0-ffffffff817a6c51: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81788580)
Location: drivers/iommu/amd/iommu.c:2695
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81788580-ffffffff817886e4: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2763
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff8180feb0-ffffffff8181001d: alloc_irq_index (STB_LOCAL)
ffffffff81cfe22a-ffffffff81cfe248: alloc_irq_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2789
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff8194f1c0-ffffffff8194f351: alloc_irq_index (STB_LOCAL)
ffffffff81ec69ad-ffffffff81ec69cb: alloc_irq_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int alloc_irq_index(struct amd_iommu *iommu, u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2962
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81ab4310-ffffffff81ab448d: alloc_irq_index (STB_LOCAL)
ffffffff82096df1-ffffffff82096e0f: alloc_irq_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int alloc_irq_index(struct amd_iommu *iommu, u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3008
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81b01e10-ffffffff81b01f8d: alloc_irq_index (STB_LOCAL)
ffffffff82117dc9-ffffffff82117de7: alloc_irq_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int alloc_irq_index(struct amd_iommu *iommu, u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3047
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81b55780-ffffffff81b558fd: alloc_irq_index (STB_LOCAL)
ffffffff821f5a7a-ffffffff821f5a98: alloc_irq_index.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6350)
Location: drivers/iommu/amd_iommu.c:3822
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff816a6350-ffffffff816a64b1: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683d40)
Location: drivers/iommu/amd_iommu.c:3822
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81683d40-ffffffff81683ea1: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d45c0)
Location: drivers/iommu/amd_iommu.c:3822
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff816d45c0-ffffffff816d4721: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alloc_irq_index(u16 devid, int count, bool align, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eecc0)
Location: drivers/iommu/amd_iommu.c:3822
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff816eecc0-ffffffff816eee21: alloc_irq_index (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>struct amd_iommu *iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>devid, count, align, pdev</code> ➡️ <code>iommu, devid, count, align, pdev</code>
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
