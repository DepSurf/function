# Function: <code>wrmsr_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b500)
Location: arch/x86/lib/msr-smp.c:65
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - arch/x86/events/intel/ds.c:fini_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8141b500-ffffffff8141b568: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814636c0)
Location: arch/x86/lib/msr-smp.c:65
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:fini_debug_store_on_cpu
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff814636c0-ffffffff81463728: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482960)
Location: arch/x86/lib/msr-smp.c:65
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:fini_debug_store_on_cpu
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff81482960-ffffffff814829c8: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c150)
Location: arch/x86/lib/msr-smp.c:65
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8148c150-ffffffff8148c1bf: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c8240)
Location: arch/x86/lib/msr-smp.c:66
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff814c8240-ffffffff814c82af: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f9150)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff814f9150-ffffffff814f91bf: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150d9f0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8150d9f0-ffffffff8150da5f: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c0a0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8153c0a0-ffffffff8153c108: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155ceb0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8155ceb0-ffffffff8155cf18: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e68d0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff815e68d0-ffffffff815e6938: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160ba20)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8160ba20-ffffffff8160ba88: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eed00)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff815eed00-ffffffff815eed68: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165be10)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8165be10-ffffffff8165be78: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774c40)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff81774c40-ffffffff81774cbb: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5730)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff818a5730-ffffffff818a57ab: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e8550)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff818e8550-ffffffff818e85cb: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192f9f0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8192f9f0-ffffffff8192fa6b: wrmsr_on_cpu (STB_GLOBAL)
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815554a0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
```
**Symbols:**

```
ffffffff815554a0-ffffffff81555508: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815456d0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff815456d0-ffffffff81545738: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815511e0)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff815511e0-ffffffff81551248: wrmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b020)
Location: arch/x86/lib/msr-smp.c:67
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:init_debug_store_on_cpu
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8156b020-ffffffff8156b088: wrmsr_on_cpu (STB_GLOBAL)
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
