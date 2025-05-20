# Function: <code>wrmsrl_safe_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b6e0)
Location: arch/x86/lib/msr-smp.c:193
Inline: False
```
**Symbols:**

```
ffffffff8141b6e0-ffffffff8141b74c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814638a0)
Location: arch/x86/lib/msr-smp.c:193
Inline: False
```
**Symbols:**

```
ffffffff814638a0-ffffffff8146390c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482b40)
Location: arch/x86/lib/msr-smp.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff81482b40-ffffffff81482bac: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c340)
Location: arch/x86/lib/msr-smp.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8148c340-ffffffff8148c3b4: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c8430)
Location: arch/x86/lib/msr-smp.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff814c8430-ffffffff814c84a4: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f92b0)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff814f92b0-ffffffff814f9324: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150db50)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8150db50-ffffffff8150dbc4: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c1f0)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8153c1f0-ffffffff8153c25c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155d000)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8155d000-ffffffff8155d06c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6a20)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff815e6a20-ffffffff815e6a8c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160bb70)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8160bb70-ffffffff8160bbdc: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eee50)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff815eee50-ffffffff815eeebc: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165bf60)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8165bf60-ffffffff8165bfcc: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774dd0)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff81774dd0-ffffffff81774e50: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a58f0)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff818a58f0-ffffffff818a5970: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e8710)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
**Symbols:**

```
ffffffff818e8710-ffffffff818e8790: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192fbb0)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
**Symbols:**

```
ffffffff8192fbb0-ffffffff8192fc30: wrmsrl_safe_on_cpu (STB_GLOBAL)
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
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815555f0)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff815555f0-ffffffff8155565c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81545820)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff81545820-ffffffff8154588c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81551330)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff81551330-ffffffff8155139c: wrmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wrmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b170)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
```
**Symbols:**

```
ffffffff8156b170-ffffffff8156b1dc: wrmsrl_safe_on_cpu (STB_GLOBAL)
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
