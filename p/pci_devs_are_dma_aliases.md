# Function: <code>pci_devs_are_dma_aliases</code>

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
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81484730)
Location: drivers/pci/pci.c:4915
Inline: False
```
**Symbols:**

```
ffffffff81484730-ffffffff81484767: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5e20)
Location: drivers/pci/pci.c:4923
Inline: False
```
**Symbols:**

```
ffffffff814a5e20-ffffffff814a5e57: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814afd50)
Location: drivers/pci/pci.c:5081
Inline: False
```
**Symbols:**

```
ffffffff814afd50-ffffffff814afd85: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ef280)
Location: drivers/pci/pci.c:5105
Inline: False
```
**Symbols:**

```
ffffffff814ef280-ffffffff814ef2b5: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151f360)
Location: drivers/pci/pci.c:5485
Inline: False
```
**Symbols:**

```
ffffffff8151f360-ffffffff8151f397: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81535300)
Location: drivers/pci/pci.c:5796
Inline: False
```
**Symbols:**

```
ffffffff81535300-ffffffff81535337: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564630)
Location: drivers/pci/pci.c:5892
Inline: False
```
**Symbols:**

```
ffffffff81564630-ffffffff81564665: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585930)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffffffff81585930-ffffffff81585965: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c570)
Location: drivers/pci/pci.c:6073
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff8162c570-ffffffff8162c5e0: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816522d0)
Location: drivers/pci/pci.c:6147
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff816522d0-ffffffff81652340: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634d80)
Location: drivers/pci/pci.c:6196
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81634d80-ffffffff81634df0: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4e70)
Location: drivers/pci/pci.c:6386
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff816a4e70-ffffffff816a4ee0: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c7370)
Location: drivers/pci/pci.c:6483
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff817c7370-ffffffff817c73e5: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4950)
Location: drivers/pci/pci.c:6430
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff818e4950-ffffffff818e49c5: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927f90)
Location: drivers/pci/pci.c:6552
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81927f90-ffffffff81928005: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970730)
Location: drivers/pci/pci.c:6696
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81970730-ffffffff819707a5: pci_devs_are_dma_aliases (STB_GLOBAL)
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
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106ea2e0)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffff8000106ea2e0-ffff8000106ea374: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c088528c)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
c088528c-c0885318: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008655e0)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
c0000000008655e0-c00000000086565c: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004c0472)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffffffe0004c0472-ffffffe0004c04ee: pci_devs_are_dma_aliases (STB_GLOBAL)
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
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579e50)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffffffff81579e50-ffffffff81579e85: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81568590)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffffffff81568590-ffffffff815685c5: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579680)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffffffff81579680-ffffffff815796b5: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_devs_are_dma_aliases(struct pci_dev *dev1, struct pci_dev *dev2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593b10)
Location: drivers/pci/pci.c:6052
Inline: False
```
**Symbols:**

```
ffffffff81593b10-ffffffff81593b45: pci_devs_are_dma_aliases (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
