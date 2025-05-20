# Function: <code>pcie_aer_is_native</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163c2e4)
Location: drivers/pci/pcie/aer.c:215
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8163c650-ffffffff8163c699: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816639c3)
Location: drivers/pci/pcie/aer.c:215
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81663600-ffffffff81663649: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81645e73)
Location: drivers/pci/pcie/aer.c:215
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81645ac0-ffffffff81645b09: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:215
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81ce6095-ffffffff81ce60a9: pcie_aer_is_native.cold (STB_LOCAL)
ffffffff816b6680-ffffffff816b66d7: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:220
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81eacb7b-ffffffff81eacb8f: pcie_aer_is_native.cold (STB_LOCAL)
ffffffff817da1c0-ffffffff817da227: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:220
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8208f5f5-ffffffff8208f609: pcie_aer_is_native.cold (STB_LOCAL)
ffffffff818fbc80-ffffffff818fbce7: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:223
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8210f980-ffffffff8210f994: pcie_aer_is_native.cold (STB_LOCAL)
ffffffff8193f550-ffffffff8193f5b7: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pcie_aer_is_native(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff821ed5e6-ffffffff821ed5fa: pcie_aer_is_native.cold (STB_LOCAL)
ffffffff81987a20-ffffffff81987a87: pcie_aer_is_native (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
