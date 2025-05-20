# Function: <code>acpi_debugger_wait_command_ready</code>

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
Location: include/linux/acpi.h:182
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
Location: include/linux/acpi.h:205
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
Location: include/linux/acpi.h:210
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537310)
Location: drivers/acpi/osl.c:956
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff81537310-ffffffff815373c2: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156ce80)
Location: drivers/acpi/osl.c:961
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff8156ce80-ffffffff8156cf32: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584ab0)
Location: drivers/acpi/osl.c:966
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff81584ab0-ffffffff81584b62: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b56c0)
Location: drivers/acpi/osl.c:952
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff815b56c0-ffffffff815b5778: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d68f0)
Location: drivers/acpi/osl.c:972
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff815d68f0-ffffffff815d69a8: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680620)
Location: drivers/acpi/osl.c:972
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff81680620-ffffffff816806d8: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f110)
Location: drivers/acpi/osl.c:976
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff8169f110-ffffffff8169f1c8: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681df0)
Location: drivers/acpi/osl.c:977
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff81681df0-ffffffff81681ea8: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:977
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff81ceedc8-ffffffff81ceeddc: acpi_debugger_wait_command_ready.cold (STB_LOCAL)
ffffffff816f6f00-ffffffff816f6fc6: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:979
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff81eb6539-ffffffff81eb654d: acpi_debugger_wait_command_ready.cold (STB_LOCAL)
ffffffff81823de0-ffffffff81823ea8: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:979
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff82091757-ffffffff8209176b: acpi_debugger_wait_command_ready.cold (STB_LOCAL)
ffffffff81955150-ffffffff81955218: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:979
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff821120ca-ffffffff821120de: acpi_debugger_wait_command_ready.cold (STB_LOCAL)
ffffffff8199b550-ffffffff8199b618: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:976
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff821efdce-ffffffff821efde2: acpi_debugger_wait_command_ready.cold (STB_LOCAL)
ffffffff819e3a40-ffffffff819e3b08: acpi_debugger_wait_command_ready (STB_GLOBAL)
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
Location: include/linux/acpi.h:200
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
Location: include/linux/acpi.h:200
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
Location: include/linux/acpi.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cabd0)
Location: drivers/acpi/osl.c:972
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff815cabd0-ffffffff815cac88: acpi_debugger_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4a70)
Location: drivers/acpi/osl.c:972
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_command_ready
```
**Symbols:**

```
ffffffff815e4a70-ffffffff815e4b28: acpi_debugger_wait_command_ready (STB_GLOBAL)
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
