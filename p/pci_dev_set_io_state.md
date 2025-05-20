# Function: <code>pci_dev_set_io_state</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8154814e)
Location: drivers/pci/pci.h:314
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815511f9)
Location: drivers/pci/pci.h:314
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815578ca)
Location: drivers/pci/pci.h:314
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff815781df)
Location: drivers/pci/pci.h:319
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81581179)
Location: drivers/pci/pci.h:319
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815878fa)
Location: drivers/pci/pci.h:319
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff8159995f)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2c79)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a92ba)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff8163913f)
Location: drivers/pci/pci.h:358
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164b7f9)
Location: drivers/pci/pci.h:358
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651f45)
Location: drivers/pci/pci.h:358
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff8165fc5f)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fb79)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674905)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff8164214f)
Location: drivers/pci/pci.h:334
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81652079)
Location: drivers/pci/pci.h:334
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656e35)
Location: drivers/pci/pci.h:334
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff816b2e1f)
Location: drivers/pci/pci.h:355
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3dc9)
Location: drivers/pci/pci.h:355
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8db5)
Location: drivers/pci/pci.h:355
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff817db7cb)
Location: drivers/pci/pci.h:316
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e98f9)
Location: drivers/pci/pci.h:316
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817ef00b)
Location: drivers/pci/pci.h:316
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff818fd6ff)
Location: drivers/pci/pci.h:332
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190f8e0)
Location: drivers/pci/pci.h:332
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81916afc)
Location: drivers/pci/pci.h:332
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff81940b8f)
Location: drivers/pci/pci.h:330
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81952fd0)
Location: drivers/pci/pci.h:330
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a0ec)
Location: drivers/pci/pci.h:330
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pci-driver.c (ffffffff81970f30)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dev_set_disconnected
```
```
In drivers/pci/pcie/err.c (ffffffff81989def)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c460)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a368c)
Location: drivers/pci/pci.h:341
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffff80001070115c)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b51c)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010712588)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (c0898e54)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/pcie/err.c (ffffffe0004cfec0)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d8156)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
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
In drivers/pci/pcie/err.c (ffffffff8158d7ef)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81596489)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ca8a)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff8157c32f)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81585619)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bc1a)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff8158d6af)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815969c9)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d00a)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
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
In drivers/pci/pcie/err.c (ffffffff815a7b5f)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b0e49)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b743a)
Location: drivers/pci/pci.h:353
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
</details>
</li>
</ul>

## Differences
