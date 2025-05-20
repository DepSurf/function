# Function: <code>acpi_device_can_wakeup</code>

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
In drivers/pci/pci-acpi.c (0)
Location: include/acpi/acpi_bus.h:627
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff8147d4f2)
Location: include/acpi/acpi_bus.h:627
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
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
In drivers/pci/pci-acpi.c (0)
Location: include/acpi/acpi_bus.h:636
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:636
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
In drivers/pci/pci-acpi.c (0)
Location: include/acpi/acpi_bus.h:638
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/acpi/acpi_bus.h:638
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814fafbd)
Location: include/acpi/acpi_bus.h:652
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153cc05)
Location: include/acpi/acpi_bus.h:670
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
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
In drivers/acpi/device_pm.c (ffffffff815721bb)
Location: include/acpi/acpi_bus.h:673
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
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
In drivers/acpi/device_pm.c (ffffffff81589f9b)
Location: include/acpi/acpi_bus.h:678
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
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
In drivers/acpi/device_pm.c (ffffffff815baa19)
Location: include/acpi/acpi_bus.h:674
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dbcb9)
Location: include/acpi/acpi_bus.h:671
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686243)
Location: include/acpi/acpi_bus.h:672
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a4002)
Location: include/acpi/acpi_bus.h:673
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686d82)
Location: include/acpi/acpi_bus.h:674
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fc212)
Location: include/acpi/acpi_bus.h:682
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff818299de)
Location: include/acpi/acpi_bus.h:719
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195bdae)
Location: include/acpi/acpi_bus.h:730
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a228e)
Location: include/acpi/acpi_bus.h:747
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819ea93e)
Location: include/acpi/acpi_bus.h:849
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010768300)
Location: include/acpi/acpi_bus.h:671
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce389)
Location: include/acpi/acpi_bus.h:671
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7f49)
Location: include/acpi/acpi_bus.h:671
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cff99)
Location: include/acpi/acpi_bus.h:671
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e9e59)
Location: include/acpi/acpi_bus.h:671
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
</details>
</li>
</ul>

## Differences
