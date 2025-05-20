# Function: <code>dw_pcie_dbi_ro_wr_en</code>

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
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513d53)
Location: drivers/pci/dwc/pcie-designware.h:287
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549787)
Location: drivers/pci/controller/dwc/pcie-designware.h:298
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549a6d)
Location: drivers/pci/controller/dwc/pcie-designware.h:298
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fe62)
Location: drivers/pci/controller/dwc/pcie-designware.h:312
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8156028d)
Location: drivers/pci/controller/dwc/pcie-designware.h:312
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81590001)
Location: drivers/pci/controller/dwc/pcie-designware.h:324
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815906c8)
Location: drivers/pci/controller/dwc/pcie-designware.h:324
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1c69)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b23f8)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b629)
Location: drivers/pci/controller/dwc/pcie-designware.h:350
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165be2a)
Location: drivers/pci/controller/dwc/pcie-designware.h:350
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b932)
Location: drivers/pci/controller/dwc/pcie-designware.h:343
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167cc9b)
Location: drivers/pci/controller/dwc/pcie-designware.h:343
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e7b2)
Location: drivers/pci/controller/dwc/pcie-designware.h:346
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fb0f)
Location: drivers/pci/controller/dwc/pcie-designware.h:346
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1332)
Location: drivers/pci/controller/dwc/pcie-designware.h:346
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d272f)
Location: drivers/pci/controller/dwc/pcie-designware.h:346
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa3d3)
Location: drivers/pci/controller/dwc/pcie-designware.h:346
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbb9f)
Location: drivers/pci/controller/dwc/pcie-designware.h:346
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926b13)
Location: drivers/pci/controller/dwc/pcie-designware.h:447
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928d6f)
Location: drivers/pci/controller/dwc/pcie-designware.h:447
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196ace3)
Location: drivers/pci/controller/dwc/pcie-designware.h:468
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196cfaf)
Location: drivers/pci/controller/dwc/pcie-designware.h:468
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b44a3)
Location: drivers/pci/controller/dwc/pcie-designware.h:582
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b5f7f)
Location: drivers/pci/controller/dwc/pcie-designware.h:582
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
void dw_pcie_dbi_ro_wr_en(struct dw_pcie *pci);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072df20)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001073037c)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pci-keystone.c (ffff80001073330c)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001073352c)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
**Symbols:**

```
ffff80001073330c-ffff800010733348: dw_pcie_dbi_ro_wr_en (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7a0c)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9580)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8940)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea2e2)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5429)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5bb8)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815945c9)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594d58)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a59b9)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a6148)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815bfdb9)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c0548)
Location: drivers/pci/controller/dwc/pcie-designware.h:336
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
