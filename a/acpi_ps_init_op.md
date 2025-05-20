# Function: <code>acpi_ps_init_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff814a23e4)
Location: drivers/acpi/acpica/psutils.c:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
```
**Symbols:**

```
ffffffff814a23e4-ffffffff814a23f7: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff814f1765)
Location: drivers/acpi/acpica/psutils.c:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff814f1711-ffffffff814f1724: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815141c6)
Location: drivers/acpi/acpica/psutils.c:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff81514172-ffffffff81514185: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8152497e)
Location: drivers/acpi/acpica/psutils.c:90
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8152490e-ffffffff81524921: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8157a557)
Location: drivers/acpi/acpica/psutils.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff8157a557-ffffffff8157a596: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815b164b)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff815b164b-ffffffff815b168a: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815ca78b)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff815ca78b-ffffffff815ca7ca: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815fbf3a)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff815fbf3a-ffffffff815fbf79: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8161d3e4)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff8161d3e4-ffffffff8161d423: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816c996d)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff816c996d-ffffffff816c99ac: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816e7993)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff816e7993-ffffffff816e79d2: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816c9856)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff816c9856-ffffffff816c9895: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81740bf8)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff81740bf8-ffffffff81740c37: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81872599)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff81872599-ffffffff818725e4: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff819b3437)
Location: drivers/acpi/acpica/psutils.c:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff819b3360-ffffffff819b33ab: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff819fa337)
Location: drivers/acpi/acpica/psutils.c:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff819fa260-ffffffff819fa2ab: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81a45187)
Location: drivers/acpi/acpica/psutils.c:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff81a450b0-ffffffff81a450fb: acpi_ps_init_op (STB_GLOBAL)
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
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffff800010793db8)
Location: drivers/acpi/acpica/psutils.c:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffff800010793d34-ffff800010793d68: acpi_ps_init_op (STB_GLOBAL)
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
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815f9220)
Location: drivers/acpi/acpica/psutils.c:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815f91b4-ffffffff815f91c7: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815e475a)
Location: drivers/acpi/acpica/psutils.c:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815e46ee-ffffffff815e4701: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816116c4)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff816116c4-ffffffff81611703: acpi_ps_init_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ps_init_op(union acpi_parse_object *op, u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8162b574)
Location: drivers/acpi/acpica/psutils.c:56
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff8162b574-ffffffff8162b5b3: acpi_ps_init_op (STB_GLOBAL)
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
