# Function: <code>calgary_handle_quirks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f76792)
Location: arch/x86/kernel/pci-calgary_64.c:971
Inline: False
```
**Symbols:**

```
ffffffff81f76792-ffffffff81f7681e: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9eee0)
Location: arch/x86/kernel/pci-calgary_64.c:971
Inline: False
```
**Symbols:**

```
ffffffff81f9eee0-ffffffff81f9ef6c: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda442)
Location: arch/x86/kernel/pci-calgary_64.c:971
Inline: False
```
**Symbols:**

```
ffffffff81fda442-ffffffff81fda4ce: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb2c1)
Location: arch/x86/kernel/pci-calgary_64.c:980
Inline: True
```
**Symbols:**

```
ffffffff820bb2c1-ffffffff820bb34b: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c1ca2)
Location: arch/x86/kernel/pci-calgary_64.c:979
Inline: True
```
**Symbols:**

```
ffffffff826c1ca2-ffffffff826c1d2d: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ebe9f)
Location: arch/x86/kernel/pci-calgary_64.c:978
Inline: False
```
**Symbols:**

```
ffffffff826ebe9f-ffffffff826ebf0a: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a2aa1)
Location: arch/x86/kernel/pci-calgary_64.c:962
Inline: False
```
**Symbols:**

```
ffffffff828a2aa1-ffffffff828a2b0c: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828badac)
Location: arch/x86/kernel/pci-calgary_64.c:950
Inline: False
```
**Symbols:**

```
ffffffff828badac-ffffffff828bae18: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c126e)
Location: arch/x86/kernel/pci-calgary_64.c:952
Inline: False
```
**Symbols:**

```
ffffffff828c126e-ffffffff828c12da: calgary_handle_quirks (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac244)
Location: arch/x86/kernel/pci-calgary_64.c:952
Inline: False
```
**Symbols:**

```
ffffffff828ac244-ffffffff828ac2b0: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a450b)
Location: arch/x86/kernel/pci-calgary_64.c:952
Inline: False
```
**Symbols:**

```
ffffffff828a450b-ffffffff828a4577: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf143)
Location: arch/x86/kernel/pci-calgary_64.c:952
Inline: False
```
**Symbols:**

```
ffffffff828bf143-ffffffff828bf1af: calgary_handle_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void calgary_handle_quirks(struct iommu_table *tbl, struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c2290)
Location: arch/x86/kernel/pci-calgary_64.c:952
Inline: False
```
**Symbols:**

```
ffffffff828c2290-ffffffff828c22fc: calgary_handle_quirks (STB_LOCAL)
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
