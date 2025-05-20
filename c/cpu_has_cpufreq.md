# Function: <code>cpu_has_cpufreq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff814ae61a)
Location: drivers/acpi/processor_thermal.c:74
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff814ae61a-ffffffff814ae665: cpu_has_cpufreq.part.2 (STB_LOCAL)
ffffffff814ae665-ffffffff814ae681: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff814fdfe3)
Location: drivers/acpi/processor_thermal.c:74
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff814fdfe3-ffffffff814fe02e: cpu_has_cpufreq.part.2 (STB_LOCAL)
ffffffff814fe02e-ffffffff814fe04a: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81520cdc)
Location: drivers/acpi/processor_thermal.c:74
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff81520cdc-ffffffff81520d27: cpu_has_cpufreq.part.2 (STB_LOCAL)
ffffffff81520d27-ffffffff81520d43: cpu_has_cpufreq (STB_LOCAL)
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
In drivers/acpi/processor_thermal.c (ffffffff8153284e)
Location: drivers/acpi/processor_thermal.c:74
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff815325f0-ffffffff8153263b: cpu_has_cpufreq.part.3 (STB_LOCAL)
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
In drivers/acpi/processor_thermal.c (ffffffff81593dfe)
Location: drivers/acpi/processor_thermal.c:74
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff81593ba0-ffffffff81593beb: cpu_has_cpufreq.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff815caf90)
Location: drivers/acpi/processor_thermal.c:74
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff815caf90-ffffffff815cafe5: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff815e4570)
Location: drivers/acpi/processor_thermal.c:74
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff815e4570-ffffffff815e45c5: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81616140)
Location: drivers/acpi/processor_thermal.c:61
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff81616140-ffffffff81616195: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81637630)
Location: drivers/acpi/processor_thermal.c:60
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff81637630-ffffffff81637684: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff816e4390)
Location: drivers/acpi/processor_thermal.c:60
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
```
**Symbols:**

```
ffffffff816e4390-ffffffff816e43e4: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81701e50)
Location: drivers/acpi/processor_thermal.c:56
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
```
**Symbols:**

```
ffffffff81701e50-ffffffff81701ea4: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff816e3730)
Location: drivers/acpi/processor_thermal.c:56
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
```
**Symbols:**

```
ffffffff816e3730-ffffffff816e3784: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:54
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
```
**Symbols:**

```
ffffffff8175c220-ffffffff8175c293: cpu_has_cpufreq (STB_LOCAL)
ffffffff81cf17f3-ffffffff81cf1807: cpu_has_cpufreq.cold (STB_LOCAL)
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
In drivers/acpi/processor_thermal.c (ffffffff8188fc01)
Location: drivers/acpi/processor_thermal.c:54
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
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
In drivers/acpi/processor_thermal.c (ffffffff819d32b1)
Location: drivers/acpi/processor_thermal.c:54
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
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
In drivers/acpi/processor_thermal.c (ffffffff81a1a8d1)
Location: drivers/acpi/processor_thermal.c:54
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
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
In drivers/acpi/processor_thermal.c (ffffffff81a65bd1)
Location: drivers/acpi/processor_thermal.c:65
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
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
<summary>In <code>aws</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81606860)
Location: drivers/acpi/processor_thermal.c:60
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff81606860-ffffffff816068b4: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff815f1930)
Location: drivers/acpi/processor_thermal.c:60
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff815f1930-ffffffff815f1984: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff8162b910)
Location: drivers/acpi/processor_thermal.c:60
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff8162b910-ffffffff8162b964: cpu_has_cpufreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_has_cpufreq(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff816457b0)
Location: drivers/acpi/processor_thermal.c:60
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:acpi_processor_max_state
```
**Symbols:**

```
ffffffff816457b0-ffffffff81645804: cpu_has_cpufreq (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
