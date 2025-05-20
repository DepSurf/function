# Function: <code>__sev_cpuid_hv</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sev_cpuid_hv(u32 fn, int reg_idx, u32 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a4850)
Location: arch/x86/kernel/sev-shared.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
```
**Symbols:**

```
ffffffff810a4850-ffffffff810a48b9: __sev_cpuid_hv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sev_cpuid_hv(u32 fn, int reg_idx, u32 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bcd70)
Location: arch/x86/kernel/sev-shared.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
```
**Symbols:**

```
ffffffff810bcd70-ffffffff810bcdd9: __sev_cpuid_hv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sev_cpuid_hv(u32 fn, int reg_idx, u32 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c0390)
Location: arch/x86/kernel/sev-shared.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_cpuid_hv
```
**Symbols:**

```
ffffffff810c0390-ffffffff810c03f9: __sev_cpuid_hv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sev_cpuid_hv(u32 fn, int reg_idx, u32 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c7780)
Location: arch/x86/kernel/sev-shared.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_msr
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_msr
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_msr
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_msr
```
**Symbols:**

```
ffffffff810c7780-ffffffff810c77e9: __sev_cpuid_hv (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
