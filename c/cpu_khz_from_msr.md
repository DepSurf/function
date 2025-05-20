# Function: <code>cpu_khz_from_msr</code>

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
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff81037910)
Location: arch/x86/kernel/tsc_msr.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff81037910-ffffffff810379e9: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff810376b0)
Location: arch/x86/kernel/tsc_msr.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff810376b0-ffffffff810377b0: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff81035750)
Location: arch/x86/kernel/tsc_msr.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff81035750-ffffffff81035851: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff81037a70)
Location: arch/x86/kernel/tsc_msr.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff81037a70-ffffffff81037b71: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff81038bb0)
Location: arch/x86/kernel/tsc_msr.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff81038bb0-ffffffff81038cb0: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff81039e00)
Location: arch/x86/kernel/tsc_msr.c:77
Inline: False
```
**Symbols:**

```
ffffffff81039e00-ffffffff81039eb7: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff8103c3c0)
Location: arch/x86/kernel/tsc_msr.c:77
Inline: False
```
**Symbols:**

```
ffffffff8103c3c0-ffffffff8103c474: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff8103cb80)
Location: arch/x86/kernel/tsc_msr.c:82
Inline: False
```
**Symbols:**

```
ffffffff8103cb80-ffffffff8103cc34: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:165
Inline: False
```
**Symbols:**

```
ffffffff8103fab8-ffffffff8103fac9: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff8103f9b0-ffffffff8103fab8: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
```
**Symbols:**

```
ffffffff81bd4438-ffffffff81bd4449: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff8103f840-ffffffff8103f948: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
```
**Symbols:**

```
ffffffff81bc6954-ffffffff81bc6968: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff810411e0-ffffffff810412e6: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
```
**Symbols:**

```
ffffffff81c99c42-ffffffff81c99c6b: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff81047410-ffffffff81047569: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff81e49729-ffffffff81e49752: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff81050260-ffffffff810503e9: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff820525b3-ffffffff820525c8: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff8105d690-ffffffff8105d830: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff820d0a82-ffffffff820d0a97: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff8105ece0-ffffffff8105ee80: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (0)
Location: arch/x86/kernel/tsc_msr.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
**Symbols:**

```
ffffffff821ab5ab-ffffffff821ab5c0: cpu_khz_from_msr.cold (STB_LOCAL)
ffffffff81065d90-ffffffff81065f30: cpu_khz_from_msr (STB_GLOBAL)
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
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff8103cd00)
Location: arch/x86/kernel/tsc_msr.c:82
Inline: False
```
**Symbols:**

```
ffffffff8103cd00-ffffffff8103cdb4: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff8102c340)
Location: arch/x86/kernel/tsc_msr.c:82
Inline: False
```
**Symbols:**

```
ffffffff8102c340-ffffffff8102c447: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff8103cb40)
Location: arch/x86/kernel/tsc_msr.c:82
Inline: False
```
**Symbols:**

```
ffffffff8103cb40-ffffffff8103cbf4: cpu_khz_from_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int cpu_khz_from_msr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_msr.c (ffffffff8103dbd0)
Location: arch/x86/kernel/tsc_msr.c:82
Inline: False
```
**Symbols:**

```
ffffffff8103dbd0-ffffffff8103dc84: cpu_khz_from_msr (STB_GLOBAL)
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
