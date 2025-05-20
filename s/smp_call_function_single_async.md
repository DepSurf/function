# Function: <code>smp_call_function_single_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103a60)
Location: kernel/smp.c:327
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
```
**Symbols:**

```
ffffffff81103a60-ffffffff81103ac7: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110ae90)
Location: kernel/smp.c:311
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
```
**Symbols:**

```
ffffffff8110ae90-ffffffff8110aefc: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811126b0)
Location: kernel/smp.c:315
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
```
**Symbols:**

```
ffffffff811126b0-ffffffff8111271c: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113bd0)
Location: kernel/smp.c:324
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:__blk_mq_complete_request
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81113bd0-ffffffff81113c09: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f180)
Location: kernel/smp.c:326
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:__blk_mq_complete_request
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8111f180-ffffffff8111f1b9: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c4b0)
Location: kernel/smp.c:326
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8112c4b0-ffffffff8112c4e9: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81137d80)
Location: kernel/smp.c:326
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81137d80-ffffffff81137db9: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81142f00)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81142f00-ffffffff81142f39: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114ea40)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8114ea40-ffffffff8114ea79: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115faf0)
Location: kernel/smp.c:411
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:kick_ilb
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_force_complete_rq
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8115faf0-ffffffff8115fb13: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ba90)
Location: kernel/smp.c:545
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:kick_ilb
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8115ba90-ffffffff8115bab3: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ccb0)
Location: kernel/smp.c:787
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8115ccb0-ffffffff8115ccd3: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181ee0)
Location: kernel/smp.c:789
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81181ee0-ffffffff81181f03: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b8660)
Location: kernel/smp.c:808
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-mq.c:blk_mq_complete_request_remote
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff811b8660-ffffffff811b86ab: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f99d0)
Location: kernel/smp.c:807
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-mq.c:blk_mq_complete_request_remote
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff811f99d0-ffffffff811f9a1b: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120f070)
Location: kernel/smp.c:661
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-mq.c:blk_mq_complete_request_remote
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8120f070-ffffffff8120f0bb: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81226810)
Location: kernel/smp.c:681
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-mq.c:blk_mq_complete_request_remote
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81226810-ffffffff8122685b: smp_call_function_single_async (STB_GLOBAL)
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
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bce78)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffff8000101bce78-ffff8000101bcf00: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0404fdc)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - drivers/cpuidle/coupled.c:cpuidle_coupled_poke_others
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
c0404fdc-c040509c: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000222fe0)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
c000000000222fe0-c000000000223080: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe0001406e4)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffe0001406e4-ffffffe000140742: smp_call_function_single_async (STB_GLOBAL)
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
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81147060)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81147060-ffffffff81147099: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a340)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff8113a340-ffffffff8113a379: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81144f10)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81144f10-ffffffff81144f49: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81151ab0)
Location: kernel/smp.c:335
Inline: False
Direct callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - net/core/dev.c:net_rps_send_ipi
```
**Symbols:**

```
ffffffff81151ab0-ffffffff81151b00: smp_call_function_single_async (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct call_single_data *csd</code> ➡️ <code>call_single_data_t *csd</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>call_single_data_t *csd</code> ➡️ <code>struct __call_single_data *csd</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __call_single_data *csd</code> ➡️ <code>call_single_data_t *csd</code>
</li>
</ul>
</details>
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
