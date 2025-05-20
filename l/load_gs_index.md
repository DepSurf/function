# Function: <code>load_gs_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d108)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b968)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81077fe8)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8107e4cd)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff816fb11d)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cd03)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b886)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d61a)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810794bf)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810801d0)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8176037d)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102cba1)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b0c6)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103cf0a)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d2af)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81084b30)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8178d37d)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102ada1)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81039123)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103af1e)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107baaf)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81081a10)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff817ab4fa)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102bae1)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bb17)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d94e)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810821b2)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810882e0)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81822b2d)
Location: arch/x86/include/asm/paravirt.h:238
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
In arch/x86/kernel/process_64.c (ffffffff8102cb0a)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cf87)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103eea9)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085872)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8108c030)
Location: arch/x86/include/asm/paravirt.h:238
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8186cd55)
Location: arch/x86/include/asm/paravirt.h:238
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
In arch/x86/kernel/process_64.c (ffffffff8102dd57)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e4b7)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810404a0)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c5e2)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810938f0)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8188cd65)
Location: arch/x86/include/asm/paravirt.h:287
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
In arch/x86/kernel/process_64.c (ffffffff8102fad6)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81040c3a)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81042b4e)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810906a9)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81097ff2)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff818d7739)
Location: arch/x86/include/asm/paravirt.h:287
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
In arch/x86/kernel/process_64.c (ffffffff81030436)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff810413ca)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810432be)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091209)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8109d879)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff819098a6)
Location: arch/x86/include/asm/paravirt.h:275
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
In arch/x86/kernel/process_64.c (ffffffff81032c6a)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81046ade)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096a14)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a4a39)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81bba34b)
Location: arch/x86/include/asm/paravirt.h:281
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
In arch/x86/kernel/process_64.c (ffffffff8103392c)
Location: arch/x86/include/asm/paravirt.h:278
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
In arch/x86/kernel/tls.c (ffffffff810461f6)
Location: arch/x86/include/asm/paravirt.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095c34)
Location: arch/x86/include/asm/paravirt.h:278
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a0149)
Location: arch/x86/include/asm/paravirt.h:278
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81bcebbb)
Location: arch/x86/include/asm/paravirt.h:278
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
In arch/x86/kernel/process_64.c (ffffffff81035476)
Location: arch/x86/include/asm/paravirt.h:295
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
In arch/x86/kernel/tls.c (ffffffff81047c16)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096594)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a0f09)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81bc256b)
Location: arch/x86/include/asm/paravirt.h:295
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
In arch/x86/kernel/process_64.c (ffffffff8103a756)
Location: arch/x86/include/asm/paravirt.h:295
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
In arch/x86/kernel/tls.c (ffffffff8104e4b6)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6534)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810b21f9)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81c92bf9)
Location: arch/x86/include/asm/paravirt.h:295
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
In arch/x86/kernel/process_64.c (ffffffff81041874)
Location: arch/x86/include/asm/paravirt.h:301
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
In arch/x86/kernel/tls.c (ffffffff8105963c)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb607)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:reload_segments
```
```
In kernel/fork.c (ffffffff810c7fa7)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff81e42562)
Location: arch/x86/include/asm/paravirt.h:301
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
In arch/x86/kernel/process_64.c (ffffffff8104afd4)
Location: arch/x86/include/asm/paravirt.h:301
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
In arch/x86/kernel/signal_32.c (ffffffff810556a7)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:reload_segments
```
```
In arch/x86/kernel/tls.c (ffffffff81066f6c)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In kernel/fork.c (ffffffff810e5167)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8201cf42)
Location: arch/x86/include/asm/paravirt.h:301
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
In arch/x86/kernel/process_64.c (ffffffff8104b852)
Location: arch/x86/include/asm/paravirt.h:303
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
In arch/x86/kernel/signal_32.c (ffffffff810566d7)
Location: arch/x86/include/asm/paravirt.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:reload_segments
```
```
In arch/x86/kernel/tls.c (ffffffff81068a4c)
Location: arch/x86/include/asm/paravirt.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In kernel/fork.c (ffffffff810f0807)
Location: arch/x86/include/asm/paravirt.h:303
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8209d5d2)
Location: arch/x86/include/asm/paravirt.h:303
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
In arch/x86/kernel/process_64.c (ffffffff81052aec)
Location: arch/x86/include/asm/paravirt.h:305
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
In arch/x86/kernel/signal_32.c (ffffffff8105d927)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:reload_segments
```
```
In arch/x86/kernel/tls.c (ffffffff8106fecc)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In kernel/fork.c (ffffffff810f9bff)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff82174dd2)
Location: arch/x86/include/asm/paravirt.h:305
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
In arch/x86/kernel/process_64.c (ffffffff81030596)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104154a)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104343e)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810901c9)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81097199)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff818a8c66)
Location: arch/x86/include/asm/paravirt.h:275
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
In arch/x86/kernel/process_64.c (ffffffff81020018)
Location: arch/x86/include/asm/special_insns.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff81030c17)
Location: arch/x86/include/asm/special_insns.h:189
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81032a5e)
Location: arch/x86/include/asm/special_insns.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ecd9)
Location: arch/x86/include/asm/special_insns.h:189
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81085c19)
Location: arch/x86/include/asm/special_insns.h:189
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8186390b)
Location: arch/x86/include/asm/special_insns.h:189
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
In arch/x86/kernel/process_64.c (ffffffff810303f6)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104138a)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104327e)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090179)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81097149)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff818fa2c6)
Location: arch/x86/include/asm/paravirt.h:275
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
In arch/x86/kernel/process_64.c (ffffffff8103128f)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104276a)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104467e)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092559)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8109e569)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - kernel/fork.c:mm_release
```
```
In arch/x86/power/cpu.c (ffffffff8191b426)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
```
</details>
</li>
</ul>

## Differences
