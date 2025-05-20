# Function: <code>acpi_processor_power_verify</code>

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
In drivers/acpi/processor_idle.c (ffffffff814aca33)
Location: drivers/acpi/processor_idle.c:575
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff814fc2ce)
Location: drivers/acpi/processor_idle.c:540
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff8151efa2)
Location: drivers/acpi/processor_idle.c:541
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81530434)
Location: drivers/acpi/processor_idle.c:541
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81591265)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815c852f)
Location: drivers/acpi/processor_idle.c:547
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815e1aef)
Location: drivers/acpi/processor_idle.c:548
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff8161362c)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81634b2c)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e10c0)
Location: drivers/acpi/processor_idle.c:399
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff816e10c0-ffffffff816e1221: acpi_processor_power_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816fee20)
Location: drivers/acpi/processor_idle.c:391
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff816fee20-ffffffff816fef81: acpi_processor_power_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:412
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff816e0a20-ffffffff816e0be8: acpi_processor_power_verify (STB_LOCAL)
ffffffff81bf446e-ffffffff81bf44a1: acpi_processor_power_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:412
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81758c80-ffffffff81758ef2: acpi_processor_power_verify (STB_LOCAL)
ffffffff81cf13e8-ffffffff81cf1423: acpi_processor_power_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:411
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8188c330-ffffffff8188c5cc: acpi_processor_power_verify (STB_LOCAL)
ffffffff81eb9355-ffffffff81eb938f: acpi_processor_power_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d3b20)
Location: drivers/acpi/processor_idle.c:410
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff819d3b20-ffffffff819d3ddd: acpi_processor_power_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1b260)
Location: drivers/acpi/processor_idle.c:410
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff81a1b260-ffffffff81a1b504: acpi_processor_power_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_power_verify(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a66560)
Location: drivers/acpi/processor_idle.c:410
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff81a66560-ffffffff81a66800: acpi_processor_power_verify (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816045e4)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815ef694)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81628e0c)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81642cbc)
Location: drivers/acpi/processor_idle.c:543
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
