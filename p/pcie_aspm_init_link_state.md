# Function: <code>pcie_aspm_init_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81447c20)
Location: drivers/pci/pcie/aspm.c:551
Inline: False
```
**Symbols:**

```
ffffffff81447c20-ffffffff81448416: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81493db0)
Location: drivers/pci/pcie/aspm.c:551
Inline: False
```
**Symbols:**

```
ffffffff81493db0-ffffffff8149460d: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814b5740)
Location: drivers/pci/pcie/aspm.c:572
Inline: False
```
**Symbols:**

```
ffffffff814b5740-ffffffff814b5ff1: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814c0020)
Location: drivers/pci/pcie/aspm.c:834
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff814c0020-ffffffff814c097c: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815003a0)
Location: drivers/pci/pcie/aspm.c:868
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff815003a0-ffffffff81500dae: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81531f80)
Location: drivers/pci/pcie/aspm.c:893
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81531f80-ffffffff81532b26: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815493d0)
Location: drivers/pci/pcie/aspm.c:888
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff815493d0-ffffffff81549f3c: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:903
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8157a3d8-ffffffff8157a3fc: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff81579c90-ffffffff81579fe0: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8159be14-ffffffff8159be36: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff8159b750-ffffffff8159baee: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:906
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8163b93f-ffffffff8163b964: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff8163b210-ffffffff8163b4fc: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:898
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81bf9107-ffffffff81bf912c: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff81662270-ffffffff8166255c: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:898
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81beaf3f-ffffffff81beaf62: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff81644620-ffffffff816449c6: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:898
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81ce5e7f-ffffffff81ce5eb7: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff816b53c0-ffffffff816b5780: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:934
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81eac8d8-ffffffff81eac910: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff817d8d10-ffffffff817d90e2: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8208f566-ffffffff8208f57b: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff818fa4c0-ffffffff818fa8bc: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:876
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8210f911-ffffffff8210f926: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff8193d9d0-ffffffff8193ddbe: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:877
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff821ed5a7-ffffffff821ed5bc: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff819868a0-ffffffff81986cbd: pcie_aspm_init_link_state (STB_GLOBAL)
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
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010703360)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffff800010703360-ffff800010703710: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c089ac58)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
c089ac58-c089b008: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/pci.h:542
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d1d06)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffe0004d1d06-ffffffe0004d2020: pcie_aspm_init_link_state (STB_GLOBAL)
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
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8158fca4-ffffffff8158fcc6: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff8158f5e0-ffffffff8158f97e: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8157e7e4-ffffffff8157e806: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff8157e120-ffffffff8157e4be: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8158fb64-ffffffff8158fb86: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff8158f4a0-ffffffff8158f83e: pcie_aspm_init_link_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_init_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:915
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff815aa014-ffffffff815aa036: pcie_aspm_init_link_state.cold (STB_LOCAL)
ffffffff815a9950-ffffffff815a9cee: pcie_aspm_init_link_state (STB_GLOBAL)
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
