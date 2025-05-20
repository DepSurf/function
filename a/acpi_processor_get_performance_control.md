# Function: <code>acpi_processor_get_performance_control</code>

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
In drivers/acpi/processor_perflib.c (ffffffff814aef2c)
Location: drivers/acpi/processor_perflib.c:223
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff814fe5f8)
Location: drivers/acpi/processor_perflib.c:223
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff815212ec)
Location: drivers/acpi/processor_perflib.c:221
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81532c73)
Location: drivers/acpi/processor_perflib.c:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81594286)
Location: drivers/acpi/processor_perflib.c:219
Inline: True
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
In drivers/acpi/processor_perflib.c (ffffffff815cbbac)
Location: drivers/acpi/processor_perflib.c:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff815e518c)
Location: drivers/acpi/processor_perflib.c:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81616d7e)
Location: drivers/acpi/processor_perflib.c:206
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff816382de)
Location: drivers/acpi/processor_perflib.c:192
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:192
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff816e4a50-ffffffff816e4baa: acpi_processor_get_performance_control (STB_LOCAL)
ffffffff816e5a7b-ffffffff816e5ac0: acpi_processor_get_performance_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:191
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff817024c0-ffffffff8170261a: acpi_processor_get_performance_control (STB_LOCAL)
ffffffff81c02ce9-ffffffff81c02d2e: acpi_processor_get_performance_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:189
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff816e3da0-ffffffff816e3ef1: acpi_processor_get_performance_control (STB_LOCAL)
ffffffff81bf4730-ffffffff81bf4775: acpi_processor_get_performance_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:189
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff8175ca20-ffffffff8175cb71: acpi_processor_get_performance_control (STB_LOCAL)
ffffffff81cf184d-ffffffff81cf1892: acpi_processor_get_performance_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:189
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81890060-ffffffff81890193: acpi_processor_get_performance_control (STB_LOCAL)
ffffffff81eb97fb-ffffffff81eb982d: acpi_processor_get_performance_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff819d77b0)
Location: drivers/acpi/processor_perflib.c:190
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff819d77b0-ffffffff819d7909: acpi_processor_get_performance_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a1f1b0)
Location: drivers/acpi/processor_perflib.c:212
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81a1f1b0-ffffffff81a1f309: acpi_processor_get_performance_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_get_performance_control(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a6a4d0)
Location: drivers/acpi/processor_perflib.c:212
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81a6a4d0-ffffffff81a6a629: acpi_processor_get_performance_control (STB_LOCAL)
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
In drivers/acpi/processor_perflib.c (ffff8000107a3518)
Location: drivers/acpi/processor_perflib.c:192
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
In drivers/acpi/processor_perflib.c (ffffffff816073de)
Location: drivers/acpi/processor_perflib.c:192
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff815f24de)
Location: drivers/acpi/processor_perflib.c:192
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff8162c5be)
Location: drivers/acpi/processor_perflib.c:192
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff8164645e)
Location: drivers/acpi/processor_perflib.c:192
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
