# Function: <code>check_hung_uninterruptible_tasks</code>

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
In kernel/hung_task.c (ffffffff8113a463)
Location: kernel/hung_task.c:158
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
In kernel/hung_task.c (ffffffff81142994)
Location: kernel/hung_task.c:158
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
In kernel/hung_task.c (ffffffff8114c774)
Location: kernel/hung_task.c:159
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
In kernel/hung_task.c (ffffffff8114e6dd)
Location: kernel/hung_task.c:165
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
In kernel/hung_task.c (ffffffff8115af6d)
Location: kernel/hung_task.c:165
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
In kernel/hung_task.c (ffffffff81169bb4)
Location: kernel/hung_task.c:164
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
In kernel/hung_task.c (ffffffff81176a5f)
Location: kernel/hung_task.c:171
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
In kernel/hung_task.c (ffffffff8118385e)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (ffffffff8118f6ce)
Location: kernel/hung_task.c:173
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
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:175
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff811a41d0-ffffffff811a4495: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff811a462c-ffffffff811a4638: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:175
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff811a1320-ffffffff811a15ef: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff81be4f36-ffffffff81be4f42: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:175
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff811a1f80-ffffffff811a2247: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff81bd6daa-ffffffff81bd6db6: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:176
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff811cb730-ffffffff811cba21: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff81cb3e54-ffffffff81cb3e9c: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:178
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff811ff4d0-ffffffff811ff7e9: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff81e64d01-ffffffff81e64d49: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:178
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81246ee0-ffffffff812471f2: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff8205c8d7-ffffffff8205c913: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:180
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff8125df70-ffffffff8125e285: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff820db24d-ffffffff820db289: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_hung_uninterruptible_tasks(long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:180
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81277eb0-ffffffff812781c5: check_hung_uninterruptible_tasks (STB_LOCAL)
ffffffff821b6f74-ffffffff821b6fb0: check_hung_uninterruptible_tasks.cold (STB_LOCAL)
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
In kernel/hung_task.c (ffff800010206ddc)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (c0445b8c)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (c000000000283330)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (ffffffe000169608)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (ffffffff81187cee)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (ffffffff8117ae2e)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (ffffffff81185abe)
Location: kernel/hung_task.c:173
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
In kernel/hung_task.c (ffffffff811933f2)
Location: kernel/hung_task.c:173
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
