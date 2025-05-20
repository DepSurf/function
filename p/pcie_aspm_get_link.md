# Function: <code>pcie_aspm_get_link</code>

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
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81599f30)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff81599f30-ffffffff81599f7a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8163b185)
Location: drivers/pci/pcie/aspm.c:1070
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff81639650-ffffffff8163969a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816619d5)
Location: drivers/pci/pcie/aspm.c:1062
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff81660620-ffffffff8166066a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816435c5)
Location: drivers/pci/pcie/aspm.c:1062
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff81642b00-ffffffff81642b4a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816b4315)
Location: drivers/pci/pcie/aspm.c:1062
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff816b3800-ffffffff816b384a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff817d7875)
Location: drivers/pci/pcie/aspm.c:1098
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff818f8e95)
Location: drivers/pci/pcie/aspm.c:1060
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8193c225)
Location: drivers/pci/pcie/aspm.c:1024
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81986095)
Location: drivers/pci/pcie/aspm.c:1049
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
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
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010701800)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffff800010701800-ffff80001070186c: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c0899430)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
c0899430-c0899494: pcie_aspm_get_link (STB_LOCAL)
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
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d04f4)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffe0004d04f4-ffffffe0004d054e: pcie_aspm_get_link (STB_LOCAL)
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
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158ddc0)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff8158ddc0-ffffffff8158de0a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157c900)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff8157c900-ffffffff8157c94a: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158dc80)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff8158dc80-ffffffff8158dcca: pcie_aspm_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pcie_link_state *pcie_aspm_get_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815a8130)
Location: drivers/pci/pcie/aspm.c:1079
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
**Symbols:**

```
ffffffff815a8130-ffffffff815a817a: pcie_aspm_get_link (STB_LOCAL)
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
