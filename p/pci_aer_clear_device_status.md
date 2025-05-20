# Function: <code>pci_aer_clear_device_status</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154b2c0)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
```
**Symbols:**

```
ffffffff8154b2c0-ffffffff8154b31a: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b150)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff8157b150-ffffffff8157b1ac: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159cbb0)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff8159cbb0-ffffffff8159cc0c: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163c6a0)
Location: drivers/pci/pcie/aer.c:244
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff8163c6a0-ffffffff8163c6fa: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010704a80)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffff800010704a80-ffff800010704ae8: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089bebc)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
c089bebc-c089bf2c: pci_aer_clear_device_status (STB_GLOBAL)
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
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d2d76)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffe0004d2d76-ffffffe0004d2db6: pci_aer_clear_device_status (STB_GLOBAL)
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
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590720)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff81590720-ffffffff8159077c: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157f580)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff8157f580-ffffffff8157f5dc: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590900)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff81590900-ffffffff8159095c: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815aadb0)
Location: drivers/pci/pcie/aer.c:369
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff815aadb0-ffffffff815aae0c: pci_aer_clear_device_status (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
