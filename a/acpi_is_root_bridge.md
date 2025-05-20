# Function: <code>acpi_is_root_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8148545a)
Location: drivers/acpi/pci_root.c:83
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff8148545a-ffffffff814854b4: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d3fe4)
Location: drivers/acpi/pci_root.c:83
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff814d3fe4-ffffffff814d403e: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814f6633)
Location: drivers/acpi/pci_root.c:83
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff814f6633-ffffffff814f668d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81504c40)
Location: drivers/acpi/pci_root.c:83
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff81504c40-ffffffff81504c9a: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81546f60)
Location: drivers/acpi/pci_root.c:84
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff81546f60-ffffffff81546fba: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8157d010)
Location: drivers/acpi/pci_root.c:84
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff8157d010-ffffffff8157d06a: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81594cf0)
Location: drivers/acpi/pci_root.c:84
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff81594cf0-ffffffff81594d4a: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815c5da0)
Location: drivers/acpi/pci_root.c:71
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815c5da0-ffffffff815c5dfd: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815e6fd0)
Location: drivers/acpi/pci_root.c:70
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815e6fd0-ffffffff815e702d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81693279)
Location: drivers/acpi/pci_root.c:70
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81692800-ffffffff8169285d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff816b0d49)
Location: drivers/acpi/pci_root.c:68
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff816b0240-ffffffff816b029d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81692f19)
Location: drivers/acpi/pci_root.c:66
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81692820-ffffffff8169287d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81708a69)
Location: drivers/acpi/pci_root.c:68
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81708370-ffffffff817083cd: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81836e31)
Location: drivers/acpi/pci_root.c:66
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff818366e0-ffffffff81836716: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8196a780)
Location: drivers/acpi/pci_root.c:66
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff8196a780-ffffffff8196a7b6: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819b0d40)
Location: drivers/acpi/pci_root.c:66
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff819b0d40-ffffffff819b0d76: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819fb220)
Location: drivers/acpi/pci_root.c:66
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff819fb220-ffffffff819fb256: acpi_is_root_bridge (STB_GLOBAL)
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
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffff800010774190)
Location: drivers/acpi/pci_root.c:70
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffff800010774190-ffff80001077420c: acpi_is_root_bridge (STB_GLOBAL)
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
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815d82b0)
Location: drivers/acpi/pci_root.c:70
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815d82b0-ffffffff815d830d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815c1ea0)
Location: drivers/acpi/pci_root.c:70
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815c1ea0-ffffffff815c1efd: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815db2b0)
Location: drivers/acpi/pci_root.c:70
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815db2b0-ffffffff815db30d: acpi_is_root_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_is_root_bridge(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815f5170)
Location: drivers/acpi/pci_root.c:70
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815f5170-ffffffff815f51cd: acpi_is_root_bridge (STB_GLOBAL)
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
