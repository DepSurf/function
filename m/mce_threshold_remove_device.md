# Function: <code>mce_threshold_remove_device</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a8f0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1310
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8104a8f0-ffffffff8104abce: mce_threshold_remove_device.part.9 (STB_LOCAL)
ffffffff8104b280-ffffffff8104b29e: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a150)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1320
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8104a150-ffffffff8104a403: mce_threshold_remove_device.part.9 (STB_LOCAL)
ffffffff8104ab80-ffffffff8104ab9e: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104dba0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1305
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8104dba0-ffffffff8104de47: mce_threshold_remove_device.part.9 (STB_LOCAL)
ffffffff8104e570-ffffffff8104e58e: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810505e0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1356
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff810505e0-ffffffff8105084a: mce_threshold_remove_device.part.12 (STB_LOCAL)
ffffffff81051190-ffffffff810511ae: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e600)
Location: arch/x86/kernel/cpu/mce/amd.c:1356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8104e600-ffffffff8104e86c: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051690)
Location: arch/x86/kernel/cpu/mce/amd.c:1436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff81051690-ffffffff81051923: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051ff0)
Location: arch/x86/kernel/cpu/mce/amd.c:1442
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff81051ff0-ffffffff81052230: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056b90)
Location: arch/x86/kernel/cpu/mce/amd.c:1460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff81056b90-ffffffff81056d3e: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055aa0)
Location: arch/x86/kernel/cpu/mce/amd.c:1460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff81055aa0-ffffffff81055c67: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81057320)
Location: arch/x86/kernel/cpu/mce/amd.c:1460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff81057320-ffffffff810574e7: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81060130)
Location: arch/x86/kernel/cpu/mce/amd.c:1473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff81060130-ffffffff8106031a: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106ca60)
Location: arch/x86/kernel/cpu/mce/amd.c:1311
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8106ca60-ffffffff8106ca9a: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107cb00)
Location: arch/x86/kernel/cpu/mce/amd.c:1318
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8107cb00-ffffffff8107cb3a: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107eeb0)
Location: arch/x86/kernel/cpu/mce/amd.c:1314
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff8107eeb0-ffffffff8107eeea: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810863a0)
Location: arch/x86/kernel/cpu/mce/amd.c:1364
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff810863a0-ffffffff810863da: mce_threshold_remove_device (STB_GLOBAL)
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
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810520f0)
Location: arch/x86/kernel/cpu/mce/amd.c:1442
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff810520f0-ffffffff81052330: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041ae0)
Location: arch/x86/kernel/cpu/mce/amd.c:1442
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff81041ae0-ffffffff81041d20: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051fa0)
Location: arch/x86/kernel/cpu/mce/amd.c:1442
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff81051fa0-ffffffff810521e0: mce_threshold_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mce_threshold_remove_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810533e0)
Location: arch/x86/kernel/cpu/mce/amd.c:1442
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
**Symbols:**

```
ffffffff810533e0-ffffffff81053620: mce_threshold_remove_device (STB_GLOBAL)
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
