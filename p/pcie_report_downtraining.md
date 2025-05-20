# Function: <code>pcie_report_downtraining</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c288)
Location: drivers/pci/probe.c:2325
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ab00)
Location: drivers/pci/probe.c:2551
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8155ab00-ffffffff8155ab3c: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157bb90)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8157bb90-ffffffff8157bbcc: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81621310)
Location: drivers/pci/probe.c:2357
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81621310-ffffffff8162134c: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81647e80)
Location: drivers/pci/probe.c:2364
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81647e80-ffffffff81647ebc: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162aac0)
Location: drivers/pci/probe.c:2408
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8162aac0-ffffffff8162aafa: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81699fa0)
Location: drivers/pci/probe.c:2452
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81699fa0-ffffffff81699fda: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bb5c0)
Location: drivers/pci/probe.c:2427
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff817bb5c0-ffffffff817bb612: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d70b0)
Location: drivers/pci/probe.c:2439
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff818d70b0-ffffffff818d7102: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a330)
Location: drivers/pci/probe.c:2450
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8191a330-ffffffff8191a382: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81962730)
Location: drivers/pci/probe.c:2499
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81962730-ffffffff81962782: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df140)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffff8000106df140-ffff8000106df1ac: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087ade4)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c087ade4-c087ae38: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857710)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c000000000857710-c000000000857784: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b71cc)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffe0004b71cc-ffffffe0004b722e: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815700b0)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff815700b0-ffffffff815700ec: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155e810)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8155e810-ffffffff8155e84c: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156f8e0)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8156f8e0-ffffffff8156f91c: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pcie_report_downtraining(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81589dc0)
Location: drivers/pci/probe.c:2289
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81589dc0-ffffffff81589dfc: pcie_report_downtraining (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
