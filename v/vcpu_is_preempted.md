# Function: <code>vcpu_is_preempted</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810d51d8)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810d5917)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d27f7)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
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
In kernel/locking/mutex.c (ffffffff810d41e9)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810d4897)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810d4e3d)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819096be)
Location: arch/x86/include/asm/qspinlock.h:37
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
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
In kernel/locking/mutex.c (ffffffff810dc142)
Location: arch/x86/include/asm/qspinlock.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810dc80e)
Location: arch/x86/include/asm/qspinlock.h:39
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810dcc80)
Location: arch/x86/include/asm/qspinlock.h:39
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819938fc)
Location: arch/x86/include/asm/qspinlock.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
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
In kernel/sched/core.c (ffffffff810c1502)
Location: arch/x86/include/asm/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff810e4755)
Location: arch/x86/include/asm/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810e4e54)
Location: arch/x86/include/asm/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810e5276)
Location: arch/x86/include/asm/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efe1a)
Location: arch/x86/include/asm/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
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
In kernel/sched/core.c (ffffffff810ca832)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff810efd45)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810f0434)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f0859)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b84c)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
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
In arch/x86/kernel/kvm.c (ffffffff810765da)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810d24dd)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff810f77a6)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810f85fc)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810f8aad)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f90db)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
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
In arch/x86/kernel/kvm.c (ffffffff810775ea)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810dc94d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff81103566)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81104444)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff811048bd)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8107e83a)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810e54cc)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8110e085)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110f0c3)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110f66f)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8107e46a)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810e2f7c)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8110b347)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110c295)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110c82f)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8107f58a)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810e4e4c)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8110d1d7)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110e0da)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110e65f)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8108e30c)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810fbd5c)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8112ca17)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8112d797)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8112ddd0)
Location: arch/x86/include/asm/qspinlock.h:60
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d549cc)
Location: arch/x86/include/asm/qspinlock.h:60
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
In arch/x86/kernel/kvm.c (ffffffff8109ef3a)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff81118208)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8114d9c7)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81f25b34)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8114ede0)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26573)
Location: arch/x86/include/asm/qspinlock.h:61
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
In arch/x86/kernel/kvm.c (ffffffff810b6bb4)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff8113f87e)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8117ccab)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff820d1505)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8117e022)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff8117e38c)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rtmutex_spin_on_owner
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
In arch/x86/kernel/kvm.c (ffffffff810b9d54)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff8114bdce)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8118d84b)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff82155791)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8118ecc2)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156477)
Location: arch/x86/include/asm/qspinlock.h:61
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
In arch/x86/kernel/kvm.c (ffffffff810c0fa4)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff81157b7e)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff8119c1fb)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff822385d1)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8119d670)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff822392b7)
Location: arch/x86/include/asm/qspinlock.h:61
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1847
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1847
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1847
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/sched.h:1847
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1847
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1847
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1847
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/sched.h:1847
Inline: True
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
In kernel/sched/core.c (c00000000018aaec)
Location: arch/powerpc/include/asm/spinlock.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (c0000000001c04a8)
Location: arch/powerpc/include/asm/spinlock.h:43
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (c0000000001c1c10)
Location: arch/powerpc/include/asm/spinlock.h:43
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (c0000000001c22e8)
Location: arch/powerpc/include/asm/spinlock.h:43
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1847
Inline: True
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
In arch/x86/kernel/kvm.c (ffffffff810765ea)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810d6b5d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff810fc876)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fd754)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810fdbcd)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8106657a)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810c544d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff810eca86)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810ed94e)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810eddcd)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8107659a)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810d379d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff810f9a36)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fa914)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810fad8d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
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
In arch/x86/kernel/kvm.c (ffffffff8107876a)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
```
In kernel/sched/core.c (ffffffff810de71d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
```
```
In kernel/locking/mutex.c (ffffffff81104ba8)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81105ae6)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff81105f5d)
Location: arch/x86/include/asm/qspinlock.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
</details>
</li>
</ul>

## Differences
