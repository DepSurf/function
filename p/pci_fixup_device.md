# Function: <code>pci_fixup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814450e0)
Location: drivers/pci/quirks.c:3296
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff814450e0-ffffffff8144518e: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81fcaf25)
Location: drivers/pci/quirks.c:3426
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff81490ff0-ffffffff8149109f: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff82007f8b)
Location: drivers/pci/quirks.c:3545
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff814b2860-ffffffff814b290f: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff820e9056)
Location: drivers/pci/quirks.c:3591
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
```
**Symbols:**

```
ffffffff814bcb50-ffffffff814bcc49: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff826f1e8e)
Location: drivers/pci/quirks.c:3606
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
```
**Symbols:**

```
ffffffff814fcf10-ffffffff814fd00f: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8271be25)
Location: drivers/pci/quirks.c:92
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
```
**Symbols:**

```
ffffffff8152bdb0-ffffffff8152bead: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828d3e08)
Location: drivers/pci/quirks.c:100
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
```
**Symbols:**

```
ffffffff81542c30-ffffffff81542cf5: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828ede5e)
Location: drivers/pci/quirks.c:100
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff81572380-ffffffff81572466: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828f6f9f)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff815939d0-ffffffff81593ab6: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81641f60)
Location: drivers/pci/quirks.c:99
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81641f60-ffffffff81642046: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816683c0)
Location: drivers/pci/quirks.c:99
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff816683c0-ffffffff816684a6: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:100
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81bec178-ffffffff81bec1bd: pci_fixup_device.cold (STB_LOCAL)
ffffffff8164a7b0-ffffffff8164a967: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:100
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81ce75ab-ffffffff81ce765a: pci_fixup_device.cold (STB_LOCAL)
ffffffff816be290-ffffffff816be479: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:101
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81eae6e3-ffffffff81eae791: pci_fixup_device.cold (STB_LOCAL)
ffffffff817e41a0-ffffffff817e437d: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:101
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff8208f6f5-ffffffff8208f75b: pci_fixup_device.cold (STB_LOCAL)
ffffffff819087b0-ffffffff819089cd: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:194
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff8210fa56-ffffffff8210fabc: pci_fixup_device.cold (STB_LOCAL)
ffffffff8194be00-ffffffff8194c01c: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:194
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff821ed77e-ffffffff821ed7e4: pci_fixup_device.cold (STB_LOCAL)
ffffffff819950d0-ffffffff819952ec: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff800011478eb8)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffff8000106faa18-ffff8000106fab30: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c15518a0)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
c0892ec8-c0892fc8: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c0000000013a267c)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
c0000000008784b0-c000000000878614: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe00002be36)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
```
**Symbols:**

```
ffffffe0004caaea-ffffffe0004cabca: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828dfd52)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff81587860-ffffffff81587946: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828d8422)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff81576610-ffffffff815766f6: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828f2bd9)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff81587720-ffffffff81587806: pci_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff828f7ff3)
Location: drivers/pci/quirks.c:99
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
**Symbols:**

```
ffffffff815a1bd0-ffffffff815a1cb6: pci_fixup_device (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
