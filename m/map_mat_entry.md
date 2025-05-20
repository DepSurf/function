# Function: <code>map_mat_entry</code>

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
In drivers/acpi/processor_core.c (ffffffff8148278b)
Location: drivers/acpi/processor_core.c:148
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_phys_id
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
In drivers/acpi/processor_core.c (ffffffff814d1330)
Location: drivers/acpi/processor_core.c:166
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
In drivers/acpi/processor_core.c (ffffffff814f3438)
Location: drivers/acpi/processor_core.c:171
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:__acpi_get_phys_id
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
In drivers/acpi/processor_core.c (ffffffff8150129c)
Location: drivers/acpi/processor_core.c:164
Inline: True
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
In drivers/acpi/processor_core.c (ffffffff815436cc)
Location: drivers/acpi/processor_core.c:164
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
In drivers/acpi/processor_core.c (ffffffff81579651)
Location: drivers/acpi/processor_core.c:164
Inline: True
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
In drivers/acpi/processor_core.c (ffffffff815912d1)
Location: drivers/acpi/processor_core.c:164
Inline: True
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
In drivers/acpi/processor_core.c (ffffffff815c2133)
Location: drivers/acpi/processor_core.c:165
Inline: True
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
In drivers/acpi/processor_core.c (ffffffff815e3413)
Location: drivers/acpi/processor_core.c:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_cpuid_t map_mat_entry(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168e720)
Location: drivers/acpi/processor_core.c:165
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff8168e720-ffffffff8168e84d: map_mat_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_cpuid_t map_mat_entry(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff816ac3f0)
Location: drivers/acpi/processor_core.c:162
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff816ac3f0-ffffffff816ac51d: map_mat_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168eb93)
Location: drivers/acpi/processor_core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff817045a3)
Location: drivers/acpi/processor_core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81832691)
Location: drivers/acpi/processor_core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81965f31)
Location: drivers/acpi/processor_core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff819ac4c1)
Location: drivers/acpi/processor_core.c:191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_cpuid_t map_mat_entry(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff819f65a0)
Location: drivers/acpi/processor_core.c:218
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff819f65a0-ffffffff819f66f7: map_mat_entry (STB_LOCAL)
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
In drivers/acpi/processor_core.c (ffff80001076fab0)
Location: drivers/acpi/processor_core.c:165
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
In drivers/acpi/processor_core.c (ffffffff815d5353)
Location: drivers/acpi/processor_core.c:165
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
In drivers/acpi/processor_core.c (ffffffff815bef13)
Location: drivers/acpi/processor_core.c:165
Inline: True
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
In drivers/acpi/processor_core.c (ffffffff815d76f3)
Location: drivers/acpi/processor_core.c:165
Inline: True
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
In drivers/acpi/processor_core.c (ffffffff815f15b3)
Location: drivers/acpi/processor_core.c:165
Inline: True
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
