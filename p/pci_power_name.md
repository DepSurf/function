# Function: <code>pci_power_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81620364)
Location: include/linux/pci.h:123
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81680da9)
Location: include/linux/pci.h:121
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816aead9)
Location: include/linux/pci.h:121
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/usb/core/hcd-pci.c (ffffffff816c37c5)
Location: include/linux/pci.h:122
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff814f09cf)
Location: include/linux/pci.h:145
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172f5a5)
Location: include/linux/pci.h:145
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff815202ef)
Location: include/linux/pci.h:143
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176eae4)
Location: include/linux/pci.h:143
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff8153611d)
Location: include/linux/pci.h:143
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81793164)
Location: include/linux/pci.h:143
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff81565a8e)
Location: include/linux/pci.h:143
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d15e3)
Location: include/linux/pci.h:143
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff81586d8e)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818024b3)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff8162cc12)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
```
```
In drivers/pci/pci-driver.c (ffffffff8162de76)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2fe3)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff81bf7d20)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
```
```
In drivers/pci/pci-driver.c (ffffffff81653569)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff81655e08)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dd433)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff81be9bc7)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
```
```
In drivers/pci/pci-driver.c (ffffffff81636009)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff81638a08)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c07a3)
Location: include/linux/pci.h:168
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff81ce455d)
Location: include/linux/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
```
```
In drivers/pci/pci-driver.c (ffffffff816a6219)
Location: include/linux/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8d38)
Location: include/linux/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81956eed)
Location: include/linux/pci.h:174
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff81eab253)
Location: include/linux/pci.h:183
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/pci-driver.c (ffffffff817c8b27)
Location: include/linux/pci.h:183
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cba38)
Location: include/linux/pci.h:183
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0b50)
Location: include/linux/pci.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff818e0756)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/pci-driver.c (ffffffff818e61a1)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e92e8)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c38df9)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff81923b5c)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/pci-driver.c (ffffffff819297e1)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192c8f8)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ca01a7)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci.c (ffffffff8196c190)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/pci-driver.c (ffffffff81971ff1)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-sysfs.c (ffffffff81975188)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:power_state_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d54df7)
Location: include/linux/pci.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffff8000106eb86c)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a36c3c)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (c08864dc)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (c0b0a060)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (c000000000867350)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (c000000000af5760)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff817ba893)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff815699ee)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac2b3)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff8157aade)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f7333)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff815950ee)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81811573)
Location: include/linux/pci.h:149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
</details>
</li>
</ul>

## Differences
