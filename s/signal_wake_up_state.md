# Function: <code>signal_wake_up_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dd70)
Location: kernel/signal.c:639
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff8108dd70-ffffffff8108dd9d: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090df0)
Location: kernel/signal.c:639
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81090df0-ffffffff81090e1d: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095d70)
Location: kernel/signal.c:645
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81095d70-ffffffff81095d98: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092d20)
Location: kernel/signal.c:659
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81092d20-ffffffff81092d48: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099c00)
Location: kernel/signal.c:661
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81099c00-ffffffff81099c28: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dbd0)
Location: kernel/signal.c:667
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff8109dbd0-ffffffff8109dbfb: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5ee0)
Location: kernel/signal.c:744
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810a5ee0-ffffffff810a5f0b: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aabb0)
Location: kernel/signal.c:754
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810aabb0-ffffffff810aabde: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b11b0)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b11b0-ffffffff810b11de: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc500)
Location: kernel/signal.c:759
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810ba850-ffffffff810ba882: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b77f0)
Location: kernel/signal.c:760
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b5b10-ffffffff810b5b42: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8d60)
Location: kernel/signal.c:759
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b7710-ffffffff810b7742: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb2f0)
Location: kernel/signal.c:760
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810c9b60-ffffffff810c9b92: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e493f)
Location: kernel/signal.c:763
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff810e15d0-ffffffff810e1615: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104fbf)
Location: kernel/signal.c:763
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff811018a0-ffffffff811018e5: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111123f)
Location: kernel/signal.c:768
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff8110daa0-ffffffff8110dae5: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111abbe)
Location: kernel/signal.c:759
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff811173e0-ffffffff81117425: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010cda8)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffff80001010cda8-ffff80001010ce18: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0365024)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
c0365024-c036506c: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153cf0)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
c000000000153cf0-c000000000153d80: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce358)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffe0000ce358-ffffffe0000ce3aa: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab520)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810ab520-ffffffff810ab54e: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099ec0)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81099ec0-ffffffff81099eee: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaa80)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810aaa80-ffffffff810aaaae: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct *t, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2b60)
Location: kernel/signal.c:759
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b2b60-ffffffff810b2b8e: signal_wake_up_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
