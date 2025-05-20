# Function: <code>acpi_processor_evaluate_cst</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff8168d7a0)
Location: drivers/acpi/acpi_processor.c:747
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff8168d7a0-ffffffff8168db0b: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff816ab450)
Location: drivers/acpi/acpi_processor.c:746
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff816ab450-ffffffff816ab8ec: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff8168dcb0)
Location: drivers/acpi/acpi_processor.c:729
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8168dcb0-ffffffff8168e14e: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff81703470)
Location: drivers/acpi/acpi_processor.c:729
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81703470-ffffffff81703945: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff818314a0)
Location: drivers/acpi/acpi_processor.c:729
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff818314a0-ffffffff81831982: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff81964bb0)
Location: drivers/acpi/acpi_processor.c:729
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff81964bb0-ffffffff81965092: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff819ab070)
Location: drivers/acpi/acpi_processor.c:767
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff819ab070-ffffffff819ab549: acpi_processor_evaluate_cst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff819f54a0)
Location: drivers/acpi/acpi_processor.c:810
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff819f54a0-ffffffff819f5979: acpi_processor_evaluate_cst (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
