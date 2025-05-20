# Function: <code>select_task_rq_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bff20)
Location: kernel/sched/rt.c:1317
Inline: True
```
**Symbols:**

```
ffffffff810bff20-ffffffff810bffb1: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c38a0)
Location: kernel/sched/rt.c:1379
Inline: True
```
**Symbols:**

```
ffffffff810c38a0-ffffffff810c3930: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c9910)
Location: kernel/sched/rt.c:1378
Inline: True
```
**Symbols:**

```
ffffffff810c9910-ffffffff810c99a0: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c34a0)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffff810c34a0-ffffffff810c3537: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca980)
Location: kernel/sched/rt.c:1380
Inline: True
```
**Symbols:**

```
ffffffff810ca980-ffffffff810caa17: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d26a0)
Location: kernel/sched/rt.c:1389
Inline: True
```
**Symbols:**

```
ffffffff810d26a0-ffffffff810d272e: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dc010)
Location: kernel/sched/rt.c:1389
Inline: True
```
**Symbols:**

```
ffffffff810dc010-ffffffff810dc09e: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e2fe0)
Location: kernel/sched/rt.c:1389
Inline: True
```
**Symbols:**

```
ffffffff810e2fe0-ffffffff810e306a: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ed9d0)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffff810ed9d0-ffffffff810eda5a: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7e10)
Location: kernel/sched/rt.c:1431
Inline: True
```
**Symbols:**

```
ffffffff810f7e10-ffffffff810f7f5e: select_task_rq_rt.part.0 (STB_LOCAL)
ffffffff810f7f60-ffffffff810f7f7b: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f6020)
Location: kernel/sched/rt.c:1433
Inline: True
```
**Symbols:**

```
ffffffff810f6020-ffffffff810f6158: select_task_rq_rt.part.0 (STB_LOCAL)
ffffffff810f6160-ffffffff810f6178: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8200)
Location: kernel/sched/rt.c:1433
Inline: True
```
**Symbols:**

```
ffffffff810f8200-ffffffff810f8351: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff811131c0)
Location: kernel/sched/rt.c:1448
Inline: True
```
**Symbols:**

```
ffffffff811131c0-ffffffff811133b6: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f8e0)
Location: kernel/sched/rt.c:1603
Inline: True
```
**Symbols:**

```
ffffffff8112f8e0-ffffffff8112fae2: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81159990)
Location: kernel/sched/rt.c:1599
Inline: True
```
**Symbols:**

```
ffffffff81159990-ffffffff81159b92: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169ba0)
Location: kernel/sched/rt.c:1599
Inline: True
```
**Symbols:**

```
ffffffff81169ba0-ffffffff81169da2: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176f20)
Location: kernel/sched/rt.c:1544
Inline: True
```
**Symbols:**

```
ffffffff81176f20-ffffffff8117709f: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014e780)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffff80001014e780-ffff80001014e840: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039bda4)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
c039bda4-c039be5c: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a1be0)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
c0000000001a1be0-c0000000001a1d00: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f739a)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffe0000f739a-ffffffe0000f744a: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e7810)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffff810e7810-ffffffff810e789a: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d6c80)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffff810d6c80-ffffffff810d6d0a: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e3f00)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffff810e3f00-ffffffff810e3f8a: select_task_rq_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_rt(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810efc70)
Location: kernel/sched/rt.c:1390
Inline: True
```
**Symbols:**

```
ffffffff810efc70-ffffffff810efd15: select_task_rq_rt (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sd_flag</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, cpu, sd_flag, flags</code> ➡️ <code>p, cpu, flags</code>
</li>
</ul>
</details>
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
