# Function: <code>acpi_add_pm_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*work_func)(struct work_struct *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d876)
Location: drivers/acpi/device_pm.c:421
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff8147d876-ffffffff8147d952: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*work_func)(struct work_struct *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cc01b)
Location: drivers/acpi/device_pm.c:423
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff814cc01b-ffffffff814cc0f4: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*work_func)(struct work_struct *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814edf49)
Location: drivers/acpi/device_pm.c:423
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff814edf49-ffffffff814ee022: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814fa8e7)
Location: drivers/acpi/device_pm.c:432
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff814fa7d0-ffffffff814fa872: acpi_add_pm_notifier.part.8 (STB_LOCAL)
ffffffff814fae30-ffffffff814fae51: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153c538)
Location: drivers/acpi/device_pm.c:439
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff8153c420-ffffffff8153c4da: acpi_add_pm_notifier.part.11 (STB_LOCAL)
ffffffff8153ca80-ffffffff8153caa1: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815723e1)
Location: drivers/acpi/device_pm.c:439
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815722e0-ffffffff8157239a: acpi_add_pm_notifier.part.12 (STB_LOCAL)
ffffffff81572930-ffffffff8157294e: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8158a1c1)
Location: drivers/acpi/device_pm.c:440
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff8158a0c0-ffffffff8158a17a: acpi_add_pm_notifier.part.12 (STB_LOCAL)
ffffffff8158a540-ffffffff8158a55e: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815baca1)
Location: drivers/acpi/device_pm.c:481
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815baba0-ffffffff815bac5a: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffffffff815bb220-ffffffff815bb23e: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dbf6f)
Location: drivers/acpi/device_pm.c:485
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815dbe40-ffffffff815dbf04: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffffffff815dc4f0-ffffffff815dc50e: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816869b0)
Location: drivers/acpi/device_pm.c:485
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff816869b0-ffffffff81686a80: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a4760)
Location: drivers/acpi/device_pm.c:485
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff816a4760-ffffffff816a4830: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816874e0)
Location: drivers/acpi/device_pm.c:482
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff816874e0-ffffffff816875b0: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fc960)
Location: drivers/acpi/device_pm.c:482
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff816fc960-ffffffff816fca30: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8182a070)
Location: drivers/acpi/device_pm.c:510
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff8182a070-ffffffff8182a14c: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195c560)
Location: drivers/acpi/device_pm.c:557
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff8195c560-ffffffff8195c63c: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a2a50)
Location: drivers/acpi/device_pm.c:557
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff819a2a50-ffffffff819a2b2c: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819eb100)
Location: drivers/acpi/device_pm.c:570
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff819eb100-ffffffff819eb1dc: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010767e8c)
Location: drivers/acpi/device_pm.c:485
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffff800010767d28-ffff800010767e0c: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffff800010768b90-ffff800010768bf0: acpi_add_pm_notifier (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce63f)
Location: drivers/acpi/device_pm.c:485
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815ce510-ffffffff815ce5d4: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffffffff815ceb40-ffffffff815ceb5e: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b81ff)
Location: drivers/acpi/device_pm.c:485
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815b80d0-ffffffff815b8194: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffffffff815b8700-ffffffff815b871e: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815d024f)
Location: drivers/acpi/device_pm.c:485
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815d0120-ffffffff815d01e4: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffffffff815d07d0-ffffffff815d07ee: acpi_add_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device *adev, struct device *dev, void (*func)(struct acpi_device_wakeup_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ea10f)
Location: drivers/acpi/device_pm.c:485
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff815e9fe0-ffffffff815ea0a4: acpi_add_pm_notifier.part.0 (STB_LOCAL)
ffffffff815ea690-ffffffff815ea6ae: acpi_add_pm_notifier (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*func)(struct acpi_device_wakeup_context *)</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*work_func)(struct work_struct *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
