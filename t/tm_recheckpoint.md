# Function: <code>tm_recheckpoint</code>

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
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tm_recheckpoint(struct thread_struct *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000022000)
Location: arch/powerpc/kernel/process.c:923
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:arch_dup_task_struct
  - arch/powerpc/kernel/process.c:__switch_to
Direct callers:
  - arch/powerpc/kernel/process.c:arch_dup_task_struct
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/traps.c:vsx_unavailable_tm
  - arch/powerpc/kernel/traps.c:altivec_unavailable_tm
  - arch/powerpc/kernel/traps.c:fp_unavailable_tm
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
```
**Symbols:**

```
c000000000020650-c0000000000206e4: tm_recheckpoint.part.0 (STB_LOCAL)
c000000000021660-c000000000021684: tm_recheckpoint (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
