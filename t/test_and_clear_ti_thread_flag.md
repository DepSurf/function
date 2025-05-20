# Function: <code>test_and_clear_ti_thread_flag</code>

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
In arch/x86/kernel/process.c (ffffffff810392ed)
Location: include/linux/thread_info.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103deb2)
Location: include/linux/thread_info.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064e3c)
Location: include/linux/thread_info.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
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
In arch/x86/kernel/process.c (ffffffff81038311)
Location: include/linux/thread_info.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103dcd2)
Location: include/linux/thread_info.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064bf0)
Location: include/linux/thread_info.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In mm/oom_kill.c (ffffffff811a4f75)
Location: include/linux/thread_info.h:85
Inline: True
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
In arch/x86/kernel/process.c (ffffffff81037dc1)
Location: include/linux/thread_info.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103d59b)
Location: include/linux/thread_info.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff810680c0)
Location: include/linux/thread_info.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
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
In arch/x86/kernel/process.c (ffffffff81035c9e)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103b5eb)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff810673e0)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff810f8e09)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81037fa2)
Location: include/linux/thread_info.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103e00b)
Location: include/linux/thread_info.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b630)
Location: include/linux/thread_info.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81103829)
Location: include/linux/thread_info.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81039162)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103f5bb)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810436a7)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106e300)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff8110c558)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103a315)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81040bbb)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff810742d0)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81117d48)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103c8d5)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104329b)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e20)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81122089)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103d095)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810439fb)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078e90)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff8112e6a9)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103ff35)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104729b)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108017c)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff8113c859)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff8103fe75)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81046af0)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fd9c)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81136f69)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81041805)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81048520)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080e5c)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81137c39)
Location: include/linux/thread_info.h:110
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81047aa5)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104ee60)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fdcc)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff8115a989)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81050bf5)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8105a0b0)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0c8e)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff8118423c)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff8105e155)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81067ac0)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8a11)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff811bf4cc)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff8105f805)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81069370)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbbe1)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff811d1fac)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103d7ee)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
```
In arch/x86/kernel/process.c (ffffffff81066965)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810707e0)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff811e6c2c)
Location: include/linux/thread_info.h:111
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff800010088068)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
```
In arch/arm64/kernel/signal.c (ffff800010093410)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In fs/select.c (ffff8000103a2378)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffff8000103f2db4)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
```
```
In fs/aio.c (ffff8000103fce00)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffff800010405b9c)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/signal.c (c030e9d0)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
```
```
In fs/select.c (c0584f14)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (c05c85ec)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (c05d1b68)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (c05d7370)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f3a60)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/signal.c (ffffffe0000b6a30)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
```
In fs/select.c (ffffffe00026a92c)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffe0002a4bcc)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (ffffffe0002ac580)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffe0002b0f5e)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
```
</details>
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
In arch/x86/kernel/process.c (ffffffff8103d215)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81043b7b)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e90)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81126c89)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8102c8c5)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810331ab)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff811196e9)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103d055)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810439bb)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e40)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff81124b79)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103e0e5)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81044dbb)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079f2e)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In kernel/livepatch/transition.c (ffffffff8113098c)
Location: include/linux/thread_info.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
</details>
</li>
</ul>

## Differences
