# Function: <code>alloc_pcie_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81447d49)
Location: drivers/pci/pcie/aspm.c:514
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81493edd)
Location: drivers/pci/pcie/aspm.c:514
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814b586d)
Location: drivers/pci/pcie/aspm.c:528
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814c0143)
Location: drivers/pci/pcie/aspm.c:789
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff815004c3)
Location: drivers/pci/pcie/aspm.c:819
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8153209a)
Location: drivers/pci/pcie/aspm.c:844
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815494f0)
Location: drivers/pci/pcie/aspm.c:842
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81579dc1)
Location: drivers/pci/pcie/aspm.c:857
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8159b881)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pcie_link_state *alloc_pcie_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816399f0)
Location: drivers/pci/pcie/aspm.c:852
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff816399f0-ffffffff81639acf: alloc_pcie_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pcie_link_state *alloc_pcie_link_state(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816608a0)
Location: drivers/pci/pcie/aspm.c:844
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff816608a0-ffffffff8166097f: alloc_pcie_link_state (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffffffff81644755)
Location: drivers/pci/pcie/aspm.c:844
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff816b54ec)
Location: drivers/pci/pcie/aspm.c:844
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff817d8e46)
Location: drivers/pci/pcie/aspm.c:880
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff818fa5fd)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8193db1b)
Location: drivers/pci/pcie/aspm.c:822
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff819869eb)
Location: drivers/pci/pcie/aspm.c:823
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffff8000107034bc)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (c089ad90)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffe0004d1e0e)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8158f711)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8157e251)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8158f5d1)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff815a9a81)
Location: drivers/pci/pcie/aspm.c:861
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
