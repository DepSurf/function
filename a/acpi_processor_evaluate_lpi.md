# Function: <code>acpi_processor_evaluate_lpi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fbb57)
Location: drivers/acpi/processor_idle.c:951
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff814fbb57-ffffffff814fbe2d: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8151e82b)
Location: drivers/acpi/processor_idle.c:952
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8151e82b-ffffffff8151eb01: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8152fc80)
Location: drivers/acpi/processor_idle.c:952
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8152fc80-ffffffff8152ffb7: acpi_processor_evaluate_lpi.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81590910)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81590910-ffffffff81590c90: acpi_processor_evaluate_lpi.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815c7cb0)
Location: drivers/acpi/processor_idle.c:965
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815c7cb0-ffffffff815c8048: acpi_processor_evaluate_lpi.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815e1270)
Location: drivers/acpi/processor_idle.c:966
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815e1270-ffffffff815e1608: acpi_processor_evaluate_lpi.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81612de0)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81612de0-ffffffff81613172: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816342e0)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816342e0-ffffffff81634672: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e1360)
Location: drivers/acpi/processor_idle.c:821
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816e1360-ffffffff816e16e8: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816ff0c0)
Location: drivers/acpi/processor_idle.c:841
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816ff0c0-ffffffff816ff448: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e0c70)
Location: drivers/acpi/processor_idle.c:875
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816e0c70-ffffffff816e0fda: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81758f80)
Location: drivers/acpi/processor_idle.c:876
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81758f80-ffffffff817592db: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188c6b0)
Location: drivers/acpi/processor_idle.c:880
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8188c6b0-ffffffff8188ca06: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d3f50)
Location: drivers/acpi/processor_idle.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff819d3f50-ffffffff819d4296: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1b680)
Location: drivers/acpi/processor_idle.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81a1b680-ffffffff81a1ba27: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a66970)
Location: drivers/acpi/processor_idle.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81a66970-ffffffff81a66d17: acpi_processor_evaluate_lpi (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffff8000107a25d0)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffff8000107a25d0-ffff8000107a294c: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81603e30)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81603e30-ffffffff8160417e: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815eeee0)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815eeee0-ffffffff815ef22e: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816285c0)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816285c0-ffffffff81628952: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81642470)
Location: drivers/acpi/processor_idle.c:961
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81642470-ffffffff81642802: acpi_processor_evaluate_lpi.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
