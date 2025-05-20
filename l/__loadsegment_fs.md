# Function: <code>__loadsegment_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81891b61)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/xen/enlighten.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ccc2)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b8ac)
Location: arch/x86/include/asm/segment.h:284
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d640)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041072)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810794d9)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810801d9)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff818c6471)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/xen/enlighten.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cb6e)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b0ec)
Location: arch/x86/include/asm/segment.h:284
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103cf30)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040abf)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d2c9)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81084b39)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
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
In arch/x86/xen/enlighten_pv.c (ffffffff8101f1e2)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ad6e)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103914d)
Location: arch/x86/include/asm/segment.h:284
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103af60)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ea42)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107bac9)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81081a19)
Location: arch/x86/include/asm/segment.h:284
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
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
In arch/x86/xen/enlighten_pv.c (ffffffff8101ff32)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102baae)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bb3e)
Location: arch/x86/include/asm/segment.h:295
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d990)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104172f)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810821cc)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810882e9)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81822b27)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff81020db2)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cae8)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cfcd)
Location: arch/x86/include/asm/segment.h:295
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103eef2)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042fff)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108588c)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8108c039)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8186cd4f)
Location: arch/x86/include/asm/segment.h:295
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810202f2)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102dd84)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e4fd)
Location: arch/x86/include/asm/segment.h:335
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810404e9)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044667)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c5fc)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810938f9)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8188cd5f)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff81021d82)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fb03)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81040c73)
Location: arch/x86/include/asm/segment.h:335
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81042b90)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046c15)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810906c1)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81097ffb)
Location: arch/x86/include/asm/segment.h:335
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff818d7733)
Location: arch/x86/include/asm/segment.h:335
Inline: True
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
In arch/x86/xen/enlighten_pv.c (ffffffff810226c2)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff81030463)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041403)
Location: arch/x86/include/asm/segment.h:347
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043300)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047395)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091221)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8109d882)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff819098a0)
Location: arch/x86/include/asm/segment.h:347
Inline: True
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
In arch/x86/xen/enlighten_pv.c (ffffffff810252e4)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff81032c98)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81046b27)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b16b)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096a10)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a4a42)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81bba345)
Location: arch/x86/include/asm/segment.h:347
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
In arch/x86/xen/enlighten_pv.c (ffffffff81025d95)
Location: arch/x86/include/asm/segment.h:343
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff81033948)
Location: arch/x86/include/asm/segment.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8104623f)
Location: arch/x86/include/asm/segment.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a83c)
Location: arch/x86/include/asm/segment.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095c30)
Location: arch/x86/include/asm/segment.h:343
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a0152)
Location: arch/x86/include/asm/segment.h:343
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81bcebb5)
Location: arch/x86/include/asm/segment.h:343
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
In arch/x86/xen/enlighten_pv.c (ffffffff81027d9a)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8103548c)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81047c5f)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c105)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096590)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a0f12)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81bc2565)
Location: arch/x86/include/asm/segment.h:336
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102c41a)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a76c)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8104e4f7)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105345a)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6530)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810b2202)
Location: arch/x86/include/asm/segment.h:336
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81c92bf3)
Location: arch/x86/include/asm/segment.h:336
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
In arch/x86/xen/enlighten_pv.c (ffffffff81030784)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff81041858)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81059659)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105eede)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb620)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:reload_segments
```
```
In kernel/fork.c (ffffffff810c7faf)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81e4255c)
Location: arch/x86/include/asm/segment.h:330
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
In arch/x86/xen/enlighten_pv.c (ffffffff81037da4)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8104afb8)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal_32.c (ffffffff810556c0)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:reload_segments
```
```
In arch/x86/kernel/tls.c (ffffffff81066f89)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d63e)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In kernel/fork.c (ffffffff810e516f)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8201cf3c)
Location: arch/x86/include/asm/segment.h:330
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
In arch/x86/xen/enlighten_pv.c (ffffffff81037d04)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b867)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal_32.c (ffffffff810566f0)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:reload_segments
```
```
In arch/x86/kernel/tls.c (ffffffff81068a69)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106efa0)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In kernel/fork.c (ffffffff810f080f)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8209d5cc)
Location: arch/x86/include/asm/segment.h:330
Inline: True
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103e074)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff81052ad0)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105d940)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:reload_segments
```
```
In arch/x86/kernel/tls.c (ffffffff8106fee9)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8107630f)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In kernel/fork.c (ffffffff810f9c07)
Location: arch/x86/include/asm/segment.h:330
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff82174dcc)
Location: arch/x86/include/asm/segment.h:330
Inline: True
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022822)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff810305c3)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041583)
Location: arch/x86/include/asm/segment.h:347
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043480)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047515)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810901e1)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810971a2)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff818a8c60)
Location: arch/x86/include/asm/segment.h:347
Inline: True
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
In arch/x86/kernel/process_64.c (ffffffff8102003a)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81030c4e)
Location: arch/x86/include/asm/segment.h:347
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81032a9e)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103669b)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ecec)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81085c20)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81863905)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022682)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff81030423)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff810413c3)
Location: arch/x86/include/asm/segment.h:347
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810432c0)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047355)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090191)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81097152)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff818fa2c0)
Location: arch/x86/include/asm/segment.h:347
Inline: True
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022992)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
```
```
In arch/x86/kernel/process_64.c (ffffffff810312ba)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff810427a3)
Location: arch/x86/include/asm/segment.h:347
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810446c0)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048755)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092571)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8109e572)
Location: arch/x86/include/asm/segment.h:347
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8191b420)
Location: arch/x86/include/asm/segment.h:347
Inline: True
```
</details>
</li>
</ul>

## Differences
