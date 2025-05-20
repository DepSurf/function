# Function: <code>local_daif_mask</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void local_daif_mask();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff8000100860b0)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
```
```
In arch/arm64/kernel/signal.c (ffff8000100932c0)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/kernel/traps.c (ffff80001009598c)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:bad_mode
```
```
In arch/arm64/kernel/smp.c (ffff80001009bcf8)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Direct callers:
  - arch/arm64/kernel/smp.c:local_cpu_stop
  - arch/arm64/kernel/smp.c:cpu_die
```
```
In arch/arm64/kernel/syscall.c (ffff80001009d9e4)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6da8)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9cf8)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In virt/kvm/arm/arm.c (ffff8000100c6e08)
Location: arch/arm64/include/asm/daifflags.h:20
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
**Symbols:**

```
ffff80001009bcf8-ffff80001009bd20: local_daif_mask (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
