# Function: <code>acpi_debugger_create_thread</code>

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
Location: include/linux/acpi.h:166
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
Location: include/linux/acpi.h:189
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
Location: include/linux/acpi.h:194
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536e60)
Location: drivers/acpi/osl.c:866
Inline: False
```
**Symbols:**

```
ffffffff81536e60-ffffffff81536f0c: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156ca60)
Location: drivers/acpi/osl.c:871
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff8156ca60-ffffffff8156cb0c: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584690)
Location: drivers/acpi/osl.c:876
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff81584690-ffffffff8158473c: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b52a0)
Location: drivers/acpi/osl.c:862
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff815b52a0-ffffffff815b5350: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d64d0)
Location: drivers/acpi/osl.c:882
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff815d64d0-ffffffff815d6580: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816801d0)
Location: drivers/acpi/osl.c:882
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff816801d0-ffffffff81680280: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169ecc0)
Location: drivers/acpi/osl.c:886
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff8169ecc0-ffffffff8169ed70: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681970)
Location: drivers/acpi/osl.c:887
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff81681970-ffffffff81681a20: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:887
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff81ceed27-ffffffff81ceed3b: acpi_debugger_create_thread.cold (STB_LOCAL)
ffffffff816f6a60-ffffffff816f6b1c: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:889
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff81eb64ac-ffffffff81eb64c0: acpi_debugger_create_thread.cold (STB_LOCAL)
ffffffff81823930-ffffffff818239f0: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:889
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff8209171b-ffffffff8209172f: acpi_debugger_create_thread.cold (STB_LOCAL)
ffffffff81954bc0-ffffffff81954c80: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:889
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff8211208e-ffffffff821120a2: acpi_debugger_create_thread.cold (STB_LOCAL)
ffffffff8199afc0-ffffffff8199b080: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:886
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff821efd92-ffffffff821efda6: acpi_debugger_create_thread.cold (STB_LOCAL)
ffffffff819e3440-ffffffff819e3500: acpi_debugger_create_thread (STB_GLOBAL)
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
Location: include/linux/acpi.h:184
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
Location: include/linux/acpi.h:184
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
Location: include/linux/acpi.h:184
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca7b0)
Location: drivers/acpi/osl.c:882
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff815ca7b0-ffffffff815ca860: acpi_debugger_create_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4650)
Location: drivers/acpi/osl.c:882
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_execute
```
**Symbols:**

```
ffffffff815e4650-ffffffff815e4700: acpi_debugger_create_thread (STB_GLOBAL)
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
