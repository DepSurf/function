# Function: <code>quirk_iommu_igfx</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ef551)
Location: drivers/iommu/intel-iommu.c:5994
Inline: False
```
**Symbols:**

```
ffffffff816ef551-ffffffff816ef579: quirk_iommu_igfx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a175a)
Location: drivers/iommu/intel/iommu.c:6091
Inline: True
```
**Symbols:**

```
ffffffff817a1740-ffffffff817a177c: quirk_iommu_igfx (STB_LOCAL)
ffffffff817a6d0f-ffffffff817a6d26: quirk_iommu_igfx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817aef1a)
Location: drivers/iommu/intel/iommu.c:5551
Inline: True
```
**Symbols:**

```
ffffffff817aef00-ffffffff817aef3c: quirk_iommu_igfx (STB_LOCAL)
ffffffff81c0c525-ffffffff81c0c53c: quirk_iommu_igfx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179175a)
Location: drivers/iommu/intel/iommu.c:5590
Inline: True
```
**Symbols:**

```
ffffffff81791740-ffffffff8179177c: quirk_iommu_igfx (STB_LOCAL)
ffffffff81bfdc9f-ffffffff81bfdcb6: quirk_iommu_igfx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81818e6a)
Location: drivers/iommu/intel/iommu.c:5615
Inline: True
```
**Symbols:**

```
ffffffff81818e50-ffffffff81818e8c: quirk_iommu_igfx (STB_LOCAL)
ffffffff81cff47e-ffffffff81cff495: quirk_iommu_igfx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195a01a)
Location: drivers/iommu/intel/iommu.c:4931
Inline: True
```
**Symbols:**

```
ffffffff8195a000-ffffffff8195a03a: quirk_iommu_igfx (STB_LOCAL)
ffffffff81ec7c63-ffffffff81ec7c84: quirk_iommu_igfx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1600)
Location: drivers/iommu/intel/iommu.c:4822
Inline: True
```
**Symbols:**

```
ffffffff81ac1600-ffffffff81ac167d: quirk_iommu_igfx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0e000)
Location: drivers/iommu/intel/iommu.c:4780
Inline: True
```
**Symbols:**

```
ffffffff81b0e000-ffffffff81b0e081: quirk_iommu_igfx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b62a60)
Location: drivers/iommu/intel/iommu.c:4906
Inline: True
```
**Symbols:**

```
ffffffff81b62a60-ffffffff81b62ae1: quirk_iommu_igfx (STB_LOCAL)
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
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4d41)
Location: drivers/iommu/intel-iommu.c:5994
Inline: False
```
**Symbols:**

```
ffffffff816b4d41-ffffffff816b4d69: quirk_iommu_igfx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692981)
Location: drivers/iommu/intel-iommu.c:5994
Inline: False
```
**Symbols:**

```
ffffffff81692981-ffffffff816929a9: quirk_iommu_igfx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e3211)
Location: drivers/iommu/intel-iommu.c:5994
Inline: False
```
**Symbols:**

```
ffffffff816e3211-ffffffff816e3239: quirk_iommu_igfx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void quirk_iommu_igfx(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd8a1)
Location: drivers/iommu/intel-iommu.c:5994
Inline: False
```
**Symbols:**

```
ffffffff816fd8a1-ffffffff816fd8c9: quirk_iommu_igfx (STB_LOCAL)
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
