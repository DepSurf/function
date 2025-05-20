# Function: <code>acpi_evaluate_reg</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816814e0)
Location: drivers/acpi/utils.c:617
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff816814e0-ffffffff8168154f: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8169fe30)
Location: drivers/acpi/utils.c:613
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8169fe30-ffffffff8169fe9f: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682bf0)
Location: drivers/acpi/utils.c:607
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81682bf0-ffffffff81682c5f: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7d40)
Location: drivers/acpi/utils.c:621
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff816f7d40-ffffffff816f7daf: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81824d00)
Location: drivers/acpi/utils.c:621
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81824d00-ffffffff81824d9c: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81955e60)
Location: drivers/acpi/utils.c:659
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81955e60-ffffffff81955efc: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c260)
Location: drivers/acpi/utils.c:659
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_config_space_access
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8199c260-ffffffff8199c2fc: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_reg(acpi_handle handle, u8 space_id, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e47b0)
Location: drivers/acpi/utils.c:731
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_config_space_access
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff819e47b0-ffffffff819e484c: acpi_evaluate_reg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
