# Function: <code>dw_pcie_readw_dbi</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549b2f)
Location: drivers/pci/controller/dwc/pcie-designware.h:273
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8156038c)
Location: drivers/pci/controller/dwc/pcie-designware.h:277
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81590780)
Location: drivers/pci/controller/dwc/pcie-designware.h:289
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0f95)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b24b0)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a7a5)
Location: drivers/pci/controller/dwc/pcie-designware.h:315
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165bfd0)
Location: drivers/pci/controller/dwc/pcie-designware.h:315
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167aeb5)
Location: drivers/pci/controller/dwc/pcie-designware.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167d4ca)
Location: drivers/pci/controller/dwc/pcie-designware.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d905)
Location: drivers/pci/controller/dwc/pcie-designware.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8166033a)
Location: drivers/pci/controller/dwc/pcie-designware.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0375)
Location: drivers/pci/controller/dwc/pcie-designware.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2f5a)
Location: drivers/pci/controller/dwc/pcie-designware.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f91ce)
Location: drivers/pci/controller/dwc/pcie-designware.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fb6b1)
Location: drivers/pci/controller/dwc/pcie-designware.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819251b0)
Location: drivers/pci/controller/dwc/pcie-designware.h:427
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928421)
Location: drivers/pci/controller/dwc/pcie-designware.h:427
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968f00)
Location: drivers/pci/controller/dwc/pcie-designware.h:448
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c64e)
Location: drivers/pci/controller/dwc/pcie-designware.h:448
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b283d)
Location: drivers/pci/controller/dwc/pcie-designware.h:469
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4a9b)
Location: drivers/pci/controller/dwc/pcie-designware.h:469
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d034)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072fd88)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731a80)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
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
In drivers/pci/controller/dwc/pcie-designware.c (c08b67f0)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9060)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb82c)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e77ee)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e9dfa)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4755)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5c70)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815938f5)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594e10)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4ce5)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a6200)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf0e5)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c0600)
Location: drivers/pci/controller/dwc/pcie-designware.h:301
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
</details>
</li>
</ul>

## Differences
