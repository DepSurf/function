# Function: <code>acpi_os_vprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479dac)
Location: drivers/acpi/osl.c:225
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_error
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
```
**Symbols:**

```
ffffffff81479dac-ffffffff81479ddc: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c839f)
Location: drivers/acpi/osl.c:156
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff814c839f-ffffffff814c83cf: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea2af)
Location: drivers/acpi/osl.c:157
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff814ea2af-ffffffff814ea313: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6060)
Location: drivers/acpi/osl.c:156
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff814f6060-ffffffff814f60d0: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537120)
Location: drivers/acpi/osl.c:156
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81537120-ffffffff815371a3: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:158
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff8156d848-ffffffff8156d8a3: acpi_os_vprintf.cold.21 (STB_LOCAL)
ffffffff8156cce0-ffffffff8156cd12: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81585408)
Location: drivers/acpi/osl.c:158
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81585408-ffffffff81585463: acpi_os_vprintf.cold.22 (STB_LOCAL)
ffffffff81584910-ffffffff81584942: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b6073)
Location: drivers/acpi/osl.c:144
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff815b6073-ffffffff815b60c3: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff815b5520-ffffffff815b5552: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d72a3)
Location: drivers/acpi/osl.c:147
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff815d72a3-ffffffff815d72f3: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff815d6750-ffffffff815d6782: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816804ed)
Location: drivers/acpi/osl.c:147
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_printf
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81680f28-ffffffff81680f7c: acpi_os_vprintf.part.0 (STB_LOCAL)
ffffffff8168106b-ffffffff81681075: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff81680450-ffffffff81680482: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169efdd)
Location: drivers/acpi/osl.c:150
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_printf
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81c00890-ffffffff81c008e4: acpi_os_vprintf.part.0 (STB_LOCAL)
ffffffff81c009d3-ffffffff81c009dd: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff8169ef40-ffffffff8169ef72: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681cb2)
Location: drivers/acpi/osl.c:153
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_printf
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81bf237c-ffffffff81bf23d0: acpi_os_vprintf.part.0 (STB_LOCAL)
ffffffff81bf24c8-ffffffff81bf24d8: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff81681c10-ffffffff81681c50: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f6dc2)
Location: drivers/acpi/osl.c:153
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_printf
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81ceec0a-ffffffff81ceec5e: acpi_os_vprintf.part.0 (STB_LOCAL)
ffffffff81ceed94-ffffffff81ceeda4: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff816f6d20-ffffffff816f6d60: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81823c85)
Location: drivers/acpi/osl.c:152
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_printf
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81eb636c-ffffffff81eb63ca: acpi_os_vprintf.part.0 (STB_LOCAL)
ffffffff81eb6511-ffffffff81eb651b: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff81823be0-ffffffff81823c1e: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81954ed0)
Location: drivers/acpi/osl.c:152
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff81954ed0-ffffffff81954f6e: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199b2d0)
Location: drivers/acpi/osl.c:152
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff8199b2d0-ffffffff8199b36e: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e37c0)
Location: drivers/acpi/osl.c:152
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff819e37c0-ffffffff819e385e: acpi_os_vprintf (STB_GLOBAL)
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
void acpi_os_vprintf(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff8000107647ec)
Location: drivers/acpi/osl.c:147
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffff8000107647ec-ffff80001076489c: acpi_os_vprintf (STB_GLOBAL)
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
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca75d)
Location: drivers/acpi/osl.c:147
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff815ca75d-ffffffff815ca7c3: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b37dd)
Location: drivers/acpi/osl.c:147
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff815b37dd-ffffffff815b3843: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb583)
Location: drivers/acpi/osl.c:147
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff815cb583-ffffffff815cb5d3: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff815caa30-ffffffff815caa62: acpi_os_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_os_vprintf(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e5423)
Location: drivers/acpi/osl.c:147
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info
  - drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_warning
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_bios_error
  - drivers/acpi/acpica/utxferror.c:acpi_info
  - drivers/acpi/acpica/utxferror.c:acpi_warning
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/utxferror.c:acpi_error
```
**Symbols:**

```
ffffffff815e5423-ffffffff815e5473: acpi_os_vprintf.cold (STB_LOCAL)
ffffffff815e48d0-ffffffff815e4902: acpi_os_vprintf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
