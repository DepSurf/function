# Function: <code>prepare_to_swait_event</code>

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
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c75e0)
Location: kernel/sched/swait.c:93
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810c75e0-ffffffff810c7624: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810cd4b0)
Location: kernel/sched/swait.c:93
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - drivers/base/firmware_class.c:__fw_state_wait_common
```
**Symbols:**

```
ffffffff810cd4b0-ffffffff810cd4ef: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c9e30)
Location: kernel/sched/swait.c:93
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810c9e30-ffffffff810c9e70: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d1650)
Location: kernel/sched/swait.c:88
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810d1650-ffffffff810d1691: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d9ba0)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810d9ba0-ffffffff810d9be1: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810e36a0)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810e36a0-ffffffff810e3777: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ea320)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ea320-ffffffff810ea401: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f5cf0)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f5cf0-ffffffff810f5dd1: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff4d0)
Location: kernel/sched/swait.c:103
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff810ff4d0-ffffffff810ff5b7: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fe030)
Location: kernel/sched/swait.c:103
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff810fe030-ffffffff810fe122: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff81100410)
Location: kernel/sched/swait.c:103
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff81100410-ffffffff81100502: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c490)
Location: kernel/sched/swait.c:103
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8111c490-ffffffff8111c569: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81142630)
Location: kernel/sched/swait.c:102
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff81142630-ffffffff81142717: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116fe60)
Location: kernel/sched/swait.c:102
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8116fe60-ffffffff8116ff47: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117fb20)
Location: kernel/sched/swait.c:102
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8117fb20-ffffffff8117fc07: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118d090)
Location: kernel/sched/swait.c:102
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8118d090-ffffffff8118d177: prepare_to_swait_event (STB_GLOBAL)
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
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffff800010159328)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - kernel/power/suspend.c:s2idle_loop
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffff800010159328-ffff80001015947c: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c03a6850)
Location: kernel/sched/swait.c:90
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
c03a6850-c03a6978: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c0000000001ad8c0)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c0000000001ad8c0-c0000000001ad9f8: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffe0000ff3f2)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffe0000ff3f2-ffffffe0000ff49a: prepare_to_swait_event (STB_GLOBAL)
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
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ef0f0)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ef0f0-ffffffff810ef1d1: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810df170)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810df170-ffffffff810df251: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ec220)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ec220-ffffffff810ec301: prepare_to_swait_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f7350)
Location: kernel/sched/swait.c:90
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f7350-ffffffff810f7431: prepare_to_swait_event (STB_GLOBAL)
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
