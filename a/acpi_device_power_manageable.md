# Function: <code>acpi_device_power_manageable</code>

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
In drivers/pci/pci-acpi.c (ffffffff81457404)
Location: include/acpi/acpi_bus.h:622
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:622
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:622
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff814a402c)
Location: include/acpi/acpi_bus.h:631
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:631
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:631
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff814c5dbc)
Location: include/acpi/acpi_bus.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:633
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:633
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff814cfe2d)
Location: include/acpi/acpi_bus.h:647
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:647
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:647
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff81510075)
Location: include/acpi/acpi_bus.h:665
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:665
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:665
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff8154525e)
Location: include/acpi/acpi_bus.h:668
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff81572407)
Location: include/acpi/acpi_bus.h:668
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815dd62d)
Location: include/acpi/acpi_bus.h:668
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff815412d2)
Location: include/acpi/acpi_bus.h:673
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff8158a1e7)
Location: include/acpi/acpi_bus.h:673
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815f6dcd)
Location: include/acpi/acpi_bus.h:673
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81570c31)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff815bacc7)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81628cfd)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81591e21)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff815dbf95)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8164a7ed)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81640711)
Location: include/acpi/acpi_bus.h:667
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff81686b25)
Location: include/acpi/acpi_bus.h:667
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff816f98ed)
Location: include/acpi/acpi_bus.h:667
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81666b21)
Location: include/acpi/acpi_bus.h:668
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff816a48d5)
Location: include/acpi/acpi_bus.h:668
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff817163ad)
Location: include/acpi/acpi_bus.h:668
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81648f01)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff81687655)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff816f769d)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff816ba9e1)
Location: include/acpi/acpi_bus.h:677
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
```
```
In drivers/acpi/device_pm.c (ffffffff816fcad5)
Location: include/acpi/acpi_bus.h:677
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81771e3d)
Location: include/acpi/acpi_bus.h:677
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff817e02c9)
Location: include/acpi/acpi_bus.h:714
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
```
```
In drivers/acpi/device_pm.c (ffffffff8182a209)
Location: include/acpi/acpi_bus.h:714
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff818a754a)
Location: include/acpi/acpi_bus.h:714
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81903259)
Location: include/acpi/acpi_bus.h:725
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff8195c709)
Location: include/acpi/acpi_bus.h:725
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff819f178a)
Location: include/acpi/acpi_bus.h:725
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff819468f9)
Location: include/acpi/acpi_bus.h:742
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff819a2bf9)
Location: include/acpi/acpi_bus.h:742
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81a39e3a)
Location: include/acpi/acpi_bus.h:742
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff8198fc29)
Location: include/acpi/acpi_bus.h:844
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff819eb2a9)
Location: include/acpi/acpi_bus.h:844
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81a856ea)
Location: include/acpi/acpi_bus.h:844
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffff8000106f791c)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffff800010767eb8)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffff8000107b7ac8)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81585cb1)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff815ce665)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8161084d)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81574a81)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff815b8225)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81604d9d)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff81585b71)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff815d0275)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8163e62d)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
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
In drivers/pci/pci-acpi.c (ffffffff815a0021)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
```
```
In drivers/acpi/device_pm.c (ffffffff815ea135)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8165897d)
Location: include/acpi/acpi_bus.h:666
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
</details>
</li>
</ul>

## Differences
