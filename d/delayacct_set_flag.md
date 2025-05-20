# Function: <code>delayacct_set_flag</code>

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
In kernel/sched/core.c (ffffffff8181f8eb)
Location: include/linux/delayacct.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In mm/memory.c (ffffffff811bf533)
Location: include/linux/delayacct.h:53
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81899feb)
Location: include/linux/delayacct.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In mm/memory.c (ffffffff811d9ac9)
Location: include/linux/delayacct.h:53
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff818ce68b)
Location: include/linux/delayacct.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In mm/memory.c (ffffffff811e95ff)
Location: include/linux/delayacct.h:53
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff819060e5)
Location: include/linux/delayacct.h:88
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff811f476f)
Location: include/linux/delayacct.h:88
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff8199012c)
Location: include/linux/delayacct.h:88
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff8120c564)
Location: include/linux/delayacct.h:88
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff819eca2d)
Location: include/linux/delayacct.h:88
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff8122d212)
Location: include/linux/delayacct.h:88
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81a27d0b)
Location: include/linux/delayacct.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff812407a6)
Location: include/linux/delayacct.h:95
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81a983ff)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff81252a4c)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81acfcc4)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff81260fac)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81bc87dc)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff81291431)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81c41581)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff8129bda1)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81c334f9)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff812a1048)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81d51e0c)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff812e1fc4)
Location: include/linux/delayacct.h:91
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffff800010da1b38)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffff8000102f8358)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (c0e99918)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (c051ab30)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (c000000000ee2b44)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (c0000000003c16bc)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffe0008c50cc)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffe0002088e2)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81a6eb34)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff812595fc)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81a2af1e)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff8124ba73)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81adaf44)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff8125739c)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81ae7406)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In mm/memory.c (ffffffff81266d8c)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
</details>
</li>
</ul>

## Differences
