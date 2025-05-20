# Function: <code>x86_gsbase_read_cpu_inactive</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d5d3)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81143710)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f3b3)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8114ea56)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fd13)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8115a766)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032ccd)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In kernel/kexec_core.c (ffffffff8116b536)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033100)
Location: arch/x86/kernel/process_64.c:406
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81033100-ffffffff8103315c: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034d23)
Location: arch/x86/kernel/process_64.c:406
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
Direct callers:
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81034b90-ffffffff81034bf7: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a043)
Location: arch/x86/kernel/process_64.c:430
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
Direct callers:
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81039eb0-ffffffff81039f17: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041081)
Location: arch/x86/kernel/process_64.c:430
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81040bd0-ffffffff81040c0b: x86_gsbase_read_cpu_inactive.part.0 (STB_LOCAL)
ffffffff81040e80-ffffffff81040edb: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a791)
Location: arch/x86/kernel/process_64.c:430
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81049f40-ffffffff81049f84: x86_gsbase_read_cpu_inactive.part.0 (STB_LOCAL)
ffffffff8104a560-ffffffff8104a5bb: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104afd1)
Location: arch/x86/kernel/process_64.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8104a560-ffffffff8104a5a4: x86_gsbase_read_cpu_inactive.part.0 (STB_LOCAL)
ffffffff8104ada0-ffffffff8104adfb: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052241)
Location: arch/x86/kernel/process_64.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff810517c0-ffffffff81051804: x86_gsbase_read_cpu_inactive.part.0 (STB_LOCAL)
ffffffff81052010-ffffffff8105206b: x86_gsbase_read_cpu_inactive (STB_GLOBAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fe73)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81152d86)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101f8b7)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8114606f)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fcd3)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81150c36)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030b23)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8115da56)
Location: arch/x86/include/asm/fsgsbase.h:33
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
