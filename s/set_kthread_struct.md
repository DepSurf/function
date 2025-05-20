# Function: <code>set_kthread_struct</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8c92)
Location: kernel/kthread.c:56
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810a5a82)
Location: kernel/kthread.c:59
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810acbd2)
Location: kernel/kthread.c:61
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810b2e26)
Location: kernel/kthread.c:60
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810bbc46)
Location: kernel/kthread.c:60
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810c1d96)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810c82f6)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0146)
Location: kernel/kthread.c:70
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cab36)
Location: kernel/kthread.c:71
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_kthread_struct(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd980)
Location: kernel/kthread.c:96
Inline: True
Direct callers:
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff810cd980-ffffffff810cd9c6: set_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_kthread_struct(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0b50)
Location: kernel/kthread.c:96
Inline: True
Direct callers:
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff810e0b50-ffffffff810e0b96: set_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool set_kthread_struct(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810faef0)
Location: kernel/kthread.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810faef0-ffffffff810fafb5: set_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool set_kthread_struct(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111dd80)
Location: kernel/kthread.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8111dd80-ffffffff8111de45: set_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool set_kthread_struct(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112af80)
Location: kernel/kthread.c:111
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8112af80-ffffffff8112b045: set_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool set_kthread_struct(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811356a0)
Location: kernel/kthread.c:111
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff811356a0-ffffffff81135794: set_kthread_struct (STB_GLOBAL)
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
In kernel/kthread.c (ffff800010127614)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (c037ae14)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (c000000000172ac0)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffe0000dec90)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810c2676)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810b0ec6)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810c1bc6)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
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
In kernel/kthread.c (ffffffff810c9ff6)
Location: kernel/kthread.c:63
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
