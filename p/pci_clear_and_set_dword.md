# Function: <code>pci_clear_and_set_dword</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814bf4b0)
Location: drivers/pci/pcie/aspm.c:597
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff814bf4b0-ffffffff814bf520: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814ff830)
Location: drivers/pci/pcie/aspm.c:622
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff814ff830-ffffffff814ff8a0: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815313f0)
Location: drivers/pci/pcie/aspm.c:647
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff815313f0-ffffffff81531460: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81548890)
Location: drivers/pci/pcie/aspm.c:645
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff81548890-ffffffff81548900: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815789d0)
Location: drivers/pci/pcie/aspm.c:660
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff815789d0-ffffffff81578a40: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8159a1e0)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff8159a1e0-ffffffff8159a250: pci_clear_and_set_dword (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffffffff8163a59f)
Location: drivers/pci/pcie/aspm.c:655
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
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
In drivers/pci/pcie/aspm.c (ffffffff81660e71)
Location: drivers/pci/pcie/aspm.c:440
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
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
In drivers/pci/pcie/aspm.c (ffffffff816437da)
Location: drivers/pci/pcie/aspm.c:440
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff816b456a)
Location: drivers/pci/pcie/aspm.c:440
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff817d7c61)
Location: drivers/pci/pcie/aspm.c:447
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff818f92a1)
Location: drivers/pci/pcie/aspm.c:462
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8193c649)
Location: drivers/pci/pcie/aspm.c:426
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010701b20)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffff800010701b20-ffff800010701bb0: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c089970c)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
c089970c-c0899790: pci_clear_and_set_dword (STB_LOCAL)
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
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d0884)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffe0004d0884-ffffffe0004d08e6: pci_clear_and_set_dword (STB_LOCAL)
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
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158e070)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff8158e070-ffffffff8158e0e0: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157cbb0)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff8157cbb0-ffffffff8157cc20: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158df30)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff8158df30-ffffffff8158dfa0: pci_clear_and_set_dword (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_clear_and_set_dword(struct pci_dev *pdev, int pos, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815a83e0)
Location: drivers/pci/pcie/aspm.c:664
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff815a83e0-ffffffff815a8450: pci_clear_and_set_dword (STB_LOCAL)
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
