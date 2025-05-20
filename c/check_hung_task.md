# Function: <code>check_hung_task</code>

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
In kernel/hung_task.c (ffffffff8113a586)
Location: kernel/hung_task.c:75
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff81142ade)
Location: kernel/hung_task.c:75
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff8114c8c0)
Location: kernel/hung_task.c:75
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff8114e838)
Location: kernel/hung_task.c:79
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff8115b0c8)
Location: kernel/hung_task.c:79
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff81169cd5)
Location: kernel/hung_task.c:80
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff81176b9f)
Location: kernel/hung_task.c:86
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff811839d8)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff8118f848)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:87
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff811a40d0-ffffffff811a41c4: check_hung_task (STB_LOCAL)
ffffffff811a4582-ffffffff811a462c: check_hung_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:87
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff811a1230-ffffffff811a1315: check_hung_task (STB_LOCAL)
ffffffff81be4e8c-ffffffff81be4f36: check_hung_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:87
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff811a1e90-ffffffff811a1f75: check_hung_task (STB_LOCAL)
ffffffff81bd6d00-ffffffff81bd6daa: check_hung_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:88
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff811cb650-ffffffff811cb72c: check_hung_task (STB_LOCAL)
ffffffff81cb3da3-ffffffff81cb3e54: check_hung_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:90
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff811ff330-ffffffff811ff472: check_hung_task (STB_LOCAL)
ffffffff81e64c53-ffffffff81e64d01: check_hung_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/hung_task.c (ffffffff81246c70)
Location: kernel/hung_task.c:90
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff81246c70-ffffffff81246e6c: check_hung_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/hung_task.c (ffffffff8125dce0)
Location: kernel/hung_task.c:90
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff8125dce0-ffffffff8125defb: check_hung_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_hung_task(struct task_struct *t, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/hung_task.c (ffffffff81277c20)
Location: kernel/hung_task.c:90
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff81277c20-ffffffff81277e3c: check_hung_task (STB_LOCAL)
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
In kernel/hung_task.c (ffff800010206ee4)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (c0445cc4)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (c00000000028348c)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffe00016964c)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff81187e68)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff8117afa8)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff81185c38)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
In kernel/hung_task.c (ffffffff81193577)
Location: kernel/hung_task.c:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
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
