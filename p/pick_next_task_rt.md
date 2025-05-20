# Function: <code>pick_next_task_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bffc0)
Location: kernel/sched/rt.c:1465
Inline: True
```
**Symbols:**

```
ffffffff810bffc0-ffffffff810c0148: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c39e0)
Location: kernel/sched/rt.c:1527
Inline: True
```
**Symbols:**

```
ffffffff810c39e0-ffffffff810c3b7e: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c9a50)
Location: kernel/sched/rt.c:1526
Inline: True
```
**Symbols:**

```
ffffffff810c9a50-ffffffff810c9bee: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4b80)
Location: kernel/sched/rt.c:1538
Inline: False
```
**Symbols:**

```
ffffffff810c4b80-ffffffff810c4d78: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cc230)
Location: kernel/sched/rt.c:1528
Inline: False
```
**Symbols:**

```
ffffffff810cc230-ffffffff810cc42e: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d3f60)
Location: kernel/sched/rt.c:1537
Inline: False
```
**Symbols:**

```
ffffffff810d3f60-ffffffff810d4153: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ddc00)
Location: kernel/sched/rt.c:1541
Inline: False
```
**Symbols:**

```
ffffffff810ddc00-ffffffff810dde49: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4c00)
Location: kernel/sched/rt.c:1541
Inline: False
```
**Symbols:**

```
ffffffff810e4c00-ffffffff810e4e5c: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ee110)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffffffff810ee110-ffffffff810ee2d5: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7ae0)
Location: kernel/sched/rt.c:1627
Inline: False
```
**Symbols:**

```
ffffffff810f7ae0-ffffffff810f7c8a: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f5ce0)
Location: kernel/sched/rt.c:1629
Inline: False
```
**Symbols:**

```
ffffffff810f5ce0-ffffffff810f5e9a: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8040)
Location: kernel/sched/rt.c:1629
Inline: False
```
**Symbols:**

```
ffffffff810f8040-ffffffff810f81fa: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1656
Inline: False
```
**Symbols:**

```
ffffffff811136a0-ffffffff811138b5: pick_next_task_rt (STB_LOCAL)
ffffffff81ca6887-ffffffff81ca68b1: pick_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1815
Inline: False
```
**Symbols:**

```
ffffffff811383e0-ffffffff8113863d: pick_next_task_rt (STB_LOCAL)
ffffffff81e567f3-ffffffff81e5681d: pick_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1814
Inline: False
```
**Symbols:**

```
ffffffff81162ad0-ffffffff81162cbc: pick_next_task_rt (STB_LOCAL)
ffffffff82057a13-ffffffff82057a3d: pick_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1814
Inline: False
```
**Symbols:**

```
ffffffff81173250-ffffffff8117343c: pick_next_task_rt (STB_LOCAL)
ffffffff820d6239-ffffffff820d6263: pick_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1759
Inline: False
```
**Symbols:**

```
ffffffff81180b30-ffffffff81180d70: pick_next_task_rt (STB_LOCAL)
ffffffff821b13d7-ffffffff821b1401: pick_next_task_rt.cold (STB_LOCAL)
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
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014edc8)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffff80001014edc8-ffff80001014efac: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039d21c)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
c039d21c-c039d47c: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a3180)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
c0000000001a3180-c0000000001a3414: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f7c72)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffffffe0000f7c72-ffffffe0000f7e9e: pick_next_task_rt (STB_LOCAL)
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
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e7e10)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffffffff810e7e10-ffffffff810e7fca: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d7460)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffffffff810d7460-ffffffff810d7625: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4640)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffffffff810e4640-ffffffff810e4805: pick_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *pick_next_task_rt(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0ad0)
Location: kernel/sched/rt.c:1571
Inline: False
```
**Symbols:**

```
ffffffff810f0ad0-ffffffff810f0c8a: pick_next_task_rt (STB_LOCAL)
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
