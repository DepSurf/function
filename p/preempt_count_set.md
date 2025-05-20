# Function: <code>preempt_count_set</code>

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
In init/main.c (ffffffff81002166)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810841b0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810859dc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff810a95d7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff810ec36b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810021d3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810872fe)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff818a1bdb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8189a66f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff810f3a0b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810021df)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff8108c24f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff818d711a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff818cec86)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff810fadb2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff8100220c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810893f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8190ef60)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8190612c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff810fd0c6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff8100222e)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff8109014e)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81c0027d)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81990173)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff811079a3)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810027f2)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff81094322)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81c00290)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff819eca74)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff81112f43)
Location: arch/x86/include/asm/preempt.h:26
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810027f2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff8109bf0a)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002b1)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a27b68)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff8111e722)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810028c2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810a0cd6)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002b1)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a98446)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff81129405)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810028c2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810a727a)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002b1)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81acfdb2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff811353a5)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810038e2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810aea00)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e0027c)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81bc870a)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff811444b5)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810039a0)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff81bdb79f)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8200025c)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81c41475)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff81140b11)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff81003980)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff81bcd8b2)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff82000257)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81c3344d)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff81141c91)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810039c0)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff81ca41f8)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff82000251)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81d51d7b)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff811651ec)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810015e5)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff81e53a91)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff822002ae)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81f22281)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff81198e5d)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff81001d10)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810f2036)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff820d7184)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff820ccb76)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff811d73ad)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff81001b52)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810fdfb6)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff8215a514)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff82150f2d)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/timer.c (ffffffff811eb70d)
Location: arch/x86/include/asm/preempt.h:30
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff81001b65)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff81106c66)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff8223ddb4)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8114b25b)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
```
```
In kernel/time/timer.c (ffffffff8120185d)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffff800010084ecc)
Location: arch/arm64/include/asm/preempt.h:15
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffff8000100fdbdc)
Location: arch/arm64/include/asm/preempt.h:15
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffff800010081eb4)
Location: arch/arm64/include/asm/preempt.h:15
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffff800010da1acc)
Location: arch/arm64/include/asm/preempt.h:15
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffff80001019e5d4)
Location: arch/arm64/include/asm/preempt.h:15
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (c03036d0)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (c035ae74)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (c0302c48)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (c0e99a00)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (c03e786c)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (c000000000010198)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (c000000000144cac)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (c000000000eeb0e0)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (c000000000ee2b98)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (c0000000001fe3dc)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffe0000b437e)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffe0000c637a)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffe0008cb5ca)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffe0008c511c)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffe00012c012)
Location: include/asm-generic/preempt.h:19
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810028c2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810a0b9a)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002b1)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a6ec22)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff8112db55)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff81000db2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff8108f5ba)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002a5)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a2b00c)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff811203c5)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810028c2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810a0b4a)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002b1)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81adb032)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff8112b875)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
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
In init/main.c (ffffffff810028c2)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffff810a8b09)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81e002e3)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81ae74f4)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/time/timer.c (ffffffff81137ef5)
Location: arch/x86/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
```
</details>
</li>
</ul>

## Differences
