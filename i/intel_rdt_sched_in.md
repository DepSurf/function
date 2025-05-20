# Function: <code>intel_rdt_sched_in</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c728)
Location: arch/x86/include/asm/intel_rdt.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043f23)
Location: arch/x86/include/asm/intel_rdt.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_update_closid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a8ed)
Location: arch/x86/include/asm/intel_rdt_sched.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042693)
Location: arch/x86/include/asm/intel_rdt_sched.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b642)
Location: arch/x86/include/asm/intel_rdt_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046383)
Location: arch/x86/include/asm/intel_rdt_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c662)
Location: arch/x86/include/asm/intel_rdt_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047eb3)
Location: arch/x86/include/asm/intel_rdt_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
```
</details>
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
