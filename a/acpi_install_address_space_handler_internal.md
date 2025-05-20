# Function: <code>acpi_install_address_space_handler_internal</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context, u8 run_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff8198fea0)
Location: drivers/acpi/acpica/evxfregn.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_no_reg
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
```
**Symbols:**

```
ffffffff8198fea0-ffffffff8198fff4: acpi_install_address_space_handler_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context, u8 run_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff819d6940)
Location: drivers/acpi/acpica/evxfregn.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_no_reg
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
```
**Symbols:**

```
ffffffff819d6940-ffffffff819d6a94: acpi_install_address_space_handler_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context, u8 run_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81a21600)
Location: drivers/acpi/acpica/evxfregn.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_no_reg
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
```
**Symbols:**

```
ffffffff81a21600-ffffffff81a21754: acpi_install_address_space_handler_internal (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
