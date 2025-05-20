# Function: <code>acpi_device_get_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d54f)
Location: drivers/acpi/device_pm.c:63
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_update_power
```
**Symbols:**

```
ffffffff8147d54f-ffffffff8147d67b: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cbd05)
Location: drivers/acpi/device_pm.c:64
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff814cbd05-ffffffff814cbe31: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814edc33)
Location: drivers/acpi/device_pm.c:64
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff814edc33-ffffffff814edd5f: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814faad0)
Location: drivers/acpi/device_pm.c:65
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff814faad0-ffffffff814fac0f: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153c6a0)
Location: drivers/acpi/device_pm.c:65
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff8153c6a0-ffffffff8153c856: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81572540)
Location: drivers/acpi/device_pm.c:65
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff81572540-ffffffff81572706: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81588f10)
Location: drivers/acpi/device_pm.c:65
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff81588f10-ffffffff815890d6: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815bae30)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff815bae30-ffffffff815baff8: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dc100)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff815dc100-ffffffff815dc2c8: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816865a0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff816865a0-ffffffff81686764: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a4350)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff816a4350-ffffffff816a451a: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816870f0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff816870f0-ffffffff81687282: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fc580)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff816fc580-ffffffff816fc70f: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81829c40)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff81829c40-ffffffff81829de2: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195c050)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff8195c050-ffffffff8195c216: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a2530)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff819a2530-ffffffff819a26f6: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819eabe0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff819eabe0-ffffffff819eada6: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff8000107687d0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffff8000107687d0-ffff800010768918: acpi_device_get_power (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce7d0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff815ce7d0-ffffffff815ce91a: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b8390)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff815b8390-ffffffff815b84da: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815d03e0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff815d03e0-ffffffff815d05a8: acpi_device_get_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_device_get_power(struct acpi_device *device, int *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ea2a0)
Location: drivers/acpi/device_pm.c:75
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:real_power_state_show
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff815ea2a0-ffffffff815ea468: acpi_device_get_power (STB_GLOBAL)
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
