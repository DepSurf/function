# Function: <code>inactive_task_timer</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c67b0)
Location: kernel/sched/deadline.c:1193
Inline: False
```
**Symbols:**

```
ffffffff810c67b0-ffffffff810c6b5b: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ce020)
Location: kernel/sched/deadline.c:1192
Inline: False
```
**Symbols:**

```
ffffffff810ce020-ffffffff810ce397: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d7e70)
Location: kernel/sched/deadline.c:1251
Inline: False
```
**Symbols:**

```
ffffffff810d7e70-ffffffff810d8318: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810df610)
Location: kernel/sched/deadline.c:1250
Inline: False
```
**Symbols:**

```
ffffffff810df610-ffffffff810dfaa5: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e6200)
Location: kernel/sched/deadline.c:1249
Inline: False
```
**Symbols:**

```
ffffffff810e6200-ffffffff810e6689: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f1880)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffffffff810f1880-ffffffff810f1d15: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fae90)
Location: kernel/sched/deadline.c:1284
Inline: False
```
**Symbols:**

```
ffffffff810fae90-ffffffff810fb339: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f95b0)
Location: kernel/sched/deadline.c:1358
Inline: False
```
**Symbols:**

```
ffffffff810f95b0-ffffffff810f9a98: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb700)
Location: kernel/sched/deadline.c:1344
Inline: False
```
**Symbols:**

```
ffffffff810fb700-ffffffff810fbc01: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:1344
Inline: False
```
**Symbols:**

```
ffffffff81118540-ffffffff81118bab: inactive_task_timer (STB_LOCAL)
ffffffff81ca6cbd-ffffffff81ca6d59: inactive_task_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1407
Inline: False
```
**Symbols:**

```
ffffffff81132d90-ffffffff81133407: inactive_task_timer (STB_LOCAL)
ffffffff81e563b1-ffffffff81e5644d: inactive_task_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1408
Inline: False
```
**Symbols:**

```
ffffffff8115d0b0-ffffffff8115d744: inactive_task_timer (STB_LOCAL)
ffffffff820575b7-ffffffff82057677: inactive_task_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1399
Inline: False
```
**Symbols:**

```
ffffffff8116c9c0-ffffffff8116d064: inactive_task_timer (STB_LOCAL)
ffffffff820d5cf4-ffffffff820d5db4: inactive_task_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1464
Inline: False
```
**Symbols:**

```
ffffffff8117ac80-ffffffff8117b45e: inactive_task_timer (STB_LOCAL)
ffffffff821b0ed1-ffffffff821b0fac: inactive_task_timer.cold (STB_LOCAL)
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
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010153578)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffff800010153578-ffff800010153a4c: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a166c)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
c03a166c-c03a1c8c: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a7890)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
c0000000001a7890-c0000000001a7ed4: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fb2e6)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffffffe0000fb2e6-ffffffe0000fb6a6: inactive_task_timer (STB_LOCAL)
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
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eac80)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffffffff810eac80-ffffffff810eb115: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810daca0)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffffffff810daca0-ffffffff810db135: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7db0)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffffffff810e7db0-ffffffff810e8245: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum hrtimer_restart inactive_task_timer(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f3020)
Location: kernel/sched/deadline.c:1282
Inline: False
```
**Symbols:**

```
ffffffff810f3020-ffffffff810f34b1: inactive_task_timer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
