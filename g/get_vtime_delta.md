# Function: <code>get_vtime_delta</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_vtime_delta(struct vtime *vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176270)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_guest_exit
  - kernel/sched/build_policy.c:vtime_guest_enter
  - kernel/sched/build_policy.c:vtime_user_exit
  - kernel/sched/build_policy.c:vtime_user_enter
  - kernel/sched/build_policy.c:vtime_account_kernel
  - kernel/sched/build_policy.c:vtime_account_kernel
```
**Symbols:**

```
ffffffff81176270-ffffffff8117632e: get_vtime_delta (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 get_vtime_delta(struct vtime *vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c82d0)
Location: kernel/sched/cputime.c:695
Inline: False
Direct callers:
  - kernel/sched/cputime.c:vtime_account_idle
  - kernel/sched/cputime.c:vtime_user_exit
  - kernel/sched/cputime.c:vtime_account_guest
  - kernel/sched/cputime.c:__vtime_account_system
```
**Symbols:**

```
ffffffff810c82d0-ffffffff810c8387: get_vtime_delta (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
