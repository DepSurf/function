# Function: <code>rq_unlock_irq</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af6f0)
Location: kernel/sched/sched.h:1750
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810c193b)
Location: kernel/sched/sched.h:1750
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
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
In kernel/sched/core.c (ffffffff810b69ce)
Location: kernel/sched/sched.h:1789
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810c9093)
Location: kernel/sched/sched.h:1789
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
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
In kernel/sched/core.c (ffffffff810bc5cf)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff810c4daf)
Location: kernel/sched/sched.h:1170
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/psi.c (ffffffff810ef869)
Location: kernel/sched/sched.h:1170
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810ce463)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/psi.c (ffffffff810f6d0b)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d8063)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810ecb30)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff81102a9b)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810df3af)
Location: kernel/sched/sched.h:1284
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810f69cc)
Location: kernel/sched/sched.h:1284
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff8110daba)
Location: kernel/sched/sched.h:1284
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810dc048)
Location: kernel/sched/sched.h:1342
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/fair.c (ffffffff810f4b7f)
Location: kernel/sched/sched.h:1342
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff8110adf8)
Location: kernel/sched/sched.h:1342
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810de068)
Location: kernel/sched/sched.h:1355
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/fair.c (ffffffff810f6c6f)
Location: kernel/sched/sched.h:1355
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff8110ca28)
Location: kernel/sched/sched.h:1355
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810f2d2d)
Location: kernel/sched/sched.h:1642
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/fair.c (ffffffff81110ebe)
Location: kernel/sched/sched.h:1642
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff8112ba74)
Location: kernel/sched/sched.h:1642
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8110eae9)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/fair.c (ffffffff8112d0eb)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8114c221)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_leave
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff811358a5)
Location: kernel/sched/sched.h:1661
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/fair.c (ffffffff81156e5a)
Location: kernel/sched/sched.h:1661
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8117b07f)
Location: kernel/sched/sched.h:1661
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff81144a07)
Location: kernel/sched/sched.h:1688
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/fair.c (ffffffff81166f09)
Location: kernel/sched/sched.h:1688
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8118bbbd)
Location: kernel/sched/sched.h:1688
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8114ff55)
Location: kernel/sched/sched.h:1712
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff81173c89)
Location: kernel/sched/sched.h:1712
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8119a51d)
Location: kernel/sched/sched.h:1712
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffff8000101387f0)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffff80001014d08c)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffff8000101678b4)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c0387504)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (c039ada4)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (c03b46cc)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c0000000001844b0)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (c00000000019fe68)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (c0000000001bf650)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffe0000e86d2)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffe0000f6406)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffe000109e0a)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d2533)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810e6c90)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff810fbdab)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810c0b6d)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff810d5e30)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff810ebfb5)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d02e3)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810e3060)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff810f8f6b)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d9c41)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810eec3f)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff811040ab)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
</ul>

## Differences
