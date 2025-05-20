# Function: <code>acpi_debugger_read_cmd</code>

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
Location: include/linux/acpi.h:177
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
Location: include/linux/acpi.h:200
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
Location: include/linux/acpi.h:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537220)
Location: drivers/acpi/osl.c:926
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff81537220-ffffffff815372d3: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156cd90)
Location: drivers/acpi/osl.c:931
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff8156cd90-ffffffff8156ce43: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815849c0)
Location: drivers/acpi/osl.c:936
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff815849c0-ffffffff81584a73: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b55d0)
Location: drivers/acpi/osl.c:922
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff815b55d0-ffffffff815b5683: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6800)
Location: drivers/acpi/osl.c:942
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff815d6800-ffffffff815d68b3: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680520)
Location: drivers/acpi/osl.c:942
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff81680520-ffffffff816805d3: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f010)
Location: drivers/acpi/osl.c:946
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff8169f010-ffffffff8169f0c3: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681cf0)
Location: drivers/acpi/osl.c:947
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff81681cf0-ffffffff81681da3: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:947
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff81ceedb4-ffffffff81ceedc8: acpi_debugger_read_cmd.cold (STB_LOCAL)
ffffffff816f6e00-ffffffff816f6ebf: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:949
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff81eb6525-ffffffff81eb6539: acpi_debugger_read_cmd.cold (STB_LOCAL)
ffffffff81823cd0-ffffffff81823d97: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:949
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff82091743-ffffffff82091757: acpi_debugger_read_cmd.cold (STB_LOCAL)
ffffffff81955020-ffffffff819550e7: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:949
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff821120b6-ffffffff821120ca: acpi_debugger_read_cmd.cold (STB_LOCAL)
ffffffff8199b420-ffffffff8199b4e7: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:946
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff821efdba-ffffffff821efdce: acpi_debugger_read_cmd.cold (STB_LOCAL)
ffffffff819e3910-ffffffff819e39d7: acpi_debugger_read_cmd (STB_GLOBAL)
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
Location: include/linux/acpi.h:195
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
Location: include/linux/acpi.h:195
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
Location: include/linux/acpi.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815caae0)
Location: drivers/acpi/osl.c:942
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff815caae0-ffffffff815cab93: acpi_debugger_read_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char *buffer, size_t buffer_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4980)
Location: drivers/acpi/osl.c:942
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_line
```
**Symbols:**

```
ffffffff815e4980-ffffffff815e4a33: acpi_debugger_read_cmd (STB_GLOBAL)
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
