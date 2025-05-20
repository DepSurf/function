# Function: <code>taskstats_tgid_alloc</code>

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
In kernel/taskstats.c (ffffffff8113ec21)
Location: kernel/taskstats.c:582
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81147251)
Location: kernel/taskstats.c:555
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff811510f1)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81153771)
Location: kernel/taskstats.c:568
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8115ff71)
Location: kernel/taskstats.c:568
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8116eeae)
Location: kernel/taskstats.c:564
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8117c9ae)
Location: kernel/taskstats.c:564
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8118986e)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff811957ae)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct taskstats *taskstats_tgid_alloc(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a9ca0)
Location: kernel/taskstats.c:554
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811a9ca0-ffffffff811a9d5e: taskstats_tgid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct taskstats *taskstats_tgid_alloc(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a72c0)
Location: kernel/taskstats.c:550
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811a72c0-ffffffff811a737e: taskstats_tgid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct taskstats *taskstats_tgid_alloc(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a7e00)
Location: kernel/taskstats.c:550
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811a7e00-ffffffff811a7ebe: taskstats_tgid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct taskstats *taskstats_tgid_alloc(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811d1930)
Location: kernel/taskstats.c:550
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811d1930-ffffffff811d19ee: taskstats_tgid_alloc (STB_LOCAL)
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
In kernel/taskstats.c (ffffffff81206f34)
Location: kernel/taskstats.c:572
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8124f2a4)
Location: kernel/taskstats.c:572
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81266654)
Location: kernel/taskstats.c:572
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81280544)
Location: kernel/taskstats.c:571
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffff80001020d998)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (c044c438)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (c00000000028bac4)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffe00016e96c)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8118ddce)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81180ede)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8118bb9e)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8119951e)
Location: kernel/taskstats.c:554
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
</ul>
