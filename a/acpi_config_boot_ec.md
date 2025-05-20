# Function: <code>acpi_config_boot_ec</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_config_boot_ec(struct acpi_ec *ec, acpi_handle handle, bool handle_events, bool is_ecdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f5867)
Location: drivers/acpi/ec.c:1498
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_ecdt_start
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff814f5867-ffffffff814f5938: acpi_config_boot_ec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_config_boot_ec(struct acpi_ec *ec, acpi_handle handle, bool handle_events, bool is_ecdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81503b50)
Location: drivers/acpi/ec.c:1523
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81503b50-ffffffff81503c3f: acpi_config_boot_ec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_config_boot_ec(struct acpi_ec *ec, acpi_handle handle, bool handle_events, bool is_ecdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81545fc0)
Location: drivers/acpi/ec.c:1524
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81545fc0-ffffffff815460af: acpi_config_boot_ec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_config_boot_ec(struct acpi_ec *ec, acpi_handle handle, bool handle_events, bool is_ecdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157b3f0)
Location: drivers/acpi/ec.c:1530
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff8157b3f0-ffffffff8157b4c1: acpi_config_boot_ec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_config_boot_ec(struct acpi_ec *ec, acpi_handle handle, bool handle_events, bool is_ecdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81593be0)
Location: drivers/acpi/ec.c:1542
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81593be0-ffffffff81593cb1: acpi_config_boot_ec (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
