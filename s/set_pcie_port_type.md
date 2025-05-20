# Function: <code>set_pcie_port_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81430e20)
Location: drivers/pci/probe.c:1026
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81430e20-ffffffff81430f1d: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147c5b0)
Location: drivers/pci/probe.c:1043
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8147c5b0-ffffffff8147c6ab: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149db10)
Location: drivers/pci/probe.c:1162
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8149db10-ffffffff8149dc0c: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a79c0)
Location: drivers/pci/probe.c:1188
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff814a79c0-ffffffff814a7ab4: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e6310)
Location: drivers/pci/probe.c:1230
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff814e6310-ffffffff814e6404: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81515790)
Location: drivers/pci/probe.c:1314
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81515790-ffffffff81515884: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152aeb0)
Location: drivers/pci/probe.c:1314
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8152aeb0-ffffffff8152afa4: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155a1f0)
Location: drivers/pci/probe.c:1417
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8155a1f0-ffffffff8155a2e4: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8157dc4b-ffffffff8157dc95: set_pcie_port_type.cold (STB_LOCAL)
ffffffff8157b260-ffffffff8157b373: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1467
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81623363-ffffffff816233ad: set_pcie_port_type.cold (STB_LOCAL)
ffffffff81620e00-ffffffff81620f13: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1486
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81bf7549-ffffffff81bf7593: set_pcie_port_type.cold (STB_LOCAL)
ffffffff816474a0-ffffffff816475b7: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1529
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81be9315-ffffffff81be935f: set_pcie_port_type.cold (STB_LOCAL)
ffffffff81629da0-ffffffff81629eac: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1538
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81ce3745-ffffffff81ce378f: set_pcie_port_type.cold (STB_LOCAL)
ffffffff816997a0-ffffffff816998af: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1519
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81eaa2ae-ffffffff81eaa2f8: set_pcie_port_type.cold (STB_LOCAL)
ffffffff817bad60-ffffffff817bae87: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d61b0)
Location: drivers/pci/probe.c:1525
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff818d61b0-ffffffff818d6317: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819193f0)
Location: drivers/pci/probe.c:1528
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff819193f0-ffffffff81919581: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81961770)
Location: drivers/pci/probe.c:1539
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81961770-ffffffff81961901: set_pcie_port_type (STB_GLOBAL)
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
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106de050)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffff8000106de050-ffff8000106de1a8: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0879c9c)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
c0879c9c-c0879df4: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000856670)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
c000000000856670-c000000000856810: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b62dc)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffe0004b62dc-ffffffe0004b63fa: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8157216b-ffffffff815721b5: set_pcie_port_type.cold (STB_LOCAL)
ffffffff8156f780-ffffffff8156f893: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff815608cb-ffffffff81560915: set_pcie_port_type.cold (STB_LOCAL)
ffffffff8155dee0-ffffffff8155dff3: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8157199b-ffffffff815719e5: set_pcie_port_type.cold (STB_LOCAL)
ffffffff8156efb0-ffffffff8156f0c3: set_pcie_port_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void set_pcie_port_type(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1419
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8158be7b-ffffffff8158bec5: set_pcie_port_type.cold (STB_LOCAL)
ffffffff81589490-ffffffff815895a3: set_pcie_port_type (STB_GLOBAL)
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
