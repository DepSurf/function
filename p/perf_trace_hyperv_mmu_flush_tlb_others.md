# Function: <code>perf_trace_hyperv_mmu_flush_tlb_others</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102adb0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102adb0-ffffffff8102aebe: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102b990)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102b990-ffffffff8102baa1: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102c4e0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102c4e0-ffffffff8102c5f1: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102d6c0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102d6c0-ffffffff8102d7bf: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102dfd0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102dfd0-ffffffff8102e0cf: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81030480)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81030480-ffffffff81030585: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810311f0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff810311f0-ffffffff810312f5: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102e130)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102e130-ffffffff8102e22f: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8101daf0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8101daf0-ffffffff8101dbef: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102df90)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102df90-ffffffff8102e08f: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_others(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102ed80)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8102ed80-ffffffff8102ee7f: perf_trace_hyperv_mmu_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
