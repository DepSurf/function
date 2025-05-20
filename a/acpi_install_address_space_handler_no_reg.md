# Function: <code>acpi_install_address_space_handler_no_reg</code>

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
acpi_status acpi_install_address_space_handler_no_reg(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81990050)
Location: drivers/acpi/acpica/evxfregn.c:109
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81990050-ffffffff81990079: acpi_install_address_space_handler_no_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler_no_reg(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff819d6af0)
Location: drivers/acpi/acpica/evxfregn.c:109
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff819d6af0-ffffffff819d6b19: acpi_install_address_space_handler_no_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler_no_reg(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81a217b0)
Location: drivers/acpi/acpica/evxfregn.c:109
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81a217b0-ffffffff81a217d9: acpi_install_address_space_handler_no_reg (STB_GLOBAL)
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
