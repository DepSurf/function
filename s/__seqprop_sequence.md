# Function: <code>__seqprop_sequence</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81109ef9)
Location: include/linux/seqlock.h:259
Inline: True
```
```
In mm/gup.c (ffffffff81295094)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In lib/flex_proportions.c (ffffffff8160dc38)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/gen_stats.c (ffffffff819f6d9b)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819f75b1)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81a06d87)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6e73d)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2accb)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In kernel/sched/psi.c (ffffffff8110bc3c)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In mm/gup.c (ffffffff8129aa54)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In lib/flex_proportions.c (ffffffff815f1388)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/gen_stats.c (ffffffff819dcf1b)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819dd731)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff819ee48d)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a56fcd)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In kernel/sched/psi.c (ffffffff8112a700)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In mm/gup.c (ffffffff812db404)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In lib/flex_proportions.c (ffffffff8165e4f8)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/gen_stats.c (ffffffff81a8d18f)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81a8da11)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81a9f72d)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0fe02)
Location: include/linux/seqlock.h:259
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810611a8)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_utility.c (ffffffff811437a3)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
```
In mm/gup.c (ffffffff8133afe8)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In lib/flex_proportions.c (ffffffff81777c68)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/gen_estimator.c (ffffffff81c03324)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fb15)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8116eeb5)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In mm/gup.c (ffffffff813b2c31)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In net/core/gen_estimator.c (ffffffff81db28e4)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In lib/flex_proportions.c (ffffffff82020948)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81071715)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_utility.c (ffffffff81180622)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/time/tick-sched.c (ffffffff81204fb8)
Location: include/linux/seqlock.h:257
Inline: True
```
```
In mm/gup.c (ffffffff813e78a1)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In net/core/gen_estimator.c (ffffffff81e22eb4)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In lib/flex_proportions.c (ffffffff820a0988)
Location: include/linux/seqlock.h:257
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078ed5)
Location: include/linux/seqlock.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81175400)
Location: include/linux/seqlock.h:209
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:task_gtime
```
```
In kernel/sched/build_utility.c (ffffffff8118e372)
Location: include/linux/seqlock.h:209
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/time/tick-sched.c (ffffffff8121b688)
Location: include/linux/seqlock.h:209
Inline: True
```
```
In mm/gup.c (ffffffff81412511)
Location: include/linux/seqlock.h:209
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In net/core/gen_estimator.c (ffffffff81ee0df4)
Location: include/linux/seqlock.h:209
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In lib/flex_proportions.c (ffffffff82178968)
Location: include/linux/seqlock.h:209
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
