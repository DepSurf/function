# Function: <code>swait_active</code>

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
In arch/x86/kernel/kvm.c (ffffffff810637d9)
Location: include/linux/swait.h:82
Inline: True
```
```
In kernel/sched/swait.c (ffffffff810c763e)
Location: include/linux/swait.h:82
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up
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
In arch/x86/kernel/kvm.c (ffffffff81066c89)
Location: include/linux/swait.h:82
Inline: True
```
```
In kernel/sched/swait.c (ffffffff810cd4fe)
Location: include/linux/swait.h:82
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up
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
In arch/x86/kernel/kvm.c (ffffffff81065f71)
Location: include/linux/swait.h:82
Inline: True
```
```
In kernel/sched/swait.c (ffffffff810c9f1e)
Location: include/linux/swait.h:82
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81069e7d)
Location: include/linux/swait.h:121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106cafd)
Location: include/linux/swait.h:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81072c0d)
Location: include/linux/swait.h:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810764dd)
Location: include/linux/swait.h:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810774ed)
Location: include/linux/swait.h:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f066)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107ec96)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f926)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8108e706)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109f1fb)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b6757)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b9867)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
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
In arch/x86/kernel/kvm.c (ffffffff810c0c93)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/rcu/tree.c (ffffffff811d3ef1)
Location: include/linux/swait.h:121
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
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
In virt/kvm/kvm_main.c (ffff8000100be914)
Location: include/linux/swait.h:134
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_on_spin
  - virt/kvm/kvm_main.c:kvm_vcpu_kick
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ed294)
Location: include/linux/swait.h:134
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810764ed)
Location: include/linux/swait.h:134
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
In arch/x86/kernel/kvm.c (ffffffff810664ad)
Location: include/linux/swait.h:134
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811150df)
Location: include/linux/swait.h:134
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107649d)
Location: include/linux/swait.h:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810784ed)
Location: include/linux/swait.h:134
Inline: True
```
</details>
</li>
</ul>

## Differences
