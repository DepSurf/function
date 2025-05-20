# Function: <code>acpi_ps_get_next_field</code>

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
In drivers/acpi/acpica/psargs.c (ffffffff814a0b72)
Location: drivers/acpi/acpica/psargs.c:484
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff814efe5d)
Location: drivers/acpi/acpica/psargs.c:484
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff815128b2)
Location: drivers/acpi/acpica/psargs.c:484
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff81522ff1)
Location: drivers/acpi/acpica/psargs.c:489
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff81577acf)
Location: drivers/acpi/acpica/psargs.c:489
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff815aea31)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff815c7a9b)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff815f940a)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff8161a8b1)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff816c677c)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff816c677c-ffffffff816c6a34: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff816e479e)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff816e479e-ffffffff816e4a56: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff816c6673)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff816c6673-ffffffff816c692b: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff8173d9de)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff8173d9de-ffffffff8173dc96: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff8186f20a)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff8186f20a-ffffffff8186f4ea: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff819af5a0)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff819af5a0-ffffffff819af8c8: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff819f6490)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff819f6490-ffffffff819f67b0: acpi_ps_get_next_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_get_next_field(struct acpi_parse_state *parser_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psargs.c (ffffffff81a412e0)
Location: drivers/acpi/acpica/psargs.c:455
Inline: False
Direct callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
```
**Symbols:**

```
ffffffff81a412e0-ffffffff81a41600: acpi_ps_get_next_field (STB_LOCAL)
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
In drivers/acpi/acpica/psargs.c (ffff800010792104)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff815f7718)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff815e2c57)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff8160eb91)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
In drivers/acpi/acpica/psargs.c (ffffffff81628a41)
Location: drivers/acpi/acpica/psargs.c:455
Inline: True
Inline callers:
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
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
