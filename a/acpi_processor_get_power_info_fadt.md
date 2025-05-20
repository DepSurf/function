# Function: <code>acpi_processor_get_power_info_fadt</code>

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
In drivers/acpi/processor_idle.c (ffffffff814ac784)
Location: drivers/acpi/processor_idle.c:257
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
In drivers/acpi/processor_idle.c (ffffffff814fc23d)
Location: drivers/acpi/processor_idle.c:225
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
In drivers/acpi/processor_idle.c (ffffffff8151ef11)
Location: drivers/acpi/processor_idle.c:226
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
In drivers/acpi/processor_idle.c (ffffffff81530664)
Location: drivers/acpi/processor_idle.c:226
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
In drivers/acpi/processor_idle.c (ffffffff81591130)
Location: drivers/acpi/processor_idle.c:228
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
In drivers/acpi/processor_idle.c (ffffffff815c8852)
Location: drivers/acpi/processor_idle.c:229
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
In drivers/acpi/processor_idle.c (ffffffff815e1e15)
Location: drivers/acpi/processor_idle.c:230
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
In drivers/acpi/processor_idle.c (ffffffff816138dd)
Location: drivers/acpi/processor_idle.c:218
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
In drivers/acpi/processor_idle.c (ffffffff81634ddd)
Location: drivers/acpi/processor_idle.c:218
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
int acpi_processor_get_power_info_fadt(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e0d00)
Location: drivers/acpi/processor_idle.c:218
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff816e0d00-ffffffff816e0eee: acpi_processor_get_power_info_fadt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_processor_get_power_info_fadt(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816fea70)
Location: drivers/acpi/processor_idle.c:210
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff816fea70-ffffffff816fec4d: acpi_processor_get_power_info_fadt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_processor_get_power_info_fadt(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e0790)
Location: drivers/acpi/processor_idle.c:208
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff816e0790-ffffffff816e08c6: acpi_processor_get_power_info_fadt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_processor_get_power_info_fadt(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81758a10)
Location: drivers/acpi/processor_idle.c:208
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81758a10-ffffffff81758b40: acpi_processor_get_power_info_fadt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_processor_get_power_info_fadt(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188c070)
Location: drivers/acpi/processor_idle.c:210
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8188c070-ffffffff8188c1bd: acpi_processor_get_power_info_fadt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_get_power_info_fadt(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d3840)
Location: drivers/acpi/processor_idle.c:211
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
**Symbols:**

```
ffffffff819d3840-ffffffff819d398d: acpi_processor_get_power_info_fadt (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff81a1c2b6)
Location: drivers/acpi/processor_idle.c:211
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a67596)
Location: drivers/acpi/processor_idle.c:211
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
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
In drivers/acpi/processor_idle.c (ffffffff81604807)
Location: drivers/acpi/processor_idle.c:218
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
In drivers/acpi/processor_idle.c (ffffffff815ef8b7)
Location: drivers/acpi/processor_idle.c:218
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
In drivers/acpi/processor_idle.c (ffffffff816290bd)
Location: drivers/acpi/processor_idle.c:218
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
In drivers/acpi/processor_idle.c (ffffffff81642f6d)
Location: drivers/acpi/processor_idle.c:218
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
</ul>
