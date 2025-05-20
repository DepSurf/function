# Function: <code>switch_gdt_and_percpu_base</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void switch_gdt_and_percpu_base(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff83e7c100)
Location: arch/x86/kernel/cpu/common.c:742
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff83e7c100-ffffffff83e7c175: switch_gdt_and_percpu_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void switch_gdt_and_percpu_base(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8369e810)
Location: arch/x86/kernel/cpu/common.c:731
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff8369e810-ffffffff8369e885: switch_gdt_and_percpu_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void switch_gdt_and_percpu_base(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff838ce4a0)
Location: arch/x86/kernel/cpu/common.c:728
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff838ce4a0-ffffffff838ce591: switch_gdt_and_percpu_base (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
