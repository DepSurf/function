# Function: <code>acpi_ut_ascii_char_to_hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff814a7e4f)
Location: drivers/acpi/acpica/uthex.c:88
Inline: False
```
**Symbols:**

```
ffffffff814a7e4f-ffffffff814a7e6e: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff814f71d0)
Location: drivers/acpi/acpica/uthex.c:88
Inline: False
```
**Symbols:**

```
ffffffff814f71d0-ffffffff814f71ef: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81519d93)
Location: drivers/acpi/acpica/uthex.c:120
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81519d93-ffffffff81519db2: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8152a5c3)
Location: drivers/acpi/acpica/uthex.c:120
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff8152a5c3-ffffffff8152a5e1: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8158390f)
Location: drivers/acpi/acpica/uthex.c:122
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff8158390f-ffffffff8158392d: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815baaac)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff815baaac-ffffffff815baaca: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815d3f06)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff815d3f06-ffffffff815d3f24: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81605885)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff81605885-ffffffff816058a3: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81626d2f)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff81626d2f-ffffffff81626d4d: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff816d34df)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff816d34df-ffffffff816d34fd: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff816f14bd)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff816f14bd-ffffffff816f14db: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff816d3365)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff816d3365-ffffffff816d3383: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8174aba9)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff8174aba9-ffffffff8174abc7: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8187d0d2)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff8187d0d2-ffffffff8187d0f6: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff819c07e7)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Inline callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff819c0850-ffffffff819c0877: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81a079e7)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Inline callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff81a07a50-ffffffff81a07a77: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81a528c7)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Inline callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
Direct callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff81a52930-ffffffff81a52957: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffff80001079c09c)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffff80001079c09c-ffff80001079c0f0: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815ff327)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff815ff327-ffffffff815ff345: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815ea819)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff815ea819-ffffffff815ea837: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8161b00f)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff8161b00f-ffffffff8161b02d: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_ascii_char_to_hex(int hex_char);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81634ebf)
Location: drivers/acpi/acpica/uthex.c:88
Inline: True
Direct callers:
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/uthex.c:acpi_ut_ascii_to_hex_byte
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_insert_digit
```
**Symbols:**

```
ffffffff81634ebf-ffffffff81634edd: acpi_ut_ascii_char_to_hex (STB_GLOBAL)
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
