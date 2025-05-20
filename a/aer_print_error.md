# Function: <code>aer_print_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814494f0)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:166
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
**Symbols:**

```
ffffffff814494f0-ffffffff814497e3: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814957e0)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:166
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
**Symbols:**

```
ffffffff814957e0-ffffffff81495acf: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814b71a0)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:166
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
**Symbols:**

```
ffffffff814b71a0-ffffffff814b748f: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814c1ae0)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:166
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
**Symbols:**

```
ffffffff814c1ae0-ffffffff814c1db7: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81501cf0)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:166
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
**Symbols:**

```
ffffffff81501cf0-ffffffff81501fca: aer_print_error (STB_GLOBAL)
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
In drivers/pci/pcie/aer.c (ffffffff81533ed9)
Location: drivers/pci/pcie/aer.c:556
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154b560)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8154b560-ffffffff8154b7a0: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b987)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8157b987-ffffffff8157bb1c: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159d3ee)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8159d3ee-ffffffff8159d57c: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163d152)
Location: drivers/pci/pcie/aer.c:675
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff8163d152-ffffffff8163d2d6: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81bf948e)
Location: drivers/pci/pcie/aer.c:697
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81bf948e-ffffffff81bf9637: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81beb2e3)
Location: drivers/pci/pcie/aer.c:697
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81beb2e3-ffffffff81beb485: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:699
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81ce60ea-ffffffff81ce610f: aer_print_error.cold (STB_LOCAL)
ffffffff816b6fc0-ffffffff816b7254: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:704
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81eacbd1-ffffffff81eacbf6: aer_print_error.cold (STB_LOCAL)
ffffffff817dac70-ffffffff817daf39: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff818fc7c0)
Location: drivers/pci/pcie/aer.c:709
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff818fc7c0-ffffffff818fcabf: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8193fc50)
Location: drivers/pci/pcie/aer.c:712
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff8193fc50-ffffffff8193ff37: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81989240)
Location: drivers/pci/pcie/aer.c:701
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81989240-ffffffff81989527: aer_print_error (STB_GLOBAL)
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
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010705530)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffff800010705530-ffff8000107056c8: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089c5f4)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
c089c5f4-c089ca0c: aer_print_error (STB_GLOBAL)
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
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d33ec)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffe0004d33ec-ffffffe0004d3740: aer_print_error (STB_GLOBAL)
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
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590cd1)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81590cd1-ffffffff81590fe8: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157fdbe)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8157fdbe-ffffffff8157ff4c: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159113e)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8159113e-ffffffff815912cc: aer_print_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815ab603)
Location: drivers/pci/pcie/aer.c:745
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815ab603-ffffffff815ab791: aer_print_error (STB_GLOBAL)
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
