# Function: <code>acpi_processor_pstate_control</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81521e05)
Location: drivers/acpi/processor_perflib.c:467
Inline: False
```
**Symbols:**

```
ffffffff81521e05-ffffffff81521e69: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815338b0)
Location: drivers/acpi/processor_perflib.c:465
Inline: False
```
**Symbols:**

```
ffffffff815338b0-ffffffff81533918: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81594fb0)
Location: drivers/acpi/processor_perflib.c:465
Inline: True
```
**Symbols:**

```
ffffffff81594fb0-ffffffff81595067: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815cc340)
Location: drivers/acpi/processor_perflib.c:466
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815cc340-ffffffff815cc3f6: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815e5920)
Location: drivers/acpi/processor_perflib.c:466
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815e5920-ffffffff815e59d6: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81617510)
Location: drivers/acpi/processor_perflib.c:453
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81617510-ffffffff816175c6: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81638b10)
Location: drivers/acpi/processor_perflib.c:439
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81638b10-ffffffff81638bc6: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff816e58a0)
Location: drivers/acpi/processor_perflib.c:439
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff816e58a0-ffffffff816e5956: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81703300)
Location: drivers/acpi/processor_perflib.c:438
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81703300-ffffffff817033b6: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff816e4b90)
Location: drivers/acpi/processor_perflib.c:437
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff816e4b90-ffffffff816e4c1e: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff8175d9d0)
Location: drivers/acpi/processor_perflib.c:435
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8175d9d0-ffffffff8175da5b: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff818910c0)
Location: drivers/acpi/processor_perflib.c:435
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff818910c0-ffffffff8189116f: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff819d8820)
Location: drivers/acpi/processor_perflib.c:432
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff819d8820-ffffffff819d88cf: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a202f0)
Location: drivers/acpi/processor_perflib.c:454
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81a202f0-ffffffff81a2039f: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a6b610)
Location: drivers/acpi/processor_perflib.c:454
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81a6b610-ffffffff81a6b6bf: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffff8000107a40b8)
Location: drivers/acpi/processor_perflib.c:439
Inline: False
```
**Symbols:**

```
ffff8000107a40b8-ffff8000107a4134: acpi_processor_pstate_control (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81607bc0)
Location: drivers/acpi/processor_perflib.c:439
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81607bc0-ffffffff81607c27: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815f2cc0)
Location: drivers/acpi/processor_perflib.c:439
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815f2cc0-ffffffff815f2d27: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff8162cdf0)
Location: drivers/acpi/processor_perflib.c:439
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8162cdf0-ffffffff8162cea6: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_pstate_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81646c90)
Location: drivers/acpi/processor_perflib.c:439
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81646c90-ffffffff81646d46: acpi_processor_pstate_control (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
