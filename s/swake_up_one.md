# Function: <code>swake_up_one</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810e3840)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_gp_kthread_wake
```
**Symbols:**

```
ffffffff810e3840-ffffffff810e387c: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ea460)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff810ea460-ffffffff810ea4a0: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f5e30)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff810f5e30-ffffffff810f5e70: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff5c0)
Location: kernel/sched/swait.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
```
**Symbols:**

```
ffffffff810ff5c0-ffffffff810ff61d: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fdfd0)
Location: kernel/sched/swait.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
```
**Symbols:**

```
ffffffff810fdfd0-ffffffff810fe02d: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff811003b0)
Location: kernel/sched/swait.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff811003b0-ffffffff8110040d: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c430)
Location: kernel/sched/swait.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff8111c430-ffffffff8111c48d: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141ea0)
Location: kernel/sched/swait.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
```
**Symbols:**

```
ffffffff81141ea0-ffffffff81141f0b: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116cf20)
Location: kernel/sched/swait.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
```
**Symbols:**

```
ffffffff8116cf20-ffffffff8116cf8b: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d840)
Location: kernel/sched/swait.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
```
**Symbols:**

```
ffffffff8117d840-ffffffff8117d8ab: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118ba90)
Location: kernel/sched/swait.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rdp_offload_toggle
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:swake_up_one_online_ipi
```
**Symbols:**

```
ffffffff8118ba90-ffffffff8118bb02: swake_up_one (STB_GLOBAL)
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
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffff800010159618)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_kick
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
  - virt/kvm/arm/arm.c:kvm_arm_resume_guest
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffff800010159618-ffff8000101596c0: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c03a69dc)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
c03a69dc-c03a6a24: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c0000000001ada90)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
c0000000001ada90-c0000000001adb00: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffe0000ff508)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffe0000ff508-ffffffe0000ff558: swake_up_one (STB_GLOBAL)
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
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ef230)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff810ef230-ffffffff810ef270: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810df2b0)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff810df2b0-ffffffff810df2f0: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ec360)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff810ec360-ffffffff810ec3a0: swake_up_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f7490)
Location: kernel/sched/swait.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
```
**Symbols:**

```
ffffffff810f7490-ffffffff810f74d0: swake_up_one (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
