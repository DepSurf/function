# Function: <code>perf_trace_hyperv_mmu_flush_tlb_multi</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81031d50)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81031d50-ffffffff81031e55: perf_trace_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81036ed0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81036ed0-ffffffff81036fd5: perf_trace_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8103cfb0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8103cfb0-ffffffff8103d0d5: perf_trace_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81045cb0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81045cb0-ffffffff81045dd2: perf_trace_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81045e60)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81045e60-ffffffff81045f82: perf_trace_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8104c530)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8104c530-ffffffff8104c652: perf_trace_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
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
