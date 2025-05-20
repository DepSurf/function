# Function: <code>pcie_capability_clear_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437af4)
Location: include/linux/pci.h:954
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81448e8e)
Location: include/linux/pci.h:954
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449b7d)
Location: include/linux/pci.h:954
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8144b259)
Location: include/linux/pci.h:954
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff8144b6f7)
Location: include/linux/pci.h:954
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483714)
Location: include/linux/pci.h:965
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81495000)
Location: include/linux/pci.h:965
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81495e3d)
Location: include/linux/pci.h:965
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814974e9)
Location: include/linux/pci.h:965
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff81497956)
Location: include/linux/pci.h:965
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4e74)
Location: include/linux/pci.h:995
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814b69b0)
Location: include/linux/pci.h:995
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b77dd)
Location: include/linux/pci.h:995
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8e12)
Location: include/linux/pci.h:995
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff814b92d6)
Location: include/linux/pci.h:995
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a67af)
Location: include/linux/pci.h:996
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff814aeee7)
Location: include/linux/pci.h:996
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814c1292)
Location: include/linux/pci.h:996
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c20b6)
Location: include/linux/pci.h:996
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814c3632)
Location: include/linux/pci.h:996
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3a6b)
Location: include/linux/pci.h:996
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e6c42)
Location: include/linux/pci.h:1021
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff814ee2b7)
Location: include/linux/pci.h:1021
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81501716)
Location: include/linux/pci.h:1021
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff815022d6)
Location: include/linux/pci.h:1021
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff81503872)
Location: include/linux/pci.h:1021
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff81503cab)
Location: include/linux/pci.h:1021
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff81516250)
Location: include/linux/pci.h:1016
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff8151df2b)
Location: include/linux/pci.h:1016
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81530326)
Location: include/linux/pci.h:1016
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff81533bb3)
Location: include/linux/pci.h:1016
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81534fb9)
Location: include/linux/pci.h:1016
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8152bd7d)
Location: include/linux/pci.h:1052
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff8153368b)
Location: include/linux/pci.h:1052
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815477e6)
Location: include/linux/pci.h:1052
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff8154b072)
Location: include/linux/pci.h:1052
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c1c9)
Location: include/linux/pci.h:1052
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8155a866)
Location: include/linux/pci.h:1113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff81562b6b)
Location: include/linux/pci.h:1113
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815778c9)
Location: include/linux/pci.h:1113
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff8157af49)
Location: include/linux/pci.h:1113
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c57b)
Location: include/linux/pci.h:1113
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8157b8ef)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff81583cfb)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81599049)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff8159c9a6)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8159dfdb)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff816208cf)
Location: include/linux/pci.h:1138
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff8162a7bd)
Location: include/linux/pci.h:1138
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81638617)
Location: include/linux/pci.h:1138
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff8163c389)
Location: include/linux/pci.h:1138
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
```
```
In drivers/pci/pcie/pme.c (ffffffff8163db91)
Location: include/linux/pci.h:1138
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff81646eef)
Location: include/linux/pci.h:1148
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff81650c2e)
Location: include/linux/pci.h:1148
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f13a)
Location: include/linux/pci.h:1148
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff816630c1)
Location: include/linux/pci.h:1148
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81664221)
Location: include/linux/pci.h:1148
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8162a897)
Location: include/linux/pci.h:1155
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff8163373e)
Location: include/linux/pci.h:1155
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81641628)
Location: include/linux/pci.h:1155
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff81645581)
Location: include/linux/pci.h:1155
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81646691)
Location: include/linux/pci.h:1155
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff81699d77)
Location: include/linux/pci.h:1203
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff816a38ef)
Location: include/linux/pci.h:1203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff816b2664)
Location: include/linux/pci.h:1203
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff816b6757)
Location: include/linux/pci.h:1203
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7e91)
Location: include/linux/pci.h:1203
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff817bb44b)
Location: include/linux/pci.h:1228
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
```
```
In drivers/pci/pci.c (ffffffff817c5c49)
Location: include/linux/pci.h:1228
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff817d5d38)
Location: include/linux/pci.h:1228
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff817da2b6)
Location: include/linux/pci.h:1228
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc1d1)
Location: include/linux/pci.h:1228
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff818d6e5b)
Location: include/linux/pci.h:1235
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
```
```
In drivers/pci/pci.c (ffffffff818e2ec9)
Location: include/linux/pci.h:1235
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7646)
Location: include/linux/pci.h:1235
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff818fc10e)
Location: include/linux/pci.h:1235
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe0c1)
Location: include/linux/pci.h:1235
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8191a0db)
Location: include/linux/pci.h:1269
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
```
```
In drivers/pci/pci.c (ffffffff81926d00)
Location: include/linux/pci.h:1269
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193abb0)
Location: include/linux/pci.h:1269
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f666)
Location: include/linux/pci.h:1269
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81941571)
Location: include/linux/pci.h:1269
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff819624db)
Location: include/linux/pci.h:1297
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
```
```
In drivers/pci/pci.c (ffffffff8196f4a0)
Location: include/linux/pci.h:1297
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983a10)
Location: include/linux/pci.h:1297
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/aspm.c (ffffffff81984f3b)
Location: include/linux/pci.h:1297
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
```
In drivers/pci/pcie/aer.c (ffffffff8198845a)
Location: include/linux/pci.h:1297
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a7d1)
Location: include/linux/pci.h:1297
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/quirks.c (ffffffff81996fcd)
Location: include/linux/pci.h:1297
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/probe.c (ffff8000106ded20)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffff8000106e7fa8)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffff800010700724)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffff8000107046a0)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffff800010705e80)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (c087aa50)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (c088306c)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (c0898440)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (c089bbd8)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (c089cba0)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857b80)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/pci.c (c000000000862a2c)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b6eaa)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffe0004be62a)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf68e)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d2aea)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3c04)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8156fe0f)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff8157821b)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158ced9)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff81590496)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff815917db)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8155e56f)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff8156695b)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157ba19)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff8157f376)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff815806bb)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff8156f63f)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff81577a4b)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cd99)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff815906f6)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81591d2b)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
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
In drivers/pci/probe.c (ffffffff81589b1f)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci.c (ffffffff81591f0b)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a7249)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer.c (ffffffff815aaba6)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff815abbeb)
Location: include/linux/pci.h:1114
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
</details>
</li>
</ul>

## Differences
