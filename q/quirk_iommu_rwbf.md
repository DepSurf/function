# Function: <code>quirk_iommu_rwbf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815357b0)
Location: drivers/iommu/intel-iommu.c:5130
Inline: False
```
**Symbols:**

```
ffffffff815357b0-ffffffff815357d1: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81589e90)
Location: drivers/iommu/intel-iommu.c:5268
Inline: False
```
**Symbols:**

```
ffffffff81589e90-ffffffff81589eb1: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b7540)
Location: drivers/iommu/intel-iommu.c:5423
Inline: False
```
**Symbols:**

```
ffffffff815b7540-ffffffff815b7561: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cdb30)
Location: drivers/iommu/intel-iommu.c:5457
Inline: False
```
**Symbols:**

```
ffffffff815cdb30-ffffffff815cdb51: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81634970)
Location: drivers/iommu/intel-iommu.c:5372
Inline: False
```
**Symbols:**

```
ffffffff81634970-ffffffff81634991: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8167539e)
Location: drivers/iommu/intel-iommu.c:5410
Inline: False
```
**Symbols:**

```
ffffffff8167539e-ffffffff816753bf: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81693821)
Location: drivers/iommu/intel-iommu.c:5414
Inline: False
```
**Symbols:**

```
ffffffff81693821-ffffffff81693842: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cbc99)
Location: drivers/iommu/intel-iommu.c:5708
Inline: False
```
**Symbols:**

```
ffffffff816cbc99-ffffffff816cbcc1: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ef579)
Location: drivers/iommu/intel-iommu.c:6035
Inline: False
```
**Symbols:**

```
ffffffff816ef579-ffffffff816ef5a1: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a179a)
Location: drivers/iommu/intel/iommu.c:6135
Inline: True
```
**Symbols:**

```
ffffffff817a1780-ffffffff817a17bc: quirk_iommu_rwbf (STB_LOCAL)
ffffffff817a6d26-ffffffff817a6d3d: quirk_iommu_rwbf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817aef5a)
Location: drivers/iommu/intel/iommu.c:5595
Inline: True
```
**Symbols:**

```
ffffffff817aef40-ffffffff817aef7c: quirk_iommu_rwbf (STB_LOCAL)
ffffffff81c0c53c-ffffffff81c0c553: quirk_iommu_rwbf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179179a)
Location: drivers/iommu/intel/iommu.c:5634
Inline: True
```
**Symbols:**

```
ffffffff81791780-ffffffff817917bc: quirk_iommu_rwbf (STB_LOCAL)
ffffffff81bfdcb6-ffffffff81bfdccd: quirk_iommu_rwbf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81818eaa)
Location: drivers/iommu/intel/iommu.c:5674
Inline: True
```
**Symbols:**

```
ffffffff81818e90-ffffffff81818ecc: quirk_iommu_rwbf (STB_LOCAL)
ffffffff81cff495-ffffffff81cff4ac: quirk_iommu_rwbf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195a05a)
Location: drivers/iommu/intel/iommu.c:4990
Inline: True
```
**Symbols:**

```
ffffffff8195a040-ffffffff8195a07c: quirk_iommu_rwbf (STB_LOCAL)
ffffffff81ec7c84-ffffffff81ec7ca5: quirk_iommu_rwbf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1570)
Location: drivers/iommu/intel/iommu.c:4881
Inline: True
```
**Symbols:**

```
ffffffff81ac1570-ffffffff81ac15ed: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0df60)
Location: drivers/iommu/intel/iommu.c:4839
Inline: True
```
**Symbols:**

```
ffffffff81b0df60-ffffffff81b0dfe1: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b629c0)
Location: drivers/iommu/intel/iommu.c:4965
Inline: True
```
**Symbols:**

```
ffffffff81b629c0-ffffffff81b62a41: quirk_iommu_rwbf (STB_LOCAL)
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
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4d69)
Location: drivers/iommu/intel-iommu.c:6035
Inline: False
```
**Symbols:**

```
ffffffff816b4d69-ffffffff816b4d91: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816929a9)
Location: drivers/iommu/intel-iommu.c:6035
Inline: False
```
**Symbols:**

```
ffffffff816929a9-ffffffff816929d1: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e3239)
Location: drivers/iommu/intel-iommu.c:6035
Inline: False
```
**Symbols:**

```
ffffffff816e3239-ffffffff816e3261: quirk_iommu_rwbf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void quirk_iommu_rwbf(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd8c9)
Location: drivers/iommu/intel-iommu.c:6035
Inline: False
```
**Symbols:**

```
ffffffff816fd8c9-ffffffff816fd8f1: quirk_iommu_rwbf (STB_LOCAL)
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
