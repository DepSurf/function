# Function: <code>report_normal_detected</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815483d0)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff815483d0-ffffffff815483e8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81578490)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff81578490-ffffffff815784a8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81599c10)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff81599c10-ffffffff81599c28: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81639290)
Location: drivers/pci/pcie/err.c:87
Inline: False
```
**Symbols:**

```
ffffffff81639290-ffffffff816392a8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81660075)
Location: drivers/pci/pcie/err.c:87
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff8165fdb0-ffffffff8165fdc8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81642560)
Location: drivers/pci/pcie/err.c:87
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff816422a0-ffffffff816422b8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff816b327d)
Location: drivers/pci/pcie/err.c:87
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff816b2f80-ffffffff816b2f98: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff817dbc58)
Location: drivers/pci/pcie/err.c:89
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff817db930-ffffffff817db952: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff818fda31)
Location: drivers/pci/pcie/err.c:93
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff818fd650-ffffffff818fd672: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81940ede)
Location: drivers/pci/pcie/err.c:93
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81940ae0-ffffffff81940b02: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8198a13e)
Location: drivers/pci/pcie/err.c:93
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81989d40-ffffffff81989d62: report_normal_detected (STB_LOCAL)
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
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffff800010701490)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffff800010701490-ffff8000107014c8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (c0899100)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
c0899100-c0899124: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffe0004d0132)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffe0004d0132-ffffffe0004d0166: report_normal_detected (STB_LOCAL)
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
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158daa0)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff8158daa0-ffffffff8158dab8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8157c5e0)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff8157c5e0-ffffffff8157c5f8: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158d960)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff8158d960-ffffffff8158d978: report_normal_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int report_normal_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815a7e10)
Location: drivers/pci/pcie/err.c:83
Inline: False
```
**Symbols:**

```
ffffffff815a7e10-ffffffff815a7e28: report_normal_detected (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
