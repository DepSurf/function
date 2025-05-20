# Function: <code>pick_next_task_fair</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bdb40)
Location: kernel/sched/fair.c:5214
Inline: False
```
**Symbols:**

```
ffffffff810bdb40-ffffffff810be021: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1350)
Location: kernel/sched/fair.c:5675
Inline: False
```
**Symbols:**

```
ffffffff810c1350-ffffffff810c180e: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7350)
Location: kernel/sched/fair.c:6216
Inline: False
```
**Symbols:**

```
ffffffff810c7350-ffffffff810c77fc: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0f20)
Location: kernel/sched/fair.c:6182
Inline: False
```
**Symbols:**

```
ffffffff810c0f20-ffffffff810c1476: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c8650)
Location: kernel/sched/fair.c:6619
Inline: False
```
**Symbols:**

```
ffffffff810c8650-ffffffff810c8c20: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0c30)
Location: kernel/sched/fair.c:6904
Inline: False
```
**Symbols:**

```
ffffffff810d0c30-ffffffff810d1237: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da470)
Location: kernel/sched/fair.c:6898
Inline: False
```
**Symbols:**

```
ffffffff810da470-ffffffff810dab52: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1790)
Location: kernel/sched/fair.c:6792
Inline: False
```
**Symbols:**

```
ffffffff810e1790-ffffffff810e1f1a: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec440)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffffffff810ec440-ffffffff810ec7dd: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6060)
Location: kernel/sched/fair.c:6966
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff810f6060-ffffffff810f643f: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f41b0)
Location: kernel/sched/fair.c:7038
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff810f41b0-ffffffff810f45ae: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5b10)
Location: kernel/sched/fair.c:7144
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff810f5b10-ffffffff810f5ee4: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:7274
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff81ca6747-ffffffff81ca675c: pick_next_task_fair.cold (STB_LOCAL)
ffffffff8110f830-ffffffff8110fc51: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:7248
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff81e55f71-ffffffff81e55f85: pick_next_task_fair.cold (STB_LOCAL)
ffffffff8112b840-ffffffff8112bc60: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:7700
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff82057163-ffffffff820571b3: pick_next_task_fair.cold (STB_LOCAL)
ffffffff81155230-ffffffff81155870: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8058
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff820d598f-ffffffff820d59df: pick_next_task_fair.cold (STB_LOCAL)
ffffffff811653e0-ffffffff811659e1: pick_next_task_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8380
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:__pick_next_task_fair
```
**Symbols:**

```
ffffffff821b09f2-ffffffff821b0a57: pick_next_task_fair.cold (STB_LOCAL)
ffffffff81172130-ffffffff81172750: pick_next_task_fair (STB_GLOBAL)
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
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014c928)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffff80001014c928-ffff80001014cc98: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039a5f0)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
c039a5f0-c039a9bc: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019f460)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
c00000000019f460-c00000000019f90c: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f5e52)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffffffe0000f5e52-ffffffe0000f6114: pick_next_task_fair (STB_LOCAL)
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
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e65a0)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffffffff810e65a0-ffffffff810e693d: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5740)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffffffff810d5740-ffffffff810d5add: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2970)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffffffff810e2970-ffffffff810e2d0d: pick_next_task_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *pick_next_task_fair(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee540)
Location: kernel/sched/fair.c:6752
Inline: False
```
**Symbols:**

```
ffffffff810ee540-ffffffff810ee8dd: pick_next_task_fair (STB_LOCAL)
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
