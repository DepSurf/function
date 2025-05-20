# Function: <code>pcie_wait_for_link</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e6e0)
Location: drivers/pci/pci.c:4248
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff8151e6e0-ffffffff8151e796: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534470)
Location: drivers/pci/pci.c:4520
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81534470-ffffffff8153457d: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4617
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81564db2-ffffffff81564ddb: pcie_wait_for_link.cold (STB_LOCAL)
ffffffff81563940-ffffffff81563a2b: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81584b00)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81584b00-ffffffff81584b19: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162b720)
Location: drivers/pci/pci.c:4697
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff8162b720-ffffffff8162b739: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651420)
Location: drivers/pci/pci.c:4770
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81651420-ffffffff81651439: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633ea0)
Location: drivers/pci/pci.c:4819
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81633ea0-ffffffff81633eb9: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4080)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff816a4080-ffffffff816a4099: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6460)
Location: drivers/pci/pci.c:4967
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff817c6460-ffffffff817c6483: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e3820)
Location: drivers/pci/pci.c:4910
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff818e3820-ffffffff818e3843: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81926d30)
Location: drivers/pci/pci.c:5016
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81926d30-ffffffff81926dcf: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196f4d0)
Location: drivers/pci/pci.c:5126
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff8196f4d0-ffffffff8196f56f: pcie_wait_for_link (STB_GLOBAL)
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
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9138)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffff8000106e9138-ffff8000106e9170: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08840f4)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
**Symbols:**

```
c08840f4-c0884114: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000863f70)
Location: drivers/pci/pci.c:4667
Inline: False
```
**Symbols:**

```
c000000000863f70-c000000000863f88: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf538)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffe0004bf538-ffffffe0004bf56e: pcie_wait_for_link (STB_GLOBAL)
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
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579020)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81579020-ffffffff81579039: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567760)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81567760-ffffffff81567779: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578850)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81578850-ffffffff81578869: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pcie_wait_for_link(struct pci_dev *pdev, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81592d10)
Location: drivers/pci/pci.c:4667
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffff81592d10-ffffffff81592d29: pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
