# Function: <code>queued_spin_trylock</code>

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
In arch/x86/kernel/dumpstack.c (ffffffff81031ad2)
Location: include/asm-generic/qspinlock.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In kernel/locking/spinlock.c (ffffffff818240c9)
Location: include/asm-generic/qspinlock.h:62
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
```
```
In kernel/locking/qspinlock.c (ffffffff810ca780)
Location: include/asm-generic/qspinlock.h:62
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/trace/trace.c (ffffffff8114e7ed)
Location: include/asm-generic/qspinlock.h:62
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
In arch/x86/kernel/dumpstack.c (ffffffff81030be2)
Location: include/asm-generic/qspinlock.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In kernel/locking/spinlock.c (ffffffff8189edb0)
Location: include/asm-generic/qspinlock.h:82
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810cf177)
Location: include/asm-generic/qspinlock.h:82
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811574bd)
Location: include/asm-generic/qspinlock.h:82
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
In arch/x86/kernel/dumpstack.c (ffffffff810307c2)
Location: include/asm-generic/qspinlock.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81065898)
Location: include/asm-generic/qspinlock.h:82
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff818d4270)
Location: include/asm-generic/qspinlock.h:82
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810d5b67)
Location: include/asm-generic/qspinlock.h:82
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811625fd)
Location: include/asm-generic/qspinlock.h:82
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
In arch/x86/kernel/dumpstack.c (ffffffff8102ea92)
Location: include/asm-generic/qspinlock.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81064c88)
Location: include/asm-generic/qspinlock.h:82
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff8190b400)
Location: include/asm-generic/qspinlock.h:82
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810d4ae7)
Location: include/asm-generic/qspinlock.h:82
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811624ce)
Location: include/asm-generic/qspinlock.h:82
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
In arch/x86/kernel/dumpstack.c (ffffffff81030962)
Location: include/asm-generic/qspinlock.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81068e19)
Location: include/asm-generic/qspinlock.h:69
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff819957b4)
Location: include/asm-generic/qspinlock.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810dcd97)
Location: include/asm-generic/qspinlock.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8116f4ce)
Location: include/asm-generic/qspinlock.h:69
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
In arch/x86/kernel/dumpstack.c (ffffffff81031b7f)
Location: include/asm-generic/qspinlock.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8106b5bc)
Location: include/asm-generic/qspinlock.h:67
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff819f1cc4)
Location: include/asm-generic/qspinlock.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810e53d5)
Location: include/asm-generic/qspinlock.h:67
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8117e546)
Location: include/asm-generic/qspinlock.h:67
Inline: True
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
In arch/x86/kernel/dumpstack.c (ffffffff81032e89)
Location: include/asm-generic/qspinlock.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81071638)
Location: include/asm-generic/qspinlock.h:67
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a2d204)
Location: include/asm-generic/qspinlock.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810f09ec)
Location: include/asm-generic/qspinlock.h:67
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118be3e)
Location: include/asm-generic/qspinlock.h:67
Inline: True
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
In arch/x86/kernel/dumpstack.c (ffffffff81034c9f)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff810754b9)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a9d390)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810f8dd0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811992d7)
Location: include/asm-generic/qspinlock.h:58
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
In arch/x86/kernel/dumpstack.c (ffffffff810354cf)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81076489)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81ad4b70)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff81104be0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a4c37)
Location: include/asm-generic/qspinlock.h:58
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
In arch/x86/kernel/dumpstack.c (ffffffff810374af)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d4a9)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81bcca80)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8110faa9)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bdae0)
Location: include/asm-generic/qspinlock.h:58
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
In arch/x86/kernel/dumpstack.c (ffffffff8103856f)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d419)
Location: include/asm-generic/qspinlock.h:61
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81c455e0)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8110cc69)
Location: include/asm-generic/qspinlock.h:61
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bb700)
Location: include/asm-generic/qspinlock.h:61
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
In arch/x86/kernel/dumpstack.c (ffffffff8103a0af)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8107e7b7)
Location: include/asm-generic/qspinlock.h:61
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81c38870)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8110e95a)
Location: include/asm-generic/qspinlock.h:61
Inline: True
```
```
In kernel/trace/trace_clock.c (ffffffff811aa1b3)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/trace.c (ffffffff811bb97b)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_save_cmdline
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
In arch/x86/kernel/dumpstack.c (ffffffff8103fa5f)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8108d437)
Location: include/asm-generic/qspinlock.h:61
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81d57150)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8112e11c)
Location: include/asm-generic/qspinlock.h:61
Inline: True
```
```
In kernel/trace/trace_clock.c (ffffffff811d3d23)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/trace.c (ffffffff811e606b)
Location: include/asm-generic/qspinlock.h:61
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_save_cmdline
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
In arch/x86/kernel/dumpstack.c (ffffffff810471cd)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d689)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/locking/spinlock.c (ffffffff81f29e40)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8114f278)
Location: include/asm-generic/qspinlock.h:90
Inline: True
```
```
In kernel/trace/trace_clock.c (ffffffff8120888e)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/trace.c (ffffffff8121dcf5)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_save_cmdline
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
In arch/x86/kernel/dumpstack.c (ffffffff8105142d)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff810b479a)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/locking/spinlock.c (ffffffff820d5dd0)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff820d663b)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81250d9e)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/trace.c (ffffffff812683a5)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_save_cmdline
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
In arch/x86/kernel/dumpstack.c (ffffffff8105218d)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7874)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/locking/spinlock.c (ffffffff821591b0)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff821599c2)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8126811e)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/trace.c (ffffffff8127f565)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_save_cmdline
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
In arch/x86/kernel/dumpstack.c (ffffffff810593ad)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff810becb4)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/locking/spinlock.c (ffffffff8223ca30)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d242)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8128238e)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/trace.c (ffffffff81299d45)
Location: include/asm-generic/qspinlock.h:90
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_save_cmdline
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
In kernel/signal.c (ffff800010113a78)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffff80001014bcbc)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/rt.c (ffff800010151058)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffff800010153b2c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/locking/qspinlock.c (ffff80001016a970)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffff80001016b2ec)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk_safe.c (ffff800010177048)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
```
In kernel/rcu/tree.c (ffff80001018ed50)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:note_gp_changes
```
```
In kernel/debug/debug_core.c (ffff8000101fa23c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203e28)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff800010218488)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
```
```
In kernel/trace/trace.c (ffff800010222684)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/padata.c (ffff8000102a9d1c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/compaction.c (ffff8000102ea140)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In mm/workingset.c (ffff8000102f0014)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffff8000103a5d10)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffff8000103aef44)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/aio.c (ffff8000103fe884)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffff800010402210)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_wake
```
```
In fs/ext4/balloc.c (ffff8000104609f0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010473d7c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010495348)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/super.c (ffff8000104bd000)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In security/selinux/avc.c (ffff800010546d54)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/blk-ioc.c (ffff8000105e86b4)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffff80001060e3cc)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In lib/random32.c (ffff80001062a3f4)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - lib/random32.c:__prandom_reseed
```
```
In drivers/acpi/apei/erst.c (ffff8000107ae5e0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In drivers/clk/clk.c (ffff8000107bf9e4)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/tty/vt/vt.c (ffff8000108743d8)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b1e4)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010896f6c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
```
```
In drivers/tty/serial/imx.c (ffff80001089ddf8)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_console_write
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089ec04)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3230)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5e84)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6edc)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
```
```
In drivers/char/random.c (ffff8000108b077c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_fast_load
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc5e0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c864)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ee50)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/net_namespace.c (ffff800010bc19b8)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/core/dev.c (ffff800010bce6b0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffff800010c11350)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffff800010ca4ad0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffff800010ccae7c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/ip6_fib.c (ffff800010d1c05c)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/icmp.c (ffff800010d2c5f8)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffff800010d43168)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In lib/ratelimit.c (ffff800010d8ed80)
Location: include/asm-generic/qspinlock.h:58
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103562f)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81075489)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a739e0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810fdef0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119d257)
Location: include/asm-generic/qspinlock.h:58
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
In arch/x86/kernel/dumpstack.c (ffffffff81024f82)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81065285)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a2fd40)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810ee0f0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811902b7)
Location: include/asm-generic/qspinlock.h:58
Inline: True
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
In arch/x86/kernel/dumpstack.c (ffffffff8103548f)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81075439)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81adfdf0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff810fb0b0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119b027)
Location: include/asm-generic/qspinlock.h:58
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
In arch/x86/kernel/dumpstack.c (ffffffff8103646f)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81077499)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81aec6e0)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff81106280)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a8cc7)
Location: include/asm-generic/qspinlock.h:58
Inline: True
```
</details>
</li>
</ul>

## Differences
