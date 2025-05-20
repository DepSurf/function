# Function: <code>acpi_pci_find_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814854b4)
Location: drivers/acpi/pci_root.c:245
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff814854b4-ffffffff81485516: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d403e)
Location: drivers/acpi/pci_root.c:245
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff814d403e-ffffffff814d40a0: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814f668d)
Location: drivers/acpi/pci_root.c:245
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff814f668d-ffffffff814f66ef: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81504ca0)
Location: drivers/acpi/pci_root.c:245
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff81504ca0-ffffffff81504d02: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81546fc0)
Location: drivers/acpi/pci_root.c:246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff81546fc0-ffffffff81547022: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8157d070)
Location: drivers/acpi/pci_root.c:247
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff8157d070-ffffffff8157d0d2: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81594d50)
Location: drivers/acpi/pci_root.c:247
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff81594d50-ffffffff81594db2: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815c5e00)
Location: drivers/acpi/pci_root.c:235
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815c5e00-ffffffff815c5e62: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815e7030)
Location: drivers/acpi/pci_root.c:234
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815e7030-ffffffff815e7092: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81692f15)
Location: drivers/acpi/pci_root.c:236
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81692860-ffffffff816928c2: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff816b09e5)
Location: drivers/acpi/pci_root.c:234
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff816b02a0-ffffffff816b0302: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81692f42)
Location: drivers/acpi/pci_root.c:227
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81692880-ffffffff816928e2: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81708a92)
Location: drivers/acpi/pci_root.c:229
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff817083d0-ffffffff81708432: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81836e56)
Location: drivers/acpi/pci_root.c:282
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
```
**Symbols:**

```
ffffffff81836720-ffffffff8183676f: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8196afb3)
Location: drivers/acpi/pci_root.c:282
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff8196a7d0-ffffffff8196a81f: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819b1573)
Location: drivers/acpi/pci_root.c:282
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff819b0d90-ffffffff819b0ddf: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819fba53)
Location: drivers/acpi/pci_root.c:282
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff819fb270-ffffffff819fb2bf: acpi_pci_find_root (STB_GLOBAL)
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
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffff800010774210)
Location: drivers/acpi/pci_root.c:234
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffff800010774210-ffff800010774290: acpi_pci_find_root (STB_GLOBAL)
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
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815d8310)
Location: drivers/acpi/pci_root.c:234
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815d8310-ffffffff815d8372: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815c1f00)
Location: drivers/acpi/pci_root.c:234
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815c1f00-ffffffff815c1f62: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815db310)
Location: drivers/acpi/pci_root.c:234
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815db310-ffffffff815db372: acpi_pci_find_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct acpi_pci_root *acpi_pci_find_root(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815f51d0)
Location: drivers/acpi/pci_root.c:234
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
```
**Symbols:**

```
ffffffff815f51d0-ffffffff815f5232: acpi_pci_find_root (STB_GLOBAL)
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
