# Function: <code>acpi_power_state_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d52e)
Location: drivers/acpi/device_pm.c:36
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_sysfs.c:power_state_show
```
**Symbols:**

```
ffffffff8147d52e-ffffffff8147d54f: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cbce4)
Location: drivers/acpi/device_pm.c:37
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff814cbce4-ffffffff814cbd05: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814edc12)
Location: drivers/acpi/device_pm.c:37
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff814edc12-ffffffff814edc33: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814faaa0)
Location: drivers/acpi/device_pm.c:38
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff814faaa0-ffffffff814faac1: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153c670)
Location: drivers/acpi/device_pm.c:38
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff8153c670-ffffffff8153c691: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81571bc2)
Location: drivers/acpi/device_pm.c:38
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff81572510-ffffffff81572531: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589992)
Location: drivers/acpi/device_pm.c:38
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff8158a2f0-ffffffff8158a311: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ba614)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff815bae00-ffffffff815bae21: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815db752)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff815dc0d0-ffffffff815dc0f1: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685edf)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff81686570-ffffffff81686591: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a3ca2)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff816a4320-ffffffff816a4341: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686932)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff816870c0-ffffffff816870e1: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fbce4)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff816fc550-ffffffff816fc571: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8182993d)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff81829c10-ffffffff81829c37: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195bcfa)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff8195c010-ffffffff8195c037: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a21da)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff819a24f0-ffffffff819a2517: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819ea88a)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
```
**Symbols:**

```
ffffffff819eaba0-ffffffff819eabc7: acpi_power_state_string (STB_GLOBAL)
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
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff8000107677a4)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffff800010768780-ffff8000107687cc: acpi_power_state_string (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cdf18)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff815ce7a0-ffffffff815ce7c1: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7a88)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff815b8360-ffffffff815b8381: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cfa32)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff815d03b0-ffffffff815d03d1: acpi_power_state_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_power_state_string(int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e98f2)
Location: drivers/acpi/device_pm.c:30
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_sysfs.c:power_state_show
  - drivers/acpi/device_sysfs.c:real_power_state_show
```
**Symbols:**

```
ffffffff815ea270-ffffffff815ea291: acpi_power_state_string (STB_GLOBAL)
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
