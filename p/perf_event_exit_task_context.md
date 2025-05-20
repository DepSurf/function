# Function: <code>perf_event_exit_task_context</code>

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
In kernel/events/core.c (ffffffff811848b2)
Location: kernel/events/core.c:8799
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8119662c)
Location: kernel/events/core.c:9987
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811a60ac)
Location: kernel/events/core.c:10247
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811ad833)
Location: kernel/events/core.c:10494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811c13ba)
Location: kernel/events/core.c:10526
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811e16fc)
Location: kernel/events/core.c:11056
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811f1b6c)
Location: kernel/events/core.c:11099
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81209746)
Location: kernel/events/core.c:11450
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81216ab6)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_exit_task_context(struct task_struct *child, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240ac0)
Location: kernel/events/core.c:12166
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff81240ac0-ffffffff81240e27: perf_event_exit_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_exit_task_context(struct task_struct *child, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124b070)
Location: kernel/events/core.c:12450
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8124b070-ffffffff8124b3d8: perf_event_exit_task_context (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812517cc)
Location: kernel/events/core.c:12636
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8128cfec)
Location: kernel/events/core.c:12757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff812e1cbc)
Location: kernel/events/core.c:12727
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8134a27c)
Location: kernel/events/core.c:12972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8137b2bc)
Location: kernel/events/core.c:13014
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff813a44bc)
Location: kernel/events/core.c:13110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
void perf_event_exit_task_context(struct task_struct *child, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029e9a8)
Location: kernel/events/core.c:11563
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffff80001029e9a8-ffff80001029eca4: perf_event_exit_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_exit_task_context(struct task_struct *child, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ce1b4)
Location: kernel/events/core.c:11563
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
c04ce1b4-c04ce578: perf_event_exit_task_context (STB_LOCAL)
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
In kernel/events/core.c (c000000000352d74)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffe0001d0030)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8120f106)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81201eb6)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8120cea6)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8121bd36)
Location: kernel/events/core.c:11563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
<b>Arch</b>
<ul>
</ul>
