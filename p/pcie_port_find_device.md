# Function: <code>pcie_port_find_device</code>

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
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815308c0)
Location: drivers/pci/pcie/portdrv_core.c:456
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
**Symbols:**

```
ffffffff815308c0-ffffffff81530918: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81547600)
Location: drivers/pci/pcie/portdrv_core.c:476
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81547600-ffffffff81547658: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815776f0)
Location: drivers/pci/pcie/portdrv_core.c:484
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff815776f0-ffffffff81577748: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81598e70)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81598e70-ffffffff81598ec8: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff816389a0)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
```
**Symbols:**

```
ffffffff816389a0-ffffffff816389f8: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f4b0)
Location: drivers/pci/pcie/portdrv_core.c:465
Inline: False
```
**Symbols:**

```
ffffffff8165f4b0-ffffffff8165f508: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff816419a0)
Location: drivers/pci/pcie/portdrv_core.c:465
Inline: False
```
**Symbols:**

```
ffffffff816419a0-ffffffff816419f8: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff816b2440)
Location: drivers/pci/pcie/portdrv_core.c:470
Inline: False
```
**Symbols:**

```
ffffffff816b2440-ffffffff816b2498: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff817d5ad0)
Location: drivers/pci/pcie/portdrv_core.c:470
Inline: False
```
**Symbols:**

```
ffffffff817d5ad0-ffffffff817d5b42: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv.c (ffffffff818f6f40)
Location: drivers/pci/pcie/portdrv.c:478
Inline: False
```
**Symbols:**

```
ffffffff818f6f40-ffffffff818f6fb2: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv.c (ffffffff8193a3a0)
Location: drivers/pci/pcie/portdrv.c:478
Inline: False
```
**Symbols:**

```
ffffffff8193a3a0-ffffffff8193a412: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv.c (ffffffff81983200)
Location: drivers/pci/pcie/portdrv.c:479
Inline: False
```
**Symbols:**

```
ffffffff81983200-ffffffff81983272: pcie_port_find_device (STB_GLOBAL)
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
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffff8000107004b8)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffff8000107004b8-ffff80001070052c: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (c08981f8)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
c08981f8-c0898270: pcie_port_find_device (STB_GLOBAL)
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
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf49c)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffe0004cf49c-ffffffe0004cf4e6: pcie_port_find_device (STB_GLOBAL)
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
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cd00)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff8158cd00-ffffffff8158cd58: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157b840)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff8157b840-ffffffff8157b898: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cbc0)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff8158cbc0-ffffffff8158cc18: pcie_port_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *pcie_port_find_device(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a7070)
Location: drivers/pci/pcie/portdrv_core.c:489
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff815a7070-ffffffff815a70c8: pcie_port_find_device (STB_GLOBAL)
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
