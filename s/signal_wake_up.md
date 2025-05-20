# Function: <code>signal_wake_up</code>

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
In kernel/signal.c (ffffffff8108ddb6)
Location: include/linux/sched.h:3074
Inline: True
Inline callers:
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
```
```
In kernel/freezer.c (ffffffff810e9d5f)
Location: include/linux/sched.h:3074
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff8126ebd6)
Location: include/linux/sched.h:3074
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810910a4)
Location: include/linux/sched.h:3351
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (ffffffff810f0ab1)
Location: include/linux/sched.h:3351
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff8129a346)
Location: include/linux/sched.h:3351
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff81096010)
Location: include/linux/sched.h:3520
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (ffffffff810f7c11)
Location: include/linux/sched.h:3520
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff812aeed6)
Location: include/linux/sched.h:3520
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff81092ff0)
Location: include/linux/sched/signal.h:348
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (ffffffff810f9ae1)
Location: include/linux/sched/signal.h:348
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff812bc306)
Location: include/linux/sched/signal.h:348
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff81099ed0)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (ffffffff811045a4)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff812dfc04)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff8109dedc)
Location: include/linux/sched/signal.h:377
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff8110c4a4)
Location: include/linux/sched/signal.h:377
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
```
```
In kernel/freezer.c (ffffffff8110f3a4)
Location: include/linux/sched/signal.h:377
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff8130be30)
Location: include/linux/sched/signal.h:377
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810a61ec)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff81117c94)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
```
```
In kernel/freezer.c (ffffffff8111a9f0)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In fs/coredump.c (ffffffff81321690)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810aaebd)
Location: include/linux/sched/signal.h:392
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff81121ab9)
Location: include/linux/sched/signal.h:392
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (ffffffff811250f6)
Location: include/linux/sched/signal.h:392
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8115dd2e)
Location: include/linux/sched/signal.h:392
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff81348f42)
Location: include/linux/sched/signal.h:392
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810b14bd)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff8112e0d9)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (ffffffff811310b6)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8116991e)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff813611e2)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810bc500)
Location: include/linux/sched/signal.h:407
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/task_work.c (ffffffff810ce569)
Location: include/linux/sched/signal.h:407
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8113c4f7)
Location: include/linux/sched/signal.h:407
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
```
```
In kernel/freezer.c (ffffffff81140486)
Location: include/linux/sched/signal.h:407
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8117b48e)
Location: include/linux/sched/signal.h:407
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff813a7012)
Location: include/linux/sched/signal.h:407
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810b77f0)
Location: include/linux/sched/signal.h:420
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/livepatch/transition.c (ffffffff81136c07)
Location: include/linux/sched/signal.h:420
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
```
```
In kernel/freezer.c (ffffffff8113c7f6)
Location: include/linux/sched/signal.h:420
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8117832e)
Location: include/linux/sched/signal.h:420
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff813b7db2)
Location: include/linux/sched/signal.h:420
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810b8d60)
Location: include/linux/sched/signal.h:421
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/freezer.c (ffffffff8113da46)
Location: include/linux/sched/signal.h:421
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81178e9e)
Location: include/linux/sched/signal.h:421
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff813beeb2)
Location: include/linux/sched/signal.h:421
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810cb2f0)
Location: include/linux/sched/signal.h:419
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/freezer.c (ffffffff81160bc6)
Location: include/linux/sched/signal.h:419
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff811a07ce)
Location: include/linux/sched/signal.h:419
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff8140ece2)
Location: include/linux/sched/signal.h:419
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810e493f)
Location: include/linux/sched/signal.h:449
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/freezer.c (ffffffff8119394f)
Location: include/linux/sched/signal.h:449
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff811d0f30)
Location: include/linux/sched/signal.h:449
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff814847dc)
Location: include/linux/sched/signal.h:449
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In kernel/signal.c (ffffffff81104fbf)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/freezer.c (ffffffff811d131d)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81214aa0)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff81517cdc)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In kernel/signal.c (ffffffff8111123f)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/freezer.c (ffffffff811e558d)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8122a3c0)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff8154f5cf)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In kernel/signal.c (ffffffff8111abbe)
Location: include/linux/sched/signal.h:441
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/freezer.c (ffffffff811fb33d)
Location: include/linux/sched/signal.h:441
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81242380)
Location: include/linux/sched/signal.h:441
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff8158540f)
Location: include/linux/sched/signal.h:441
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In kernel/signal.c (ffff80001010d0d0)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (ffff80001019841c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffff8000101dce1c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffff800010427784)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (c036533c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (c03e33c4)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (c041ee9c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (c05f033c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000154180)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (c0000000001f31ec)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (c0000000001f833c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (c00000000024aba0)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (c000000000537480)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffe0000ce606)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/freezer.c (ffffffe0001290d2)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffe000154a9c)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffe0002c5c70)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810ab82d)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff811266b9)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (ffffffff81129866)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81161f3e)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff813597c2)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff8109a1cd)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff81119115)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (ffffffff8111c0f6)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8115519e)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff8134a472)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810aad8d)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff811245a9)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (ffffffff81127586)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8115fd0e)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff81357292)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
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
In kernel/signal.c (ffffffff810b2e6d)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/livepatch/transition.c (ffffffff81130c04)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/freezer.c (ffffffff81133bc6)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8116d03e)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In fs/coredump.c (ffffffff8136a972)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
</details>
</li>
</ul>

## Differences
