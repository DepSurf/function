# Function: <code>acpi_dev_uid_to_integer</code>

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
int acpi_dev_uid_to_integer(struct acpi_device *adev, u64 *integer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956700)
Location: drivers/acpi/utils.c:805
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81956700-ffffffff81956750: acpi_dev_uid_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dev_uid_to_integer(struct acpi_device *adev, u64 *integer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199cb00)
Location: drivers/acpi/utils.c:805
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8199cb00-ffffffff8199cb50: acpi_dev_uid_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dev_uid_to_integer(struct acpi_device *adev, u64 *integer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4b70)
Location: drivers/acpi/utils.c:852
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff819e4b70-ffffffff819e4bc0: acpi_dev_uid_to_integer (STB_GLOBAL)
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
