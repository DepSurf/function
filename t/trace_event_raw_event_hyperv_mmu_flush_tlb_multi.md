# Function: <code>trace_event_raw_event_hyperv_mmu_flush_tlb_multi</code>

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
void trace_event_raw_event_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81031f50)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81031f50-ffffffff81032027: trace_event_raw_event_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810370d0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff810370d0-ffffffff810371a7: trace_event_raw_event_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8103d200)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8103d200-ffffffff8103d2c8: trace_event_raw_event_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81045f10)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff81045f10-ffffffff81045fd8: trace_event_raw_event_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810460c0)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff810460c0-ffffffff81046188: trace_event_raw_event_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_hyperv_mmu_flush_tlb_multi(void *__data, const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8104c790)
Location: arch/x86/include/asm/trace/hyperv.h:11
Inline: False
```
**Symbols:**

```
ffffffff8104c790-ffffffff8104c858: trace_event_raw_event_hyperv_mmu_flush_tlb_multi (STB_LOCAL)
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
