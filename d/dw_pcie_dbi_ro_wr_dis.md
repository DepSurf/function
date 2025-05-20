# Function: <code>dw_pcie_dbi_ro_wr_dis</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513dc1)
Location: drivers/pci/dwc/pcie-designware.h:298
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815497f5)
Location: drivers/pci/controller/dwc/pcie-designware.h:309
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549ac4)
Location: drivers/pci/controller/dwc/pcie-designware.h:309
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fed0)
Location: drivers/pci/controller/dwc/pcie-designware.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815602e4)
Location: drivers/pci/controller/dwc/pcie-designware.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81590058)
Location: drivers/pci/controller/dwc/pcie-designware.h:335
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81590712)
Location: drivers/pci/controller/dwc/pcie-designware.h:335
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1dcc)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b2442)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b7dc)
Location: drivers/pci/controller/dwc/pcie-designware.h:361
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165be66)
Location: drivers/pci/controller/dwc/pcie-designware.h:361
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bb00)
Location: drivers/pci/controller/dwc/pcie-designware.h:354
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167cd2f)
Location: drivers/pci/controller/dwc/pcie-designware.h:354
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e998)
Location: drivers/pci/controller/dwc/pcie-designware.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fb78)
Location: drivers/pci/controller/dwc/pcie-designware.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1531)
Location: drivers/pci/controller/dwc/pcie-designware.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2798)
Location: drivers/pci/controller/dwc/pcie-designware.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa598)
Location: drivers/pci/controller/dwc/pcie-designware.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbc08)
Location: drivers/pci/controller/dwc/pcie-designware.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926cdc)
Location: drivers/pci/controller/dwc/pcie-designware.h:458
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928e19)
Location: drivers/pci/controller/dwc/pcie-designware.h:458
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196aeac)
Location: drivers/pci/controller/dwc/pcie-designware.h:479
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d059)
Location: drivers/pci/controller/dwc/pcie-designware.h:479
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b466c)
Location: drivers/pci/controller/dwc/pcie-designware.h:593
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b6029)
Location: drivers/pci/controller/dwc/pcie-designware.h:593
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dw_pcie_dbi_ro_wr_dis(struct dw_pcie *pci);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e078)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff8000107303c0)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010733348)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff800010733568)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
**Symbols:**

```
ffff800010733348-ffff800010733384: dw_pcie_dbi_ro_wr_dis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7b5c)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b95c4)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8a92)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea33c)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a558c)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5c02)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8159472c)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594da2)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5b1c)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a6192)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815bff1c)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c0592)
Location: drivers/pci/controller/dwc/pcie-designware.h:347
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
