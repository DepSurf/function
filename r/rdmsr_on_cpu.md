# Function: <code>rdmsr_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b3f0)
Location: arch/x86/lib/msr-smp.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff8141b3f0-ffffffff8141b476: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814635b0)
Location: arch/x86/lib/msr-smp.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff814635b0-ffffffff81463636: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482850)
Location: arch/x86/lib/msr-smp.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff81482850-ffffffff814828d6: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c040)
Location: arch/x86/lib/msr-smp.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8148c040-ffffffff8148c0c5: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c8130)
Location: arch/x86/lib/msr-smp.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff814c8130-ffffffff814c81b5: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f9040)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff814f9040-ffffffff814f90c5: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150d8e0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8150d8e0-ffffffff8150d965: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153bf90)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8153bf90-ffffffff8153c016: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155cda0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8155cda0-ffffffff8155ce26: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e67c0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff815e67c0-ffffffff815e6846: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160b910)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8160b910-ffffffff8160b996: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eebf0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff815eebf0-ffffffff815eec76: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165bd00)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8165bd00-ffffffff8165bd86: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774b10)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff81774b10-ffffffff81774ba1: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a55e0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff818a55e0-ffffffff818a5671: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e8400)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff818e8400-ffffffff818e8491: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192f8a0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8192f8a0-ffffffff8192f931: rdmsr_on_cpu (STB_GLOBAL)
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555390)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81555390-ffffffff81555416: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815455c0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff815455c0-ffffffff81545646: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815510d0)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff815510d0-ffffffff81551156: rdmsr_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156af10)
Location: arch/x86/lib/msr-smp.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:show_error_count
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
  - drivers/cpufreq/speedstep-centrino.c:get_cur_freq
```
**Symbols:**

```
ffffffff8156af10-ffffffff8156af96: rdmsr_on_cpu (STB_GLOBAL)
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
