# Function: <code>pcie_has_flr</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af6ce)
Location: drivers/pci/pci.c:3881
Inline: True
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
In drivers/pci/pci.c (ffffffff814eebee)
Location: drivers/pci/pci.c:3918
Inline: True
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
In drivers/pci/pci.c (ffffffff8151ece7)
Location: drivers/pci/pci.c:4119
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534c77)
Location: drivers/pci/pci.c:4384
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81530ed0-ffffffff81530f19: pcie_has_flr.part.30 (STB_LOCAL)
ffffffff81530f20-ffffffff81530f3c: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564128)
Location: drivers/pci/pci.c:4481
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81560810-ffffffff81560859: pcie_has_flr.part.0 (STB_LOCAL)
ffffffff81560860-ffffffff8156087c: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585408)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81581930-ffffffff81581979: pcie_has_flr.part.0 (STB_LOCAL)
ffffffff81581980-ffffffff8158199c: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162bf11)
Location: drivers/pci/pci.c:4507
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff816261d0-ffffffff81626222: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651c41)
Location: drivers/pci/pci.c:4582
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff8164bee0-ffffffff8164bf32: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634731)
Location: drivers/pci/pci.c:4631
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff8162eb60-ffffffff8162ebb2: pcie_has_flr (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9b18)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffff8000106e4a80-ffff8000106e4ae0: pcie_has_flr.part.0 (STB_LOCAL)
ffff8000106e4ae0-ffff8000106e4b28: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c0884abc)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c08807a0-c0880804: pcie_has_flr.part.0 (STB_LOCAL)
c0880804-c0880838: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c000000000864be0)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c00000000085f270-c00000000085f2dc: pcie_has_flr.part.0 (STB_LOCAL)
c00000000085f2e0-c00000000085f314: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bfe00)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffe0004bbe92-ffffffe0004bbecc: pcie_has_flr.part.0 (STB_LOCAL)
ffffffe0004bbecc-ffffffe0004bbf02: pcie_has_flr (STB_GLOBAL)
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
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579928)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81575e50-ffffffff81575e99: pcie_has_flr.part.0 (STB_LOCAL)
ffffffff81575ea0-ffffffff81575ebc: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81568068)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815645b0-ffffffff815645f9: pcie_has_flr.part.0 (STB_LOCAL)
ffffffff81564600-ffffffff8156461c: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579158)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81575680-ffffffff815756c9: pcie_has_flr.part.0 (STB_LOCAL)
ffffffff815756d0-ffffffff815756ec: pcie_has_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pcie_has_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815935f0)
Location: drivers/pci/pci.c:4477
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8158fc50-ffffffff8158fc99: pcie_has_flr.part.0 (STB_LOCAL)
ffffffff8158fca0-ffffffff8158fcbc: pcie_has_flr (STB_GLOBAL)
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
