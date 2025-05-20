# Function: <code>acpi_trace_point</code>

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
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81581f7d)
Location: drivers/acpi/acpica/utdebug.c:617
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81581f7d-ffffffff81581fb7: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b9132)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815b9132-ffffffff815b916c: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d2503)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff815d2503-ffffffff815d253d: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603dfd)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81603dfd-ffffffff81603e37: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816252a7)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816252a7-ffffffff816252e1: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1a48)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816d1a48-ffffffff816d1a82: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816efa26)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816efa26-ffffffff816efa60: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d188b)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff816d188b-ffffffff816d18c5: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81748fe5)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81748fe5-ffffffff8174901f: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187b24a)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff8187b24a-ffffffff8187b290: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819be010)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff819be010-ffffffff819be081: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a05200)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81a05200-ffffffff81a05271: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a500a0)
Location: drivers/acpi/acpica/utdebug.c:602
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81a500a0-ffffffff81a50111: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81619587)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81619587-ffffffff816195c1: acpi_trace_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_trace_point(acpi_trace_event_type type, u8 begin, u8 *aml, char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81633437)
Location: drivers/acpi/acpica/utdebug.c:597
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
**Symbols:**

```
ffffffff81633437-ffffffff81633471: acpi_trace_point (STB_GLOBAL)
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
