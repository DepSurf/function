# Function: <code>pcie_retrain_link</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81579666)
Location: drivers/pci/pcie/aspm.c:199
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8159aeba)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81639ba0)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
```
**Symbols:**

```
ffffffff81639ba0-ffffffff81639c82: pcie_retrain_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81660a50)
Location: drivers/pci/pcie/aspm.c:195
Inline: True
```
**Symbols:**

```
ffffffff81660a50-ffffffff81660b32: pcie_retrain_link.isra.0 (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffffffff81642f86)
Location: drivers/pci/pcie/aspm.c:195
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
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
In drivers/pci/pcie/aspm.c (ffffffff816b3cd6)
Location: drivers/pci/pcie/aspm.c:195
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
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
In drivers/pci/pcie/aspm.c (ffffffff817d72cd)
Location: drivers/pci/pcie/aspm.c:195
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
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
In drivers/pci/pcie/aspm.c (ffffffff818f882f)
Location: drivers/pci/pcie/aspm.c:196
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcie_retrain_link(struct pci_dev *pdev, bool use_lt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81926c80)
Location: drivers/pci/pci.c:4932
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
```
**Symbols:**

```
ffffffff81926c80-ffffffff81926d16: pcie_retrain_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcie_retrain_link(struct pci_dev *pdev, bool use_lt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196f420)
Location: drivers/pci/pci.c:5042
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
```
**Symbols:**

```
ffffffff8196f420-ffffffff8196f4b6: pcie_retrain_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff8000107028e8)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c089a360)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d12fe)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158ed4a)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157d88a)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158ec0a)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815a90ba)
Location: drivers/pci/pcie/aspm.c:203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
