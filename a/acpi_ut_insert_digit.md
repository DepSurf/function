# Function: <code>acpi_ut_insert_digit</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81586e43)
Location: drivers/acpi/acpica/utstrsuppt.c:333
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff81586e43-ffffffff81586f11: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815bdfec)
Location: drivers/acpi/acpica/utstrsuppt.c:296
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff815bdfec-ffffffff815be0b6: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815d7437)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff815d7437-ffffffff815d7501: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81608e26)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff81608e26-ffffffff81608efd: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8162a2cb)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff8162a2cb-ffffffff8162a3a2: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816d6aaa)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff816d6aaa-ffffffff816d6b7b: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816f4a55)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff816f4a55-ffffffff816f4b26: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816d68f5)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff816d68f5-ffffffff816d69c3: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8174e461)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff8174e461-ffffffff8174e52f: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81880d1e)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff81880d1e-ffffffff81880df9: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff819c53d0)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff819c53d0-ffffffff819c54b5: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81a0c7d0)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff81a0c7d0-ffffffff81a0c8b5: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81a577a0)
Location: drivers/acpi/acpica/utstrsuppt.c:331
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff81a577a0-ffffffff81a57885: acpi_ut_insert_digit (STB_LOCAL)
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
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffff80001079e974)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffff80001079e974-ffff80001079ea68: acpi_ut_insert_digit (STB_LOCAL)
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
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816013b5)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff816013b5-ffffffff8160148c: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815ec870)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff815ec870-ffffffff815ec947: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8161e5ab)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff8161e5ab-ffffffff8161e682: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ut_insert_digit(u64 *accumulated_value, u32 base, int ascii_digit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8163845b)
Location: drivers/acpi/acpica/utstrsuppt.c:316
Inline: False
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_hex_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_octal_string
```
**Symbols:**

```
ffffffff8163845b-ffffffff81638532: acpi_ut_insert_digit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
