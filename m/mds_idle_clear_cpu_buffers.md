# Function: <code>mds_idle_clear_cpu_buffers</code>

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
In arch/x86/kernel/process.c (ffffffff81a9cb81)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd42)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106492c)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d6a)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a9cda0)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b4d)
Location: arch/x86/include/asm/nospec-branch.h:355
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
In arch/x86/kernel/process.c (ffffffff81ad43d1)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad4592)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064fac)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81077dba)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81ad45f0)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d8d)
Location: arch/x86/include/asm/nospec-branch.h:355
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
In arch/x86/kernel/process.c (ffffffff81bcc4bd)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ab4)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b6d5)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81bcc670)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8d4)
Location: arch/x86/include/asm/nospec-branch.h:297
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
In arch/x86/kernel/process.c (ffffffff81c45196)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a754)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d375)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81c45220)
Location: arch/x86/include/asm/nospec-branch.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5d4)
Location: arch/x86/include/asm/nospec-branch.h:297
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
In arch/x86/kernel/process.c (ffffffff81c38413)
Location: arch/x86/include/asm/nospec-branch.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b21b)
Location: arch/x86/include/asm/nospec-branch.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dde5)
Location: arch/x86/include/asm/nospec-branch.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81c384a0)
Location: arch/x86/include/asm/nospec-branch.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff8168035b)
Location: arch/x86/include/asm/nospec-branch.h:296
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
In arch/x86/kernel/process.c (ffffffff81d56ca3)
Location: arch/x86/include/asm/nospec-branch.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d3b)
Location: arch/x86/include/asm/nospec-branch.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff810795f5)
Location: arch/x86/include/asm/nospec-branch.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81d56d50)
Location: arch/x86/include/asm/nospec-branch.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff816f50cb)
Location: arch/x86/include/asm/nospec-branch.h:300
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
In arch/x86/kernel/process.c (ffffffff81f28f13)
Location: arch/x86/include/asm/nospec-branch.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084784)
Location: arch/x86/include/asm/nospec-branch.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088485)
Location: arch/x86/include/asm/nospec-branch.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81f29010)
Location: arch/x86/include/asm/nospec-branch.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff818219f4)
Location: arch/x86/include/asm/nospec-branch.h:391
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
In arch/x86/kernel/process.c (ffffffff820d4c03)
Location: arch/x86/include/asm/nospec-branch.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a14)
Location: arch/x86/include/asm/nospec-branch.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bf45)
Location: arch/x86/include/asm/nospec-branch.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff820d4d00)
Location: arch/x86/include/asm/nospec-branch.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff819526e4)
Location: arch/x86/include/asm/nospec-branch.h:567
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
In arch/x86/kernel/process.c (ffffffff82142ff1)
Location: arch/x86/include/asm/nospec-branch.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff821430f7)
Location: arch/x86/include/asm/nospec-branch.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ee9a)
Location: arch/x86/include/asm/nospec-branch.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff82141030)
Location: arch/x86/include/asm/nospec-branch.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_safe_halt
  - arch/x86/kernel/paravirt.c:native_halt
```
```
In drivers/idle/intel_idle.c (ffffffff8214362c)
Location: arch/x86/include/asm/nospec-branch.h:589
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
In arch/x86/kernel/process.c (ffffffff822256de)
Location: arch/x86/include/asm/nospec-branch.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257e2)
Location: arch/x86/include/asm/nospec-branch.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a62ca)
Location: arch/x86/include/asm/nospec-branch.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff82222e50)
Location: arch/x86/include/asm/nospec-branch.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_safe_halt
  - arch/x86/kernel/paravirt.c:native_halt
```
```
In drivers/idle/intel_idle.c (ffffffff82225d3c)
Location: arch/x86/include/asm/nospec-branch.h:598
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
In arch/x86/kernel/process.c (ffffffff81a73241)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73402)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a9c)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81076dba)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a73460)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815c8add)
Location: arch/x86/include/asm/nospec-branch.h:355
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
In arch/x86/kernel/process.c (ffffffff81a2f601)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/tboot.c (ffffffff81033448)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7b2)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/reboot.c (ffffffff81052aec)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d71)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81066e0e)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/mm/extable.c (ffffffff828a626f)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b4d)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815efa6d)
Location: arch/x86/include/asm/nospec-branch.h:355
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
In arch/x86/kernel/process.c (ffffffff81adf651)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf812)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f4c)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d6a)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81adf870)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815c906d)
Location: arch/x86/include/asm/nospec-branch.h:355
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
In arch/x86/kernel/process.c (ffffffff81aebde1)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfe2)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106652c)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81078dc7)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81aec040)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_halt
  - arch/x86/kernel/paravirt.c:native_safe_halt
```
```
In drivers/idle/intel_idle.c (ffffffff815e2ecd)
Location: arch/x86/include/asm/nospec-branch.h:355
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
</details>
</li>
</ul>

## Differences
