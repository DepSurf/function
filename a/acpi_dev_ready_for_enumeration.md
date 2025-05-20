# Function: <code>acpi_dev_ready_for_enumeration</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_ready_for_enumeration(const struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182daa2)
Location: drivers/acpi/scan.c:2375
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8182c720-ffffffff8182c752: acpi_dev_ready_for_enumeration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_ready_for_enumeration(const struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960889)
Location: drivers/acpi/scan.c:2372
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8195f380-ffffffff8195f3ac: acpi_dev_ready_for_enumeration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_ready_for_enumeration(const struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6b99)
Location: drivers/acpi/scan.c:2379
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff819a5780-ffffffff819a57ac: acpi_dev_ready_for_enumeration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_ready_for_enumeration(const struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ef5b9)
Location: drivers/acpi/scan.c:2412
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff819ee100-ffffffff819ee12c: acpi_dev_ready_for_enumeration (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
