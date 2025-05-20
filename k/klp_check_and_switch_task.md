# Function: <code>klp_check_and_switch_task</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_check_and_switch_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81183dac)
Location: kernel/livepatch/transition.c:268
Inline: True
```
**Symbols:**

```
ffffffff81183d00-ffffffff81183eee: klp_check_and_switch_task (STB_LOCAL)
ffffffff81e60be2-ffffffff81e60bf7: klp_check_and_switch_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_check_and_switch_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811befd8)
Location: kernel/livepatch/transition.c:268
Inline: True
```
**Symbols:**

```
ffffffff811bef30-ffffffff811bf0e2: klp_check_and_switch_task (STB_LOCAL)
ffffffff8205a687-ffffffff8205a69c: klp_check_and_switch_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_check_and_switch_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811d1891)
Location: kernel/livepatch/transition.c:293
Inline: True
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff811d17d0-ffffffff811d19a1: klp_check_and_switch_task (STB_LOCAL)
ffffffff820d8efb-ffffffff820d8f10: klp_check_and_switch_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_check_and_switch_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811e6511)
Location: kernel/livepatch/transition.c:293
Inline: True
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff811e6450-ffffffff811e6621: klp_check_and_switch_task (STB_LOCAL)
ffffffff821b4634-ffffffff821b4649: klp_check_and_switch_task.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
