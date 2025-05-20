# Function: <code>acpi_ut_hex_to_ascii_char</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff814a7e35)
Location: drivers/acpi/acpica/uthex.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
```
**Symbols:**

```
ffffffff814a7e35-ffffffff814a7e4f: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff814f71b6)
Location: drivers/acpi/acpica/uthex.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff814f71b6-ffffffff814f71d0: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81519d79)
Location: drivers/acpi/acpica/uthex.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff81519d79-ffffffff81519d93: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8152a5a9)
Location: drivers/acpi/acpica/uthex.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff8152a5a9-ffffffff8152a5c3: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815838c7)
Location: drivers/acpi/acpica/uthex.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff815838c7-ffffffff8158390f: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815baa64)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff815baa64-ffffffff815baaac: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815d3ebe)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff815d3ebe-ffffffff815d3f06: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8160583d)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff8160583d-ffffffff81605885: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81626ce7)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff81626ce7-ffffffff81626d2f: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff816d3497)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff816d3497-ffffffff816d34df: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff816f1475)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff816f1475-ffffffff816f14bd: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff816d331d)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff816d331d-ffffffff816d3365: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8174ab61)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff8174ab61-ffffffff8174aba9: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8187d07a)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff8187d07a-ffffffff8187d0d2: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff819c0740)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff819c0740-ffffffff819c079b: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81a07940)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff81a07940-ffffffff81a0799b: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81a52820)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff81a52820-ffffffff81a5287b: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
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
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffff80001079c024)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffff80001079c024-ffff80001079c09c: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
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
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815ff2df)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff815ff2df-ffffffff815ff327: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff815ea7d1)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff815ea7d1-ffffffff815ea819: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff8161afc7)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff8161afc7-ffffffff8161b00f: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char acpi_ut_hex_to_ascii_char(u64 integer, u32 position);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uthex.c (ffffffff81634e77)
Location: drivers/acpi/acpica/uthex.c:36
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
```
**Symbols:**

```
ffffffff81634e77-ffffffff81634ebf: acpi_ut_hex_to_ascii_char (STB_GLOBAL)
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
