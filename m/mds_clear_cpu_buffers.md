# Function: <code>mds_clear_cpu_buffers</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810047fa)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff81035d60)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81a9cb86)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd47)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064931)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d6f)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a9cda5)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b52)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/entry/common.c (ffffffff8100485a)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff8103657b)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81ad43d6)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad4597)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064fb1)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81077dbf)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81ad45f5)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d92)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/entry/common.c (ffffffff81bbc7f1)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:syscall_return_slowpath
  - arch/x86/entry/common.c:prepare_exit_to_usermode
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbdf59)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff81bcc4c2)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ab9)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b6da)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81bcc675)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8d9)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81c367fd)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff81c4519b)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a759)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d37a)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81c45225)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In kernel/entry/common.c (ffffffff81c38a2e)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5d9)
Location: arch/x86/include/asm/nospec-branch.h:265
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81c28c8d)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff81c38418)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b220)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106ddea)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81c384a5)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In kernel/entry/common.c (ffffffff81c2ae2e)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
```
In drivers/idle/intel_idle.c (ffffffff81680360)
Location: arch/x86/include/asm/nospec-branch.h:264
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81d46e27)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff81d56ca5)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d3d)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff810795f7)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81d56d52)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In kernel/entry/common.c (ffffffff81d493bb)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
```
In drivers/idle/intel_idle.c (ffffffff816f50cd)
Location: arch/x86/include/asm/nospec-branch.h:268
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81f1536f)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff81f28f15)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084786)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088487)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81f29012)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In kernel/entry/common.c (ffffffff81f1884b)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
```
In drivers/idle/intel_idle.c (ffffffff818219f6)
Location: arch/x86/include/asm/nospec-branch.h:359
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff820bc801)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff820d4c05)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a16)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bf47)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff820d4d02)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In kernel/entry/common.c (ffffffff820bfe8b)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
```
In drivers/idle/intel_idle.c (ffffffff819526e6)
Location: arch/x86/include/asm/nospec-branch.h:535
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff8213e088)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/process.c (ffffffff82142ff3)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff821430f9)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ee9c)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff82141032)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_safe_halt
  - arch/x86/kernel/paravirt.c:native_halt
```
```
In kernel/entry/common.c (ffffffff82141ccb)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
```
In drivers/idle/intel_idle.c (ffffffff8214362e)
Location: arch/x86/include/asm/nospec-branch.h:557
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff822256e0)
Location: arch/x86/include/asm/nospec-branch.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257e4)
Location: arch/x86/include/asm/nospec-branch.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a62cc)
Location: arch/x86/include/asm/nospec-branch.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff82222e52)
Location: arch/x86/include/asm/nospec-branch.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_safe_halt
  - arch/x86/kernel/paravirt.c:native_halt
```
```
In drivers/idle/intel_idle.c (ffffffff82225d3e)
Location: arch/x86/include/asm/nospec-branch.h:577
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/entry/common.c (ffffffff8100485a)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff810366db)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81a73246)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73407)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064aa1)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81076dbf)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a73465)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815c8ae2)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/entry/common.c (ffffffff81002ead)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff81026023)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81a2f606)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/tboot.c (ffffffff8103344d)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7b7)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/reboot.c (ffffffff81052af1)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d76)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81066e13)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/mm/extable.c (ffffffff828a6274)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b52)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815efa72)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In arch/x86/entry/common.c (ffffffff8100481a)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff8103653b)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81adf656)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf817)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f51)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d6f)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81adf875)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815c9072)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/entry/common.c (ffffffff8100495a)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff8103753b)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81aebde6)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfe7)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81066531)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81078dcc)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81aec045)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815e2ed2)
Location: arch/x86/include/asm/nospec-branch.h:323
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
</details>
</li>
</ul>

## Differences
