# Function: <code>delayacct_clear_flag</code>

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
In kernel/sched/core.c (ffffffff8181f981)
Location: include/linux/delayacct.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In mm/memory.c (ffffffff811bf58c)
Location: include/linux/delayacct.h:59
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
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
In kernel/sched/core.c (ffffffff8189a081)
Location: include/linux/delayacct.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In mm/memory.c (ffffffff811d9b0c)
Location: include/linux/delayacct.h:59
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff818ce721)
Location: include/linux/delayacct.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In mm/memory.c (ffffffff811e963f)
Location: include/linux/delayacct.h:59
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff81906348)
Location: include/linux/delayacct.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff811f47af)
Location: include/linux/delayacct.h:94
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff819903d7)
Location: include/linux/delayacct.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff8120cd2d)
Location: include/linux/delayacct.h:94
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff819ecbca)
Location: include/linux/delayacct.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff8122da4e)
Location: include/linux/delayacct.h:94
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff81a27e17)
Location: include/linux/delayacct.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff81241066)
Location: include/linux/delayacct.h:101
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810d082c)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff81253252)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810da7dc)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff812617b2)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810e3765)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff81291a47)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810e127d)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In mm/memory.c (ffffffff8129c348)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810e309d)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In mm/memory.c (ffffffff812a1608)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810f9af5)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In mm/memory.c (ffffffff812e2045)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
</details>
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
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/core.c (ffff80001013a3a4)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffff8000102f8a30)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (c0389d50)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (c051b248)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (c000000000187b68)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (c0000000003c2064)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffe0000e9b38)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffe000208e46)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810d4c8c)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff81259e02)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810c32dc)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff8124c1c5)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810d1acc)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff81257ba2)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
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
In kernel/sched/core.c (ffffffff810dc48c)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In mm/memory.c (ffffffff8126758b)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
</details>
</li>
</ul>

## Differences
