# Function: <code>reweight_task</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6550)
Location: kernel/sched/fair.c:2814
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810c6550-ffffffff810c6599: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce420)
Location: kernel/sched/fair.c:2842
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810ce420-ffffffff810ce469: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7910)
Location: kernel/sched/fair.c:2823
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810d7910-ffffffff810d7959: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ded50)
Location: kernel/sched/fair.c:2908
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810ded50-ffffffff810ded99: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9440)
Location: kernel/sched/fair.c:2908
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810e9440-ffffffff810e9489: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f39b0)
Location: kernel/sched/fair.c:3109
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f39b0-ffffffff810f39f6: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1bf0)
Location: kernel/sched/fair.c:3123
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f1bf0-ffffffff810f1c36: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3ed0)
Location: kernel/sched/fair.c:3120
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f3ed0-ffffffff810f3f16: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110d7e0)
Location: kernel/sched/fair.c:3110
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff8110d7e0-ffffffff8110d862: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81129470)
Location: kernel/sched/fair.c:3137
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
**Symbols:**

```
ffffffff81129470-ffffffff811294fe: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81152f10)
Location: kernel/sched/fair.c:3345
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
**Symbols:**

```
ffffffff81152f10-ffffffff81152f9e: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811627c0)
Location: kernel/sched/fair.c:3402
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
**Symbols:**

```
ffffffff811627c0-ffffffff8116284e: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116f290)
Location: kernel/sched/fair.c:3832
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
**Symbols:**

```
ffffffff8116f290-ffffffff8116f31e: reweight_task (STB_GLOBAL)
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
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101492e8)
Location: kernel/sched/fair.c:2908
Inline: False
```
**Symbols:**

```
ffff8000101492e8-ffff800010149344: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039703c)
Location: kernel/sched/fair.c:2908
Inline: False
```
**Symbols:**

```
c039703c-c0397088: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019b180)
Location: kernel/sched/fair.c:2908
Inline: False
```
**Symbols:**

```
c00000000019b180-c00000000019b1f8: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f3264)
Location: kernel/sched/fair.c:2908
Inline: False
```
**Symbols:**

```
ffffffe0000f3264-ffffffe0000f32be: reweight_task (STB_GLOBAL)
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
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e35f0)
Location: kernel/sched/fair.c:2908
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810e35f0-ffffffff810e3639: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d26f0)
Location: kernel/sched/fair.c:2908
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810d26f0-ffffffff810d2739: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df970)
Location: kernel/sched/fair.c:2908
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810df970-ffffffff810df9b9: reweight_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reweight_task(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb540)
Location: kernel/sched/fair.c:2908
Inline: False
Direct callers:
  - kernel/sched/core.c:set_load_weight
```
**Symbols:**

```
ffffffff810eb540-ffffffff810eb589: reweight_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
