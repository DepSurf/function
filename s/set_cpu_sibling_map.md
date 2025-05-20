# Function: <code>set_cpu_sibling_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810510c0)
Location: arch/x86/kernel/smpboot.c:485
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810510c0-ffffffff8105159e: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051240)
Location: arch/x86/kernel/smpboot.c:500
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81051240-ffffffff8105174d: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053b70)
Location: arch/x86/kernel/smpboot.c:524
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81053b70-ffffffff81054099: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810534d0)
Location: arch/x86/kernel/smpboot.c:527
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810534d0-ffffffff810539e1: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057240)
Location: arch/x86/kernel/smpboot.c:464
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81057240-ffffffff8105770c: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105a0f0)
Location: arch/x86/kernel/smpboot.c:517
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8105a0f0-ffffffff8105a5e6: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fd70)
Location: arch/x86/kernel/smpboot.c:517
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8105fd70-ffffffff81060266: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063600)
Location: arch/x86/kernel/smpboot.c:565
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81063600-ffffffff81063b8f: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063cb0)
Location: arch/x86/kernel/smpboot.c:565
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81063cb0-ffffffff8106423f: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a6c0)
Location: arch/x86/kernel/smpboot.c:578
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:smp_callin
```
**Symbols:**

```
ffffffff8106a6c0-ffffffff8106ac9f: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c390)
Location: arch/x86/kernel/smpboot.c:573
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:smp_callin
```
**Symbols:**

```
ffffffff8106c390-ffffffff8106c96f: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106ce60)
Location: arch/x86/kernel/smpboot.c:575
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8106ce60-ffffffff8106d407: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077ed0)
Location: arch/x86/kernel/smpboot.c:574
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81077ed0-ffffffff81078b26: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81086b50)
Location: arch/x86/kernel/smpboot.c:608
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81086b50-ffffffff8108792b: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109a190)
Location: arch/x86/kernel/smpboot.c:606
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8109a190-ffffffff8109b091: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109d680)
Location: arch/x86/kernel/smpboot.c:668
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8109d680-ffffffff8109e581: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a4cd0)
Location: arch/x86/kernel/smpboot.c:671
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810a4cd0-ffffffff810a5c41: set_cpu_sibling_map (STB_GLOBAL)
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
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810637a0)
Location: arch/x86/kernel/smpboot.c:565
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810637a0-ffffffff81063d2f: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053ab0)
Location: arch/x86/kernel/smpboot.c:565
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81053ab0-ffffffff8105403f: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063c50)
Location: arch/x86/kernel/smpboot.c:565
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81063c50-ffffffff810641df: set_cpu_sibling_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81065210)
Location: arch/x86/kernel/smpboot.c:565
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81065210-ffffffff8106579f: set_cpu_sibling_map (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
