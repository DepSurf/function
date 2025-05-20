# Function: <code>intel_thermal_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049800)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:452
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
**Symbols:**

```
ffffffff81049800-ffffffff81049830: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810499c0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:451
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
**Symbols:**

```
ffffffff810499c0-ffffffff810499f0: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bdc0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:424
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
**Symbols:**

```
ffffffff8104bdc0-ffffffff8104bdf0: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b530)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:418
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
**Symbols:**

```
ffffffff8104b530-ffffffff8104b560: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ef40)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:404
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
**Symbols:**

```
ffffffff8104ef40-ffffffff8104ef70: intel_thermal_supported (STB_LOCAL)
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051c8f)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f308)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8105242f)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052d1f)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057d2f)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
**Symbols:**

```
ffffffff81057310-ffffffff81057340: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056aaf)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
**Symbols:**

```
ffffffff810560c0-ffffffff810560f0: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff8194746f)
Location: drivers/thermal/intel/therm_throt.c:610
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
Direct callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
```
**Symbols:**

```
ffffffff81946b10-ffffffff81946b40: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff819ec2d3)
Location: drivers/thermal/intel/therm_throt.c:615
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
Direct callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
```
**Symbols:**

```
ffffffff819eb5d0-ffffffff819eb600: intel_thermal_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int intel_thermal_supported(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81b522c3)
Location: drivers/thermal/intel/therm_throt.c:631
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
Direct callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
```
**Symbols:**

```
ffffffff81b51580-ffffffff81b515b8: intel_thermal_supported (STB_LOCAL)
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
In drivers/thermal/intel/therm_throt.c (ffffffff81cea483)
Location: drivers/thermal/intel/therm_throt.c:635
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
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
In drivers/thermal/intel/therm_throt.c (ffffffff81d52fc3)
Location: drivers/thermal/intel/therm_throt.c:691
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
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
In drivers/thermal/intel/therm_throt.c (ffffffff81e09d23)
Location: drivers/thermal/intel/therm_throt.c:691
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e1f)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104286e)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052ccf)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8105414f)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
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
</ul>
