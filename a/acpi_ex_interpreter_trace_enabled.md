# Function: <code>acpi_ex_interpreter_trace_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exdebug.c (ffffffff81495039)
Location: drivers/acpi/acpica/exdebug.c:337
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdebug.c:acpi_ex_start_trace_method
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff814e8c4c)
Location: drivers/acpi/acpica/extrace.c:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
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
In drivers/acpi/acpica/extrace.c (ffffffff8150b48e)
Location: drivers/acpi/acpica/extrace.c:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
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
In drivers/acpi/acpica/extrace.c (ffffffff8151babe)
Location: drivers/acpi/acpica/extrace.c:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff8156b740)
Location: drivers/acpi/acpica/extrace.c:74
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff8156b740-ffffffff8156b799: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff815a2398)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815a2398-ffffffff815a23f1: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff815bb058)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815bb058-ffffffff815bb0b1: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff815ecc30)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815ecc30-ffffffff815ecc8b: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff8160dfc5)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff8160dfc5-ffffffff8160e020: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff816ba323)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816ba323-ffffffff816ba37e: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff816d7d1b)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816d7d1b-ffffffff816d7d76: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff816b9caf)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816b9caf-ffffffff816b9d0a: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff81730cff)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81730cff-ffffffff81730d5a: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff818618c4)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff818618c4-ffffffff81861927: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff8199ef55)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff8199eb10-ffffffff8199eb8f: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff819e5c25)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff819e57e0-ffffffff819e585f: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff81a30975)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81a30530-ffffffff81a305af: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
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
In drivers/acpi/acpica/extrace.c (ffff80001078a468)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
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
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff815efded)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815efded-ffffffff815efe48: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff815db3c4)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815db3c4-ffffffff815db41f: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff816022a5)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816022a5-ffffffff81602300: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/extrace.c (ffffffff8161c155)
Location: drivers/acpi/acpica/extrace.c:40
Inline: True
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff8161c155-ffffffff8161c1b0: acpi_ex_interpreter_trace_enabled (STB_LOCAL)
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
