# Function: <code>detach_one_task</code>

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
In kernel/sched/fair.c (ffffffff810b3c47)
Location: kernel/sched/fair.c:5751
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810b6f62)
Location: kernel/sched/fair.c:6212
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810bc832)
Location: kernel/sched/fair.c:6753
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810b70d7)
Location: kernel/sched/fair.c:6716
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810c0701)
Location: kernel/sched/fair.c:7162
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810c7ef5)
Location: kernel/sched/fair.c:7449
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810d29ec)
Location: kernel/sched/fair.c:7455
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810da6be)
Location: kernel/sched/fair.c:7354
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810e5a1e)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *detach_one_task(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f16c0)
Location: kernel/sched/fair.c:7573
Inline: False
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
**Symbols:**

```
ffffffff810f16c0-ffffffff810f1763: detach_one_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *detach_one_task(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eeb60)
Location: kernel/sched/fair.c:7649
Inline: False
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
**Symbols:**

```
ffffffff810eeb60-ffffffff810eec03: detach_one_task (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810f2a3f)
Location: kernel/sched/fair.c:7765
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff8110a060)
Location: kernel/sched/fair.c:7903
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff81125a2f)
Location: kernel/sched/fair.c:7877
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff8114ecbc)
Location: kernel/sched/fair.c:8329
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff8116029b)
Location: kernel/sched/fair.c:8687
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff8116a6cb)
Location: kernel/sched/fair.c:9010
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffff800010145310)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (c0391c64)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (c0000000001958d4)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffe0000f006a)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810dfbce)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810cebd4)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810dbf4e)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/fair.c (ffffffff810e7c13)
Location: kernel/sched/fair.c:7316
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
</ul>
