# Function: <code>newidle_balance</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec030)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810ec030-ffffffff810ec401: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5ce0)
Location: kernel/sched/fair.c:10460
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810f5ce0-ffffffff810f6022: newidle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3e30)
Location: kernel/sched/fair.c:10574
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810f3e30-ffffffff810f417c: newidle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f56f0)
Location: kernel/sched/fair.c:10631
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810f56f0-ffffffff810f5ad2: newidle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10873
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff8110f390-ffffffff8110f7f8: newidle_balance (STB_LOCAL)
ffffffff81ca6732-ffffffff81ca6747: newidle_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10989
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff8112b350-ffffffff8112b7f9: newidle_balance (STB_LOCAL)
ffffffff81e55f5c-ffffffff81e55f71: newidle_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11516
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff81154d20-ffffffff811551c9: newidle_balance (STB_LOCAL)
ffffffff8205714e-ffffffff82057163: newidle_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11820
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff81164ed0-ffffffff81165375: newidle_balance (STB_LOCAL)
ffffffff820d597a-ffffffff820d598f: newidle_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12295
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff81171c20-ffffffff811720c5: newidle_balance (STB_LOCAL)
ffffffff821b09dd-ffffffff821b09f2: newidle_balance.cold (STB_LOCAL)
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
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014c4e8)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffff80001014c4e8-ffff80001014c8cc: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039a0bc)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
c039a0bc-c039a5b4: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019ee80)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
c00000000019ee80-c00000000019f3f8: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f5a0a)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffe0000f5a0a-ffffffe0000f5e16: newidle_balance (STB_GLOBAL)
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
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6190)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810e6190-ffffffff810e6561: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5330)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810d5330-ffffffff810d5701: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2560)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810e2560-ffffffff810e2931: newidle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int newidle_balance(struct rq *this_rq, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee110)
Location: kernel/sched/fair.c:9775
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810ee110-ffffffff810ee508: newidle_balance (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
