# Function: <code>acpi_debugger_write_log</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: include/linux/acpi.h:172
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: include/linux/acpi.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: include/linux/acpi.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537070)
Location: drivers/acpi/osl.c:896
Inline: False
```
**Symbols:**

```
ffffffff81537070-ffffffff81537119: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156cc30)
Location: drivers/acpi/osl.c:901
Inline: False
```
**Symbols:**

```
ffffffff8156cc30-ffffffff8156ccd9: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584860)
Location: drivers/acpi/osl.c:906
Inline: False
```
**Symbols:**

```
ffffffff81584860-ffffffff81584909: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5470)
Location: drivers/acpi/osl.c:892
Inline: False
```
**Symbols:**

```
ffffffff815b5470-ffffffff815b5519: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d66a0)
Location: drivers/acpi/osl.c:912
Inline: False
```
**Symbols:**

```
ffffffff815d66a0-ffffffff815d6749: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816803a0)
Location: drivers/acpi/osl.c:912
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
```
**Symbols:**

```
ffffffff816803a0-ffffffff81680449: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169ee90)
Location: drivers/acpi/osl.c:916
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
```
**Symbols:**

```
ffffffff8169ee90-ffffffff8169ef39: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681b60)
Location: drivers/acpi/osl.c:917
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
```
**Symbols:**

```
ffffffff81681b60-ffffffff81681c09: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:917
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
```
**Symbols:**

```
ffffffff81ceed80-ffffffff81ceed94: acpi_debugger_write_log.cold (STB_LOCAL)
ffffffff816f6c60-ffffffff816f6d15: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:919
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_printf
```
**Symbols:**

```
ffffffff81eb64fd-ffffffff81eb6511: acpi_debugger_write_log.cold (STB_LOCAL)
ffffffff81823b20-ffffffff81823bdd: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:919
Inline: False
```
**Symbols:**

```
ffffffff8209172f-ffffffff82091743: acpi_debugger_write_log.cold (STB_LOCAL)
ffffffff81954e00-ffffffff81954ebd: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:919
Inline: False
```
**Symbols:**

```
ffffffff821120a2-ffffffff821120b6: acpi_debugger_write_log.cold (STB_LOCAL)
ffffffff8199b200-ffffffff8199b2bd: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:916
Inline: False
```
**Symbols:**

```
ffffffff821efda6-ffffffff821efdba: acpi_debugger_write_log.cold (STB_LOCAL)
ffffffff819e36f0-ffffffff819e37ad: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: include/linux/acpi.h:190
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: include/linux/acpi.h:190
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: include/linux/acpi.h:190
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca980)
Location: drivers/acpi/osl.c:912
Inline: False
```
**Symbols:**

```
ffffffff815ca980-ffffffff815caa29: acpi_debugger_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t acpi_debugger_write_log(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4820)
Location: drivers/acpi/osl.c:912
Inline: False
```
**Symbols:**

```
ffffffff815e4820-ffffffff815e48c9: acpi_debugger_write_log (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
