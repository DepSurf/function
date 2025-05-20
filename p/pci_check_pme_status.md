# Function: <code>pci_check_pme_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436ed0)
Location: drivers/pci/pci.c:1643
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff81436ed0-ffffffff81436f69: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482a60)
Location: drivers/pci/pci.c:1664
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff81482a60-ffffffff81482afa: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3ff0)
Location: drivers/pci/pci.c:1689
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff814a3ff0-ffffffff814a408a: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae000)
Location: drivers/pci/pci.c:1687
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff814ae000-ffffffff814ae08d: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed3e0)
Location: drivers/pci/pci.c:1690
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff814ed3e0-ffffffff814ed46d: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d020)
Location: drivers/pci/pci.c:1754
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff8151d020-ffffffff8151d0ad: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532720)
Location: drivers/pci/pci.c:1927
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff81532720-ffffffff815327ad: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561df0)
Location: drivers/pci/pci.c:2000
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff81561df0-ffffffff81561e82: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582f90)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff81582f90-ffffffff81583022: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627b63)
Location: drivers/pci/pci.c:2066
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff81629be0-ffffffff81629c72: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164d803)
Location: drivers/pci/pci.c:2210
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff81650010-ffffffff816500a2: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81630393)
Location: drivers/pci/pci.c:2240
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff81632bd0-ffffffff81632c62: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a0073)
Location: drivers/pci/pci.c:2271
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff816a2d40-ffffffff816a2dd2: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4e70)
Location: drivers/pci/pci.c:2333
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff817c4e70-ffffffff817c4f10: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1ed0)
Location: drivers/pci/pci.c:2307
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff818e1ed0-ffffffff818e1f70: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925310)
Location: drivers/pci/pci.c:2345
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff81925310-ffffffff819253b0: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d9e0)
Location: drivers/pci/pci.c:2442
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
**Symbols:**

```
ffffffff8196d9e0-ffffffff8196da80: pci_check_pme_status (STB_GLOBAL)
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
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6db0)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffff8000106e6db0-ffff8000106e6e54: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c088201c)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
c088201c-c08820c4: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008612d0)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
**Symbols:**

```
c0000000008612d0-c0000000008613c4: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd6b8)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_wakeup
  - drivers/pci/pci.c:pci_pme_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffe0004bd6b8-ffffffe0004bd744: pci_check_pme_status (STB_GLOBAL)
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
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815774b0)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff815774b0-ffffffff81577542: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565c10)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff81565c10-ffffffff81565ca2: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576ce0)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff81576ce0-ffffffff81576d72: pci_check_pme_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_check_pme_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815911c0)
Location: drivers/pci/pci.c:1996
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
**Symbols:**

```
ffffffff815911c0-ffffffff81591252: pci_check_pme_status (STB_GLOBAL)
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
