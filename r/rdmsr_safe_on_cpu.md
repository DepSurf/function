# Function: <code>rdmsr_safe_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b5e0)
Location: arch/x86/lib/msr-smp.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
```
**Symbols:**

```
ffffffff8141b5e0-ffffffff8141b66c: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814637a0)
Location: arch/x86/lib/msr-smp.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
```
**Symbols:**

```
ffffffff814637a0-ffffffff8146382c: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482a40)
Location: arch/x86/lib/msr-smp.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81482a40-ffffffff81482acc: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c230)
Location: arch/x86/lib/msr-smp.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8148c230-ffffffff8148c2bc: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c8320)
Location: arch/x86/lib/msr-smp.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff814c8320-ffffffff814c83ac: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f9470)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff814f9470-ffffffff814f9544: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150dd10)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff8150dd10-ffffffff8150dde4: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c390)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff8153c390-ffffffff8153c45f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155d1a0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff8155d1a0-ffffffff8155d26f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6b80)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff815e6b80-ffffffff815e6c4f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160bcd0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff8160bcd0-ffffffff8160bd9f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eefb0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff815eefb0-ffffffff815ef07f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165c0c0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff8165c0c0-ffffffff8165c18f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81775070)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff81775070-ffffffff8177514b: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5be0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff818a5be0-ffffffff818a5cbb: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e8a00)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_temp
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_tjmax
```
**Symbols:**

```
ffffffff818e8a00-ffffffff818e8adb: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192fea0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_temp
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_tjmax
```
**Symbols:**

```
ffffffff8192fea0-ffffffff8192ff7b: rdmsr_safe_on_cpu (STB_GLOBAL)
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
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555790)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff81555790-ffffffff8155585f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81545a60)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff81545a60-ffffffff81545b2f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815514d0)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff815514d0-ffffffff8155159f: rdmsr_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdmsr_safe_on_cpu(unsigned int cpu, u32 msr_no, u32 *l, u32 *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b330)
Location: arch/x86/lib/msr-smp.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
```
**Symbols:**

```
ffffffff8156b330-ffffffff8156b3ff: rdmsr_safe_on_cpu (STB_GLOBAL)
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
