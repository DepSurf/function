# Function: <code>xen_smp_intr_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b070)
Location: arch/x86/xen/smp.c:162
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff8102b070-ffffffff8102b2d6: xen_smp_intr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a390)
Location: arch/x86/xen/smp.c:162
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff8102a390-ffffffff8102a5f6: xen_smp_intr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b370)
Location: arch/x86/xen/smp.c:162
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_prepare
  - arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102b370-ffffffff8102b5d6: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028c90)
Location: arch/x86/xen/smp.c:61
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81028c90-ffffffff81028e23: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028ea0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81028ea0-ffffffff81029033: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810298f0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810298f0-ffffffff81029a9c: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029ed0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81029ed0-ffffffff8102a07c: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102bc80)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102bc80-ffffffff8102be35: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c560)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102c560-ffffffff8102c715: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102e520)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102e520-ffffffff8102e6d5: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102f380)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102f380-ffffffff8102f53e: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102fe90)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102fe90-ffffffff8103004e: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81c97b58-ffffffff81c97b6d: xen_smp_intr_init.cold (STB_LOCAL)
ffffffff81034b70-ffffffff81034e74: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81e46f1f-ffffffff81e46f33: xen_smp_intr_init.cold (STB_LOCAL)
ffffffff8103a8a0-ffffffff8103abab: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff82051e43-ffffffff82051e57: xen_smp_intr_init.cold (STB_LOCAL)
ffffffff81042f70-ffffffff8104328c: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff820d02b8-ffffffff820d02cc: xen_smp_intr_init.cold (STB_LOCAL)
ffffffff81043170-ffffffff8104348c: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff821aac25-ffffffff821aac39: xen_smp_intr_init.cold (STB_LOCAL)
ffffffff81049640-ffffffff81049988: xen_smp_intr_init (STB_GLOBAL)
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
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c6c0)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102c6c0-ffffffff8102c875: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c520)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102c520-ffffffff8102c6d5: xen_smp_intr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102d310)
Location: arch/x86/xen/smp.c:62
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d310-ffffffff8102d4c5: xen_smp_intr_init (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
