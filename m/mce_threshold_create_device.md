# Function: <code>mce_threshold_create_device</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b2a0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1328
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff8104b2a0-ffffffff8104b606: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104aba0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1338
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff8104aba0-ffffffff8104af03: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104e590)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1323
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff8104e590-ffffffff8104e8f5: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810511b0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1374
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff810511b0-ffffffff81051507: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e870)
Location: arch/x86/kernel/cpu/mce/amd.c:1371
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff8104e870-ffffffff8104ebae: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810519a4)
Location: arch/x86/kernel/cpu/mce/amd.c:1451
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff81051dbc-ffffffff81051dcf: mce_threshold_create_device.cold (STB_LOCAL)
ffffffff81051930-ffffffff81051c6b: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052230)
Location: arch/x86/kernel/cpu/mce/amd.c:1457
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff81052230-ffffffff81052572: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056d40)
Location: arch/x86/kernel/cpu/mce/amd.c:1495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81056d40-ffffffff81056e0e: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055c70)
Location: arch/x86/kernel/cpu/mce/amd.c:1495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81055c70-ffffffff81055d47: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810574f0)
Location: arch/x86/kernel/cpu/mce/amd.c:1495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff810574f0-ffffffff810575c7: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:1508
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81c9bb77-ffffffff81c9bba4: mce_threshold_create_device.cold (STB_LOCAL)
ffffffff81060320-ffffffff8106041e: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:1339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81e4af93-ffffffff81e4afc6: mce_threshold_create_device.cold (STB_LOCAL)
ffffffff8106caa0-ffffffff8106cbcd: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:1346
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff82052ef4-ffffffff82052f27: mce_threshold_create_device.cold (STB_LOCAL)
ffffffff8107cb50-ffffffff8107cc7d: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff820d1455-ffffffff820d1482: mce_threshold_create_device.cold (STB_LOCAL)
ffffffff8107ef00-ffffffff8107f021: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:1392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff821abfc9-ffffffff821abff6: mce_threshold_create_device.cold (STB_LOCAL)
ffffffff810863f0-ffffffff81086511: mce_threshold_create_device (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052330)
Location: arch/x86/kernel/cpu/mce/amd.c:1457
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff81052330-ffffffff81052672: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041d20)
Location: arch/x86/kernel/cpu/mce/amd.c:1457
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff81041d20-ffffffff81042062: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810521e0)
Location: arch/x86/kernel/cpu/mce/amd.c:1457
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff810521e0-ffffffff81052522: mce_threshold_create_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mce_threshold_create_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81053620)
Location: arch/x86/kernel/cpu/mce/amd.c:1457
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
```
**Symbols:**

```
ffffffff81053620-ffffffff81053962: mce_threshold_create_device (STB_GLOBAL)
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
