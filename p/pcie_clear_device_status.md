# Function: <code>pcie_clear_device_status</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164ff90)
Location: drivers/pci/pci.c:2185
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff8164ff90-ffffffff8164ffea: pcie_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81632b50)
Location: drivers/pci/pci.c:2215
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_process_err_devices
```
**Symbols:**

```
ffffffff81632b50-ffffffff81632baa: pcie_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a2cc0)
Location: drivers/pci/pci.c:2246
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
```
**Symbols:**

```
ffffffff816a2cc0-ffffffff816a2d1a: pcie_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4dd0)
Location: drivers/pci/pci.c:2307
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff817c4dd0-ffffffff817c4e3b: pcie_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1e10)
Location: drivers/pci/pci.c:2281
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff818e1e10-ffffffff818e1e7b: pcie_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925250)
Location: drivers/pci/pci.c:2319
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff81925250-ffffffff819252bb: pcie_clear_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d920)
Location: drivers/pci/pci.c:2416
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff8196d920-ffffffff8196d98b: pcie_clear_device_status (STB_GLOBAL)
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
