# Function: <code>finish_swait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c74f0)
Location: kernel/sched/swait.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810c74f0-ffffffff810c7554: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810cd3c0)
Location: kernel/sched/swait.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - drivers/base/firmware_class.c:__fw_state_wait_common
```
**Symbols:**

```
ffffffff810cd3c0-ffffffff810cd425: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c9dc0)
Location: kernel/sched/swait.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810c9dc0-ffffffff810c9e2a: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d15e0)
Location: kernel/sched/swait.c:106
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810d15e0-ffffffff810d164a: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d9bf0)
Location: kernel/sched/swait.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810d9bf0-ffffffff810d9c55: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810e3780)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810e3780-ffffffff810e37e5: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ea2b0)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ea2b0-ffffffff810ea318: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f5c80)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f5c80-ffffffff810f5ce8: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff460)
Location: kernel/sched/swait.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff810ff460-ffffffff810ff4c8: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fdf60)
Location: kernel/sched/swait.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff810fdf60-ffffffff810fdfcb: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff81100340)
Location: kernel/sched/swait.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff81100340-ffffffff811003ab: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c3c0)
Location: kernel/sched/swait.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8111c3c0-ffffffff8111c42a: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113b7b0)
Location: kernel/sched/swait.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8113b7b0-ffffffff8113b829: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811661c0)
Location: kernel/sched/swait.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff811661c0-ffffffff81166239: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176630)
Location: kernel/sched/swait.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff81176630-ffffffff811766a9: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811848b0)
Location: kernel/sched/swait.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff811848b0-ffffffff81184929: finish_swait (STB_GLOBAL)
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
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffff8000101597e0)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffff8000101597e0-ffff8000101598bc: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c03a66bc)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c03a66bc-c03a673c: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c0000000001ad810)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c0000000001ad810-c0000000001ad8c0: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffe0000ff38c)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffe0000ff38c-ffffffe0000ff3f2: finish_swait (STB_GLOBAL)
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
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ef080)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ef080-ffffffff810ef0e8: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810df100)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810df100-ffffffff810df168: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ec1b0)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ec1b0-ffffffff810ec218: finish_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f7200)
Location: kernel/sched/swait.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f7200-ffffffff810f7268: finish_swait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
