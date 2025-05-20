# Function: <code>pick_next_task_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle_task.c (ffffffff810b1c60)
Location: kernel/sched/idle_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810b1c60-ffffffff810b1c85: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle_task.c (ffffffff810b4780)
Location: kernel/sched/idle_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810b4780-ffffffff810b47b4: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle_task.c (ffffffff810badb0)
Location: kernel/sched/idle_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810badb0-ffffffff810badf3: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle_task.c (ffffffff810b5650)
Location: kernel/sched/idle_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810b5650-ffffffff810b5696: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle_task.c (ffffffff810bc9a0)
Location: kernel/sched/idle_task.c:28
Inline: False
```
**Symbols:**

```
ffffffff810bc9a0-ffffffff810bc9ec: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c4050)
Location: kernel/sched/idle.c:392
Inline: False
```
**Symbols:**

```
ffffffff810c4050-ffffffff810c4099: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd350)
Location: kernel/sched/idle.c:377
Inline: False
```
**Symbols:**

```
ffffffff810cd350-ffffffff810cd399: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d5710)
Location: kernel/sched/idle.c:378
Inline: False
```
**Symbols:**

```
ffffffff810d5710-ffffffff810d5759: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810dfd10)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffffffff810dfd10-ffffffff810dfd62: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e80b0)
Location: kernel/sched/idle.c:411
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810e80b0-ffffffff810e80ee: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e5cd0)
Location: kernel/sched/idle.c:436
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810e5cd0-ffffffff810e5d0e: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e7c90)
Location: kernel/sched/idle.c:442
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810e7c90-ffffffff810e7cce: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff2e0)
Location: kernel/sched/idle.c:450
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff810ff2e0-ffffffff810ff308: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f4d0)
Location: kernel/sched/idle.c:446
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff8112f4d0-ffffffff8112f514: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81159290)
Location: kernel/sched/idle.c:446
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81159290-ffffffff811592d4: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169550)
Location: kernel/sched/idle.c:425
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81169550-ffffffff81169594: pick_next_task_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176710)
Location: kernel/sched/idle.c:456
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81176710-ffffffff81176754: pick_next_task_idle (STB_GLOBAL)
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
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff80001013f8c8)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffff80001013f8c8-ffff80001013f93c: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c038f7e0)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
c038f7e0-c038f87c: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018e9d0)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
c00000000018e9d0-c00000000018ea58: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0000edd08)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffffffe0000edd08-ffffffe0000edd7e: pick_next_task_idle (STB_LOCAL)
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
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d9f00)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffffffff810d9f00-ffffffff810d9f52: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c8ef0)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffffffff810c8ef0-ffffffff810c8f42: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d6240)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffffffff810d6240-ffffffff810d6292: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *pick_next_task_idle(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e1b50)
Location: kernel/sched/idle.c:395
Inline: False
```
**Symbols:**

```
ffffffff810e1b50-ffffffff810e1ba2: pick_next_task_idle (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pin_cookie cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags *rf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pin_cookie cookie</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_flags *rf</code>
</li>
</ul>
</details>
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
