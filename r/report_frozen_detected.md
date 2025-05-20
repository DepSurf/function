# Function: <code>report_frozen_detected</code>

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
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815483f0)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff815483f0-ffffffff81548408: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815784b0)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff815784b0-ffffffff815784c8: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81599c30)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff81599c30-ffffffff81599c48: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff816392b0)
Location: drivers/pci/pcie/err.c:82
Inline: False
```
**Symbols:**

```
ffffffff816392b0-ffffffff816392c8: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81660206)
Location: drivers/pci/pcie/err.c:82
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff8165fdd0-ffffffff8165fde8: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff816426fd)
Location: drivers/pci/pcie/err.c:82
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff816422c0-ffffffff816422d8: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff816b33fd)
Location: drivers/pci/pcie/err.c:82
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff816b2fa0-ffffffff816b2fb8: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff817dbdd7)
Location: drivers/pci/pcie/err.c:84
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff817db960-ffffffff817db982: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff818fdb8a)
Location: drivers/pci/pcie/err.c:88
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff818fd690-ffffffff818fd6b2: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81941033)
Location: drivers/pci/pcie/err.c:88
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81940b20-ffffffff81940b42: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8198a293)
Location: drivers/pci/pcie/err.c:88
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81989d80-ffffffff81989da2: report_frozen_detected (STB_LOCAL)
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
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffff8000107014c8)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffff8000107014c8-ffff800010701500: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (c0899124)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
c0899124-c0899148: report_frozen_detected (STB_LOCAL)
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
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffe0004d0166)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffe0004d0166-ffffffe0004d019a: report_frozen_detected (STB_LOCAL)
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
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158dac0)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff8158dac0-ffffffff8158dad8: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8157c600)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff8157c600-ffffffff8157c618: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158d980)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff8158d980-ffffffff8158d998: report_frozen_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815a7e30)
Location: drivers/pci/pcie/err.c:78
Inline: False
```
**Symbols:**

```
ffffffff815a7e30-ffffffff815a7e48: report_frozen_detected (STB_LOCAL)
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
