# Function: <code>acpi_ps_get_arguments</code>

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
In drivers/acpi/acpica/psloop.c (ffffffff814a10d2)
Location: drivers/acpi/acpica/psloop.c:86
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
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
In drivers/acpi/acpica/psloop.c (ffffffff814f03d5)
Location: drivers/acpi/acpica/psloop.c:86
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
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
In drivers/acpi/acpica/psloop.c (ffffffff81512e2a)
Location: drivers/acpi/acpica/psloop.c:86
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
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
In drivers/acpi/acpica/psloop.c (ffffffff81523630)
Location: drivers/acpi/acpica/psloop.c:87
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff8157837a)
Location: drivers/acpi/acpica/psloop.c:87
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff815af35d)
Location: drivers/acpi/acpica/psloop.c:54
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff815c83e5)
Location: drivers/acpi/acpica/psloop.c:54
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff815f9d8d)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff8161b234)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ps_get_arguments(struct acpi_walk_state *walk_state, u8 *aml_op_start, union acpi_parse_object *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff816c73ec)
Location: drivers/acpi/acpica/psloop.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff816c73ec-ffffffff816c76c8: acpi_ps_get_arguments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ps_get_arguments(struct acpi_walk_state *walk_state, u8 *aml_op_start, union acpi_parse_object *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff816e540e)
Location: drivers/acpi/acpica/psloop.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff816e540e-ffffffff816e56ea: acpi_ps_get_arguments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff816c72f1)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff816c72f1-ffffffff816c75cd: acpi_ps_get_arguments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff8173e65c)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff8173e65c-ffffffff8173e938: acpi_ps_get_arguments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff8186fed5)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff8186fed5-ffffffff818701c4: acpi_ps_get_arguments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff819b04e0)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff819b04e0-ffffffff819b0841: acpi_ps_get_arguments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff819f73e0)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff819f73e0-ffffffff819f773a: acpi_ps_get_arguments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff81a42230)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff81a42230-ffffffff81a4258a: acpi_ps_get_arguments.constprop.0 (STB_LOCAL)
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
In drivers/acpi/acpica/psloop.c (ffff800010792720)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
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
In drivers/acpi/acpica/psloop.c (ffffffff815f7c70)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
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
In drivers/acpi/acpica/psloop.c (ffffffff815e31af)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff8160f514)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psloop.c (ffffffff816293c4)
Location: drivers/acpi/acpica/psloop.c:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
