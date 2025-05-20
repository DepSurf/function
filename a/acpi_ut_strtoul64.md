# Function: <code>acpi_ut_strtoul64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u32 base, u64 *ret_integer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utnonansi.c (ffffffff814a8d85)
Location: drivers/acpi/acpica/utnonansi.c:162
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff814a8d85-ffffffff814a8fc9: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u32 base, u32 max_integer_byte_width, u64 *ret_integer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utnonansi.c (ffffffff814f8051)
Location: drivers/acpi/acpica/utnonansi.c:236
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff814f8051-ffffffff814f825f: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u32 flags, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8151bde8)
Location: drivers/acpi/acpica/utstrtoul64.c:165
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff8151bde8-ffffffff8151bf54: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u32 flags, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8152c5fc)
Location: drivers/acpi/acpica/utstrtoul64.c:165
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff8152c5fc-ffffffff8152c76a: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff81587125)
Location: drivers/acpi/acpica/utstrtoul64.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff81587125-ffffffff8158727a: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff815be2ce)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff815be2ce-ffffffff815be423: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff815d7735)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff815d7735-ffffffff815d788a: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8160913b)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff8160913b-ffffffff81609294: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8162a5dc)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff8162a5dc-ffffffff8162a735: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff816d6db5)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff816d6db5-ffffffff816d6f0e: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff816f4d5b)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff816f4d5b-ffffffff816f4eb4: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff816d6bf8)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff816d6bf8-ffffffff816d6d51: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8174e764)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff8174e764-ffffffff8174e8bd: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8188107e)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff8188107e-ffffffff81881205: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff819c5910)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff819c5910-ffffffff819c5ad6: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff81a0cd10)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff81a0cd10-ffffffff81a0ced6: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff81a57ce0)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff81a57ce0-ffffffff81a57ea6: acpi_ut_strtoul64 (STB_GLOBAL)
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
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffff80001079edb8)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffff80001079edb8-ffff80001079ee9c: acpi_ut_strtoul64 (STB_GLOBAL)
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
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff816016c6)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff816016c6-ffffffff81601779: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff815ecb81)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff815ecb81-ffffffff815ecc34: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8161e8bc)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff8161e8bc-ffffffff8161ea15: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ut_strtoul64(char *string, u64 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8163876c)
Location: drivers/acpi/acpica/utstrtoul64.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
```
**Symbols:**

```
ffffffff8163876c-ffffffff816388c5: acpi_ut_strtoul64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 max_integer_byte_width</code>
</li>
<li>
<b>Param reordered. </b>
<code>string, base, ret_integer</code> ➡️ <code>string, base, max_integer_byte_width, ret_integer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param added. </b>
<code>u64 *return_value</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 base</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 max_integer_byte_width</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *ret_integer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>string, flags, return_value</code> ➡️ <code>string, return_value</code>
</li>
</ul>
</details>
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
