# Function: <code>acpi_thermal_cpufreq_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff814ae9c6)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
```
**Symbols:**

```
ffffffff814ae9c6-ffffffff814ae9f0: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff814fe38f)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
```
**Symbols:**

```
ffffffff814fe38f-ffffffff814fe3b9: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81521083)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
```
**Symbols:**

```
ffffffff81521083-ffffffff815210ad: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81532900)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
```
**Symbols:**

```
ffffffff81532900-ffffffff8153292a: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81593eb0)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
```
**Symbols:**

```
ffffffff81593eb0-ffffffff81593eda: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff815cb330)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
**Symbols:**

```
ffffffff815cb330-ffffffff815cb35a: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff815e4910)
Location: drivers/acpi/processor_thermal.c:144
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
**Symbols:**

```
ffffffff815e4910-ffffffff815e493a: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff816164f0)
Location: drivers/acpi/processor_thermal.c:131
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
**Symbols:**

```
ffffffff816164f0-ffffffff8161651a: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:128
Inline: False
```
**Symbols:**

```
ffffffff81637b17-ffffffff81637b2d: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff81637a20-ffffffff81637a9d: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:128
Inline: False
```
**Symbols:**

```
ffffffff816e4887-ffffffff816e489d: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff816e4790-ffffffff816e480d: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:124
Inline: False
```
**Symbols:**

```
ffffffff81c02cbb-ffffffff81c02cd1: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff81702250-ffffffff817022cd: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:124
Inline: False
```
**Symbols:**

```
ffffffff81bf46fe-ffffffff81bf4718: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff816e3b20-ffffffff816e3ba9: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:122
Inline: False
```
**Symbols:**

```
ffffffff81cf181f-ffffffff81cf1835: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff8175c750-ffffffff8175c7eb: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:129
Inline: False
```
**Symbols:**

```
ffffffff81eb97d0-ffffffff81eb97e5: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff8188fd60-ffffffff8188fe06: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff819d3420)
Location: drivers/acpi/processor_thermal.c:129
Inline: False
```
**Symbols:**

```
ffffffff819d3420-ffffffff819d34ed: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81a1aa40)
Location: drivers/acpi/processor_thermal.c:129
Inline: False
```
**Symbols:**

```
ffffffff81a1aa40-ffffffff81a1ab17: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81a65d40)
Location: drivers/acpi/processor_thermal.c:158
Inline: False
```
**Symbols:**

```
ffffffff81a65d40-ffffffff81a65e17: acpi_thermal_cpufreq_init (STB_GLOBAL)
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
In drivers/acpi/processor_driver.c (0)
Location: include/acpi/processor.h:437
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:128
Inline: False
```
**Symbols:**

```
ffffffff81606d47-ffffffff81606d5d: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff81606c50-ffffffff81606ccd: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:128
Inline: False
```
**Symbols:**

```
ffffffff815f1e17-ffffffff815f1e2d: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff815f1d20-ffffffff815f1d9d: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:128
Inline: False
```
**Symbols:**

```
ffffffff8162bdf7-ffffffff8162be0d: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff8162bd00-ffffffff8162bd7d: acpi_thermal_cpufreq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_thermal_cpufreq_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_thermal.c (0)
Location: drivers/acpi/processor_thermal.c:128
Inline: False
```
**Symbols:**

```
ffffffff81645c97-ffffffff81645cad: acpi_thermal_cpufreq_init.cold (STB_LOCAL)
ffffffff81645ba0-ffffffff81645c1d: acpi_thermal_cpufreq_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpufreq_policy *policy</code>
</li>
</ul>
</details>
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
