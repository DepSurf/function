# Function: <code>acpi_dev_get_first_match_dev</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6d90)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffffffff815b6d90-ffffffff815b6ea6: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7fc0)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffffffff815d7fc0-ffffffff815d80d6: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81681bc0)
Location: drivers/acpi/utils.c:863
Inline: False
```
**Symbols:**

```
ffffffff81681bc0-ffffffff81681cd6: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0710)
Location: drivers/acpi/utils.c:859
Inline: False
```
**Symbols:**

```
ffffffff816a0710-ffffffff816a0826: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816834a0)
Location: drivers/acpi/utils.c:886
Inline: False
Direct callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816834a0-ffffffff816834bb: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f85f0)
Location: drivers/acpi/utils.c:900
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816f85f0-ffffffff816f860b: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825780)
Location: drivers/acpi/utils.c:900
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81825780-ffffffff818257a7: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956a20)
Location: drivers/acpi/utils.c:962
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81956a20-ffffffff81956a47: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199ce20)
Location: drivers/acpi/utils.c:962
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8199ce20-ffffffff8199ce47: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4e90)
Location: drivers/acpi/utils.c:1008
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff819e4e90-ffffffff819e4eb7: acpi_dev_get_first_match_dev (STB_GLOBAL)
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
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010765590)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffff800010765590-ffff80001076565c: acpi_dev_get_first_match_dev (STB_GLOBAL)
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
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb2f0)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffffffff815cb2f0-ffffffff815cb406: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b4340)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffffffff815b4340-ffffffff815b4456: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc2a0)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffffffff815cc2a0-ffffffff815cc3b6: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct acpi_device *acpi_dev_get_first_match_dev(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e6140)
Location: drivers/acpi/utils.c:806
Inline: False
```
**Symbols:**

```
ffffffff815e6140-ffffffff815e6256: acpi_dev_get_first_match_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
