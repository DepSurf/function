# Function: <code>pcie_cap_has_rtctl</code>

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
In drivers/pci/access.c (ffffffff8142e297)
Location: drivers/pci/access.c:601
Inline: True
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
In drivers/pci/access.c (ffffffff81479867)
Location: drivers/pci/access.c:712
Inline: True
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
In drivers/pci/access.c (ffffffff8149acf7)
Location: drivers/pci/access.c:724
Inline: True
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
In drivers/pci/access.c (ffffffff814a4a87)
Location: drivers/pci/access.c:734
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
In drivers/pci/access.c (ffffffff814e3861)
Location: drivers/pci/access.c:734
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
In drivers/pci/access.c (ffffffff81513248)
Location: drivers/pci/access.c:367
Inline: True
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
In drivers/pci/access.c (ffffffff8152893c)
Location: drivers/pci/access.c:367
Inline: True
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
In drivers/pci/access.c (ffffffff81557c39)
Location: drivers/pci/access.c:367
Inline: True
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
In drivers/pci/access.c (ffffffff81579250)
Location: drivers/pci/access.c:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e2e8)
Location: drivers/pci/access.c:354
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff8161ec60-ffffffff8161ec83: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644b08)
Location: drivers/pci/access.c:354
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff81645490-ffffffff816454b3: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816277af)
Location: drivers/pci/access.c:354
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff816281e0-ffffffff816281fd: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816970af)
Location: drivers/pci/access.c:354
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff81697ae0-ffffffff81697afd: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b881a)
Location: drivers/pci/access.c:359
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_reg_implemented
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff817b8cd0-ffffffff817b8cf6: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d32c2)
Location: drivers/pci/access.c:364
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_reg_implemented
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff818d3760-ffffffff818d3786: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819162b0)
Location: drivers/pci/access.c:364
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_reg_implemented
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff81916890-ffffffff819168b6: pcie_cap_has_rtctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pcie_cap_has_rtctl(const struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e2e0)
Location: drivers/pci/access.c:364
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_reg_implemented
Direct callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
```
**Symbols:**

```
ffffffff8195e8b0-ffffffff8195e8d6: pcie_cap_has_rtctl (STB_GLOBAL)
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
In drivers/pci/access.c (ffff8000106da6d0)
Location: drivers/pci/access.c:358
Inline: True
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
In drivers/pci/access.c (c0877de0)
Location: drivers/pci/access.c:358
Inline: True
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
In drivers/pci/access.c (c000000000852e40)
Location: drivers/pci/access.c:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3f0a)
Location: drivers/pci/access.c:358
Inline: True
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
In drivers/pci/access.c (ffffffff8156d770)
Location: drivers/pci/access.c:358
Inline: True
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
In drivers/pci/access.c (ffffffff8155bee0)
Location: drivers/pci/access.c:358
Inline: True
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
In drivers/pci/access.c (ffffffff8156cfa0)
Location: drivers/pci/access.c:358
Inline: True
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
In drivers/pci/access.c (ffffffff81587aa0)
Location: drivers/pci/access.c:358
Inline: True
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
