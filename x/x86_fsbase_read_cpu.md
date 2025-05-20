# Function: <code>x86_fsbase_read_cpu</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d583)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81143700)
Location: arch/x86/include/asm/fsgsbase.h:24
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
In arch/x86/kernel/process_64.c (ffffffff8102f363)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8114ea46)
Location: arch/x86/include/asm/fsgsbase.h:24
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
In arch/x86/kernel/process_64.c (ffffffff8102fcc3)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8115a756)
Location: arch/x86/include/asm/fsgsbase.h:24
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
In arch/x86/kernel/process_64.c (ffffffff81032c59)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In kernel/kexec_core.c (ffffffff8116b526)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033201)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff81167c61)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034cb1)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff811689f1)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81039fd1)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff8118e72f)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81040fc1)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff811bdcf6)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a6c1)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff811ffd56)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104af01)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff812151b6)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052171)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
```
```
In kernel/kexec_core.c (ffffffff8122d156)
Location: arch/x86/include/asm/fsgsbase.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
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
In arch/x86/kernel/process_64.c (ffffffff8102fe23)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81152d76)
Location: arch/x86/include/asm/fsgsbase.h:24
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
In arch/x86/kernel/process_64.c (ffffffff8101f847)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8114605a)
Location: arch/x86/include/asm/fsgsbase.h:24
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
In arch/x86/kernel/process_64.c (ffffffff8102fc83)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81150c26)
Location: arch/x86/include/asm/fsgsbase.h:24
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
In arch/x86/kernel/process_64.c (ffffffff81030ad3)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8115da46)
Location: arch/x86/include/asm/fsgsbase.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
</ul>

## Differences
