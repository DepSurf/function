# Function: <code>task_tick_numa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb2b0)
Location: kernel/sched/fair.c:2301
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810bb2b0-ffffffff810bb368: task_tick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be740)
Location: kernel/sched/fair.c:2428
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810be740-ffffffff810be7f3: task_tick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c3a20)
Location: kernel/sched/fair.c:2560
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810c3a20-ffffffff810c3ad3: task_tick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be650)
Location: kernel/sched/fair.c:2557
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810be650-ffffffff810be70b: task_tick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6330)
Location: kernel/sched/fair.c:2609
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810c6330-ffffffff810c63eb: task_tick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cdd30)
Location: kernel/sched/fair.c:2637
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810cdd30-ffffffff810cddeb: task_tick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_tick_numa(struct rq *rq, struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7070)
Location: kernel/sched/fair.c:2583
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
```
**Symbols:**

```
ffffffff810d7070-ffffffff810d712b: task_tick_numa (STB_GLOBAL)
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
In kernel/sched/fair.c (ffffffff810dc81b)
Location: kernel/sched/fair.c:2671
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (ffffffff810e6c5b)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eea5b)
Location: kernel/sched/fair.c:2902
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec8a6)
Location: kernel/sched/fair.c:2916
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ef23c)
Location: kernel/sched/fair.c:2913
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811077bf)
Location: kernel/sched/fair.c:2902
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81124a18)
Location: kernel/sched/fair.c:2923
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114cc03)
Location: kernel/sched/fair.c:3131
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115af03)
Location: kernel/sched/fair.c:3188
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116c1c2)
Location: kernel/sched/fair.c:3486
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (ffff800010146b70)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:2738
Inline: True
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
In kernel/sched/fair.c (c000000000198030)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:2738
Inline: True
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
In kernel/sched/fair.c (ffffffff810e0e0b)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (ffffffff810cfeeb)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (ffffffff810dd18b)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
In kernel/sched/fair.c (ffffffff810e8ef8)
Location: kernel/sched/fair.c:2673
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
