# Function: <code>pull_dl_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c2b10)
Location: kernel/sched/deadline.c:1580
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810c2b10-ffffffff810c2d83: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c6490)
Location: kernel/sched/deadline.c:1536
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810c6490-ffffffff810c671b: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cc470)
Location: kernel/sched/deadline.c:1525
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810cc470-ffffffff810cc708: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c5c90)
Location: kernel/sched/deadline.c:2053
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810c5c90-ffffffff810c614a: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cd650)
Location: kernel/sched/deadline.c:2047
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810cd650-ffffffff810cdae7: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d5d90)
Location: kernel/sched/deadline.c:2120
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810d5d90-ffffffff810d635d: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dfc60)
Location: kernel/sched/deadline.c:2123
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810dfc60-ffffffff810e022d: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:2118
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810e6690-ffffffff810e68d0: pull_dl_task (STB_LOCAL)
ffffffff810e965b-ffffffff810e96af: pull_dl_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f1f20)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810f1f20-ffffffff810f215e: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fd1d0)
Location: kernel/sched/deadline.c:2133
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810fd1d0-ffffffff810fd411: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb6e0)
Location: kernel/sched/deadline.c:2234
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810fb6e0-ffffffff810fb9de: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fd9f0)
Location: kernel/sched/deadline.c:2213
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810fd9f0-ffffffff810fdcf7: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81115e90)
Location: kernel/sched/deadline.c:2225
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff81115e90-ffffffff8111623b: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112faf0)
Location: kernel/sched/deadline.c:2378
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_dl
```
**Symbols:**

```
ffffffff8112faf0-ffffffff8112fe38: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81159bb0)
Location: kernel/sched/deadline.c:2381
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_dl
```
**Symbols:**

```
ffffffff81159bb0-ffffffff81159efc: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169dc0)
Location: kernel/sched/deadline.c:2373
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_dl
```
**Symbols:**

```
ffffffff81169dc0-ffffffff8116a10c: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81177460)
Location: kernel/sched/deadline.c:2468
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_dl
```
**Symbols:**

```
ffffffff81177460-ffffffff811777ce: pull_dl_task (STB_LOCAL)
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
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010153a50)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffff800010153a50-ffff800010153d90: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c039fd40)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
c039fd40-c03a00c0: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a6850)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
c0000000001a6850-c0000000001a6bf8: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fb784)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffe0000fb784-ffffffe0000fba50: pull_dl_task (STB_LOCAL)
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
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb320)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810eb320-ffffffff810eb55e: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810db340)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810db340-ffffffff810db579: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8450)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810e8450-ffffffff810e868e: pull_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pull_dl_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2750)
Location: kernel/sched/deadline.c:2134
Inline: False
Direct callers:
  - kernel/sched/deadline.c:balance_dl
```
**Symbols:**

```
ffffffff810f2750-ffffffff810f297f: pull_dl_task (STB_LOCAL)
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
