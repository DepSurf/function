# Function: <code>prepare_task_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8181fb33)
Location: kernel/sched/core.c:2509
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8189a269)
Location: kernel/sched/core.c:2692
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff818ce887)
Location: kernel/sched/core.c:2702
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81905ca0)
Location: kernel/sched/core.c:2570
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8198fd1c)
Location: kernel/sched/core.c:2589
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff819ec568)
Location: kernel/sched/core.c:2634
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81a277ea)
Location: kernel/sched/core.c:2623
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81a9808c)
Location: kernel/sched/core.c:3033
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81acf962)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddd60)
Location: kernel/sched/core.c:3314
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810ddd60-ffffffff810ddf8a: prepare_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da2d0)
Location: kernel/sched/core.c:4119
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810da2d0-ffffffff810da4fa: prepare_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc8f0)
Location: kernel/sched/core.c:4140
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810dc8f0-ffffffff810dcb88: prepare_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4752
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810f1470-ffffffff810f173d: prepare_task_switch (STB_LOCAL)
ffffffff81ca5be4-ffffffff81ca5c23: prepare_task_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4961
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8110d860-ffffffff8110db3b: prepare_task_switch (STB_LOCAL)
ffffffff81e55508-ffffffff81e55547: prepare_task_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:5100
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81134580-ffffffff8113485b: prepare_task_switch (STB_LOCAL)
ffffffff82056975-ffffffff820569b4: prepare_task_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:5178
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81143780-ffffffff81143a5d: prepare_task_switch (STB_LOCAL)
ffffffff820d5061-ffffffff820d50a0: prepare_task_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void prepare_task_switch(struct rq *rq, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:5199
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8114eca0-ffffffff8114ef7d: prepare_task_switch (STB_LOCAL)
ffffffff821aff84-ffffffff821affc3: prepare_task_switch.cold (STB_LOCAL)
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
In kernel/sched/core.c (ffff800010da15a4)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (c0e995f0)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (c000000000ee2618)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffe0008c4e28)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81a6e7d2)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81a2abcb)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81adabe2)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81ae7094)
Location: kernel/sched/core.c:3153
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
