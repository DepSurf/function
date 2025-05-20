# Function: <code>calc_l1ss_pwron</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814bfe40)
Location: drivers/pci/pcie/aspm.c:320
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff814bfe40-ffffffff814bfe87: calc_l1ss_pwron (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815001c0)
Location: drivers/pci/pcie/aspm.c:309
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff815001c0-ffffffff81500207: calc_l1ss_pwron (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81531da0)
Location: drivers/pci/pcie/aspm.c:326
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81531da0-ffffffff81531de5: calc_l1ss_pwron (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81549380)
Location: drivers/pci/pcie/aspm.c:324
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81549380-ffffffff815493c5: calc_l1ss_pwron (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157a345)
Location: drivers/pci/pcie/aspm.c:339
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81579500-ffffffff8157952b: calc_l1ss_pwron (STB_LOCAL)
ffffffff8157a345-ffffffff8157a368: calc_l1ss_pwron.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8159bd65)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff8159acc0-ffffffff8159aceb: calc_l1ss_pwron (STB_LOCAL)
ffffffff8159bd65-ffffffff8159bd88: calc_l1ss_pwron.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8163a04b)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81661ae9)
Location: drivers/pci/pcie/aspm.c:339
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81643eba)
Location: drivers/pci/pcie/aspm.c:339
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816b4c5a)
Location: drivers/pci/pcie/aspm.c:339
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
In drivers/pci/pcie/aspm.c (ffffffff817d84cc)
Location: drivers/pci/pcie/aspm.c:339
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
In drivers/pci/pcie/aspm.c (ffffffff818f9baf)
Location: drivers/pci/pcie/aspm.c:340
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff8000107026a8)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffff8000107026a8-ffff800010702740: calc_l1ss_pwron (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c089a130)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
c089a130-c089a1a0: calc_l1ss_pwron (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d1122)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffe0004d1122-ffffffe0004d11b2: calc_l1ss_pwron (STB_LOCAL)
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
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158fbf5)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff8158eb50-ffffffff8158eb7b: calc_l1ss_pwron (STB_LOCAL)
ffffffff8158fbf5-ffffffff8158fc18: calc_l1ss_pwron.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157e735)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff8157d690-ffffffff8157d6bb: calc_l1ss_pwron (STB_LOCAL)
ffffffff8157e735-ffffffff8157e758: calc_l1ss_pwron.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158fab5)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff8158ea10-ffffffff8158ea3b: calc_l1ss_pwron (STB_LOCAL)
ffffffff8158fab5-ffffffff8158fad8: calc_l1ss_pwron.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 calc_l1ss_pwron(struct pci_dev *pdev, u32 scale, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815a9f65)
Location: drivers/pci/pcie/aspm.c:343
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff815a8ec0-ffffffff815a8eeb: calc_l1ss_pwron (STB_LOCAL)
ffffffff815a9f65-ffffffff815a9f88: calc_l1ss_pwron.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
