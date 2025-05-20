# Function: <code>acpi_dev_get_next_match_dev</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_next_match_dev(struct acpi_device *adev, const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81683290)
Location: drivers/acpi/utils.c:856
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81683290-ffffffff8168349c: acpi_dev_get_next_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_next_match_dev(struct acpi_device *adev, const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f83e0)
Location: drivers/acpi/utils.c:870
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816f83e0-ffffffff816f85ec: acpi_dev_get_next_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_next_match_dev(struct acpi_device *adev, const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825570)
Location: drivers/acpi/utils.c:870
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81825570-ffffffff81825773: acpi_dev_get_next_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_next_match_dev(struct acpi_device *adev, const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819568f0)
Location: drivers/acpi/utils.c:932
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff819568f0-ffffffff81956a0f: acpi_dev_get_next_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_next_match_dev(struct acpi_device *adev, const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199ccf0)
Location: drivers/acpi/utils.c:932
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8199ccf0-ffffffff8199ce0f: acpi_dev_get_next_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_next_match_dev(struct acpi_device *adev, const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4d60)
Location: drivers/acpi/utils.c:978
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff819e4d60-ffffffff819e4e7f: acpi_dev_get_next_match_dev (STB_GLOBAL)
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
