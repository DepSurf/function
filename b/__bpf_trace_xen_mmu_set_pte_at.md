# Function: <code>__bpf_trace_xen_mmu_set_pte_at</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff81028580)
Location: include/trace/events/xen.h:152
Inline: True
```
**Symbols:**

```
ffffffff81028580-ffffffff8102858b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff81028b60)
Location: include/trace/events/xen.h:152
Inline: True
```
**Symbols:**

```
ffffffff81028b60-ffffffff81028b6b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102a960)
Location: include/trace/events/xen.h:152
Inline: False
```
**Symbols:**

```
ffffffff8102a960-ffffffff8102a96b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102b260)
Location: include/trace/events/xen.h:156
Inline: False
```
**Symbols:**

```
ffffffff8102b260-ffffffff8102b26b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102d030)
Location: include/trace/events/xen.h:156
Inline: True
```
**Symbols:**

```
ffffffff8102d030-ffffffff8102d03b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
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
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102b3c0)
Location: include/trace/events/xen.h:156
Inline: False
```
**Symbols:**

```
ffffffff8102b3c0-ffffffff8102b3cb: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102b220)
Location: include/trace/events/xen.h:156
Inline: False
```
**Symbols:**

```
ffffffff8102b220-ffffffff8102b22b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_xen_mmu_set_pte_at(void *__data, struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/trace.c (ffffffff8102c010)
Location: include/trace/events/xen.h:156
Inline: False
```
**Symbols:**

```
ffffffff8102c010-ffffffff8102c01b: __bpf_trace_xen_mmu_set_pte_at (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
