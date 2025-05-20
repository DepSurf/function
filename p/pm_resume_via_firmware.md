# Function: <code>pm_resume_via_firmware</code>

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
In drivers/base/power/generic_ops.c (0)
Location: include/linux/suspend.h:230
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/suspend.h:230
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
In drivers/base/power/generic_ops.c (0)
Location: include/linux/suspend.h:229
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff816c5bc6)
Location: include/linux/suspend.h:229
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/suspend.h:229
Inline: True
```
```
In drivers/base/power/generic_ops.c (0)
Location: include/linux/suspend.h:229
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff816f3be6)
Location: include/linux/suspend.h:229
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/suspend.h:231
Inline: True
```
```
In drivers/base/power/generic_ops.c (0)
Location: include/linux/suspend.h:231
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81709736)
Location: include/linux/suspend.h:231
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/suspend.h:235
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/linux/suspend.h:235
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff8177a8e6)
Location: include/linux/suspend.h:235
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (ffffffff81520b01)
Location: include/linux/suspend.h:235
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff81572027)
Location: include/linux/suspend.h:235
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff817bb176)
Location: include/linux/suspend.h:235
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db538)
Location: include/linux/suspend.h:235
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff81536931)
Location: include/linux/suspend.h:235
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff81589e07)
Location: include/linux/suspend.h:235
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff817e25e6)
Location: include/linux/suspend.h:235
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818028e8)
Location: include/linux/suspend.h:235
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff81566215)
Location: include/linux/suspend.h:272
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815ba87d)
Location: include/linux/suspend.h:272
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81822f81)
Location: include/linux/suspend.h:272
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843da8)
Location: include/linux/suspend.h:272
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff81587575)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815dbb1d)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81854421)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875718)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff8162d375)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff81685b4f)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81926b91)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a238)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff81652a65)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff816a395f)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff8192e701)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fdc8)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff81635525)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8168674f)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81911ac1)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933c88)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff816a5435)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff816fbaef)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff819b3318)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7088)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff817c7aab)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff81829044)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81b12448)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39ba2)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff818e521b)
Location: include/linux/suspend.h:274
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8195b1f4)
Location: include/linux/suspend.h:274
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81ca2ef8)
Location: include/linux/suspend.h:274
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (ffffffff8192885b)
Location: include/linux/suspend.h:278
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff819a16c4)
Location: include/linux/suspend.h:278
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81d0a5b8)
Location: include/linux/suspend.h:278
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (ffffffff8197107b)
Location: include/linux/suspend.h:278
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff819e9d74)
Location: include/linux/suspend.h:278
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81dc0248)
Location: include/linux/suspend.h:278
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (ffff8000106eb218)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffff800010767c04)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba514)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (c0886ce0)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99b94)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (c00000000086691c)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/input/serio/i8042.c (c000000000b72360)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dba8)
Location: include/linux/suspend.h:273
Inline: True
```
</details>
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/suspend.h:339
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/linux/suspend.h:339
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/suspend.h:339
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff8156a1d5)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815b7dad)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff817d0be1)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/pci/pci-driver.c (ffffffff8157b2c5)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815cfdfd)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff818485b1)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186abc8)
Location: include/linux/suspend.h:273
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff815958d5)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815e9cbd)
Location: include/linux/suspend.h:273
Inline: True
```
```
In drivers/input/serio/i8042.c (ffffffff81863831)
Location: include/linux/suspend.h:273
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884b58)
Location: include/linux/suspend.h:273
Inline: True
```
</details>
</li>
</ul>

## Differences
