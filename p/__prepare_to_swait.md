# Function: <code>__prepare_to_swait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c7480)
Location: kernel/sched/swait.c:75
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait
```
**Symbols:**

```
ffffffff810c7730-ffffffff810c776e: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810cd350)
Location: kernel/sched/swait.c:75
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait
```
**Symbols:**

```
ffffffff810cd5f0-ffffffff810cd62e: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c9d50)
Location: kernel/sched/swait.c:75
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait
```
**Symbols:**

```
ffffffff810ca010-ffffffff810ca04e: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d1570)
Location: kernel/sched/swait.c:70
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait
```
**Symbols:**

```
ffffffff810d1820-ffffffff810d185e: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d9b30)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait
```
**Symbols:**

```
ffffffff810d9de0-ffffffff810d9e1e: __prepare_to_swait (STB_GLOBAL)
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
In kernel/sched/swait.c (ffffffff810e3710)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
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
In kernel/sched/swait.c (ffffffff810ea360)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
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
In kernel/sched/swait.c (ffffffff810f5d30)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff508)
Location: kernel/sched/swait.c:85
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
Direct callers:
  - kernel/sched/completion.c:__wait_for_common
```
**Symbols:**

```
ffffffff810ff7b0-ffffffff810ff7ed: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fe068)
Location: kernel/sched/swait.c:85
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
Direct callers:
  - kernel/sched/completion.c:__wait_for_common
```
**Symbols:**

```
ffffffff810fe2c0-ffffffff810fe2fd: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff81100448)
Location: kernel/sched/swait.c:85
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
Direct callers:
  - kernel/sched/completion.c:__wait_for_common
```
**Symbols:**

```
ffffffff811006a0-ffffffff811006dd: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c4bf)
Location: kernel/sched/swait.c:85
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
Direct callers:
  - kernel/sched/completion.c:__wait_for_common
```
**Symbols:**

```
ffffffff8111c700-ffffffff8111c73d: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114265f)
Location: kernel/sched/swait.c:84
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_exclusive
  - kernel/sched/build_utility.c:__wait_for_common
```
**Symbols:**

```
ffffffff81148be0-ffffffff81148c35: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116fe8f)
Location: kernel/sched/swait.c:84
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_exclusive
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
```
**Symbols:**

```
ffffffff81177430-ffffffff81177485: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117fb4f)
Location: kernel/sched/swait.c:84
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_exclusive
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
```
**Symbols:**

```
ffffffff81188080-ffffffff811880d5: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118d0bf)
Location: kernel/sched/swait.c:84
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_exclusive
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
```
**Symbols:**

```
ffffffff811968d0-ffffffff81196925: __prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffff8000101593a8)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c03a68bc)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c0000000001ad924)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
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
In kernel/sched/swait.c (ffffffe0000ff42c)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
</details>
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
In kernel/sched/swait.c (ffffffff810ef130)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810df1b0)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
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
In kernel/sched/swait.c (ffffffff810ec260)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
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
In kernel/sched/swait.c (ffffffff810f7390)
Location: kernel/sched/swait.c:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
