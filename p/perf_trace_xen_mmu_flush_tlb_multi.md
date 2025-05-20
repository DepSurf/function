# Function: <code>perf_trace_xen_mmu_flush_tlb_multi</code>

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
void perf_trace_xen_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102e830)
Location: include/trace/events/xen.h:349
Inline: False
```
**Symbols:**

```
ffffffff8102e830-ffffffff8102e93a: perf_trace_xen_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_xen_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff810330a0)
Location: include/trace/events/xen.h:349
Inline: False
```
**Symbols:**

```
ffffffff810330a0-ffffffff810331aa: perf_trace_xen_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_xen_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff81039bc0)
Location: include/trace/events/xen.h:349
Inline: False
```
**Symbols:**

```
ffffffff81039bc0-ffffffff81039ce7: perf_trace_xen_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_xen_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff81041cd0)
Location: include/trace/events/xen.h:349
Inline: False
```
**Symbols:**

```
ffffffff81041cd0-ffffffff81041df4: perf_trace_xen_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_xen_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff81041e10)
Location: include/trace/events/xen.h:349
Inline: False
```
**Symbols:**

```
ffffffff81041e10-ffffffff81041f34: perf_trace_xen_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_xen_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff810482e0)
Location: include/trace/events/xen.h:349
Inline: False
```
**Symbols:**

```
ffffffff810482e0-ffffffff81048404: perf_trace_xen_mmu_flush_tlb_multi (STB_LOCAL)
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
