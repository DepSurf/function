# Function: <code>is_global_init</code>

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
In kernel/exit.c (0)
Location: include/linux/sched.h:2016
Inline: True
```
```
In kernel/signal.c (ffffffff8108dd35)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8110ca12)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2016
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:2016
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:2155
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:2155
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:2155
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2155
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2155
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:2155
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
In kernel/exit.c (0)
Location: include/linux/sched.h:2242
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:2242
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:2242
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2242
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2242
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:2242
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:1245
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1245
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1245
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1245
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1245
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:1245
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:1275
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1275
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1275
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1275
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1275
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:1275
Inline: True
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
In kernel/exit.c (ffffffff81091a1d)
Location: include/linux/sched.h:1367
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109db99)
Location: include/linux/sched.h:1367
Inline: True
Inline callers:
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81136e82)
Location: include/linux/sched.h:1367
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff811f3dcc)
Location: include/linux/sched.h:1367
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In fs/proc/base.c (ffffffff8131de44)
Location: include/linux/sched.h:1367
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff8161d072)
Location: include/linux/sched.h:1367
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff81099cfd)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810a6599)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81142602)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff81205c0f)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff8133522e)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff8163a2d2)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff8109e30c)
Location: include/linux/sched.h:1441
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ab28d)
Location: include/linux/sched.h:1441
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8114da22)
Location: include/linux/sched.h:1441
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff8121c218)
Location: include/linux/sched.h:1441
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff8135cd7f)
Location: include/linux/sched.h:1441
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff8166e5fa)
Location: include/linux/sched.h:1441
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810a63b3)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b1896)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81159732)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff81229be4)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff813754ef)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff81690c3a)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810ae177)
Location: include/linux/sched.h:1476
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b9ea6)
Location: include/linux/sched.h:1476
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8116aae2)
Location: include/linux/sched.h:1476
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff81256a41)
Location: include/linux/sched.h:1476
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff813bdf6b)
Location: include/linux/sched.h:1476
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8174372a)
Location: include/linux/sched.h:1476
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810a982a)
Location: include/linux/sched.h:1535
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b5156)
Location: include/linux/sched.h:1535
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81167222)
Location: include/linux/sched.h:1535
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff812615df)
Location: include/linux/sched.h:1535
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff813cfcbb)
Location: include/linux/sched.h:1535
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8175f5aa)
Location: include/linux/sched.h:1535
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810aa85c)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b6d46)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81167fb2)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff81265e1f)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff813d6b9b)
Location: include/linux/sched.h:1557
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8174341a)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810bc383)
Location: include/linux/sched.h:1655
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810c7259)
Location: include/linux/sched.h:1655
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8118d997)
Location: include/linux/sched.h:1655
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff812a3700)
Location: include/linux/sched.h:1655
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff814282da)
Location: include/linux/sched.h:1655
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff817c3eba)
Location: include/linux/sched.h:1655
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810d2e71)
Location: include/linux/sched.h:1680
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810df67b)
Location: include/linux/sched.h:1680
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff811bce87)
Location: include/linux/sched.h:1680
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff812fb651)
Location: include/linux/sched.h:1680
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/base.c (ffffffff814a1517)
Location: include/linux/sched.h:1680
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8190074a)
Location: include/linux/sched.h:1680
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810f19b1)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ff9f7)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff811fee37)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6c26)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In mm/oom_kill.c (ffffffff813656fb)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/base.c (ffffffff81536537)
Location: include/linux/sched.h:1702
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff81a5a35a)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810fd934)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8110ba3a)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81214237)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8ce6)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In mm/oom_kill.c (ffffffff81397b9e)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/base.c (ffffffff8156e6f7)
Location: include/linux/sched.h:1711
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff81aa498a)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff811067af)
Location: include/linux/pid.h:327
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff811153ea)
Location: include/linux/pid.h:327
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8122c187)
Location: include/linux/pid.h:327
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5cb6)
Location: include/linux/pid.h:327
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In mm/oom_kill.c (ffffffff813c19cc)
Location: include/linux/pid.h:327
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/base.c (ffffffff815a70b7)
Location: include/linux/pid.h:327
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff81af738a)
Location: include/linux/pid.h:327
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffff8000100fd348)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffff80001010d53c)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffff8000101c8d48)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffff8000102b79c8)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffff80001043f678)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffff800010864208)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (c035a460)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c0365880)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (c040fbc0)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (c04e4658)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/base.c (c06060b8)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (c0969dec)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In arch/powerpc/kernel/traps.c (c00000000002d818)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:die_will_crash
```
```
In kernel/exit.c (c000000000144194)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c000000000154718)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (c000000000231498)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (c00000000036f810)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (c000000000554bac)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (c000000000902bb0)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffe0000c5bda)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffe0000ce79a)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In mm/oom_kill.c (ffffffe0001dbc94)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/base.c (ffffffe0002d7326)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffe00053a5ac)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff8109fcd3)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810abc06)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81151d52)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff81222234)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff8136dacf)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff816566ba)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff8108e703)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109a596)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff81145032)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff812153e4)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff8135e55f)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff81636a4a)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff8109fc83)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ab166)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8114fc02)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff8121ffd4)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff8136b59f)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff81684a7a)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
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
In kernel/exit.c (ffffffff810a7bf3)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b3246)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/kexec_core.c (ffffffff8115ca62)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In mm/oom_kill.c (ffffffff8122f0cf)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/base.c (ffffffff8137ecf9)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In drivers/tty/sysrq.c (ffffffff8169f08a)
Location: include/linux/sched.h:1435
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
</details>
</li>
</ul>

## Differences
