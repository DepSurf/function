# Function: <code>_sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa030)
Location: kernel/sched/core.c:4025
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810aa030-ffffffff810aa0bc: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810accb0)
Location: kernel/sched/core.c:4275
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810accb0-ffffffff810acd3c: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2d40)
Location: kernel/sched/core.c:4312
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810b2d40-ffffffff810b2dcc: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aec60)
Location: kernel/sched/core.c:4212
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810aec60-ffffffff810aecef: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5ea0)
Location: kernel/sched/core.c:4256
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810b5ea0-ffffffff810b5f2f: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdb00)
Location: kernel/sched/core.c:4386
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810bdb00-ffffffff810bdb8e: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6cb0)
Location: kernel/sched/core.c:4371
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810c6cb0-ffffffff810c6d3e: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd1f0)
Location: kernel/sched/core.c:4808
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810cd1f0-ffffffff810cd284: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6be0)
Location: kernel/sched/core.c:5023
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810d6be0-ffffffff810d6c74: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3c98)
Location: kernel/sched/core.c:5256
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810e14e0-ffffffff810e1572: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e16e8)
Location: kernel/sched/core.c:6031
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810de860-ffffffff810de8f2: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e34f8)
Location: kernel/sched/core.c:6332
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810e0450-ffffffff810e04e2: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810f59e6)
Location: kernel/sched/core.c:7495
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810f56c0-ffffffff810f5752: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81112526)
Location: kernel/sched/core.c:7603
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff81112170-ffffffff81112217: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff811395b6)
Location: kernel/sched/core.c:7745
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff81139190-ffffffff81139237: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81148826)
Location: kernel/sched/core.c:7854
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff81148400-ffffffff811484a7: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81154046)
Location: kernel/sched/core.c:7915
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff81153b30-ffffffff81153bd7: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff8000101373c0)
Location: kernel/sched/core.c:5023
Inline: True
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffff8000101373c0-ffff80001013747c: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0386314)
Location: kernel/sched/core.c:5023
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
c0386314-c03863d8: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c0000000001829c0)
Location: kernel/sched/core.c:5023
Inline: True
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
c0000000001829c0-c000000000182a7c: _sched_setscheduler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7b5a)
Location: kernel/sched/core.c:5023
Inline: True
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffe0000e7b5a-ffffffe0000e7bea: _sched_setscheduler.isra.0 (STB_LOCAL)
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
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d11b0)
Location: kernel/sched/core.c:5023
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810d11b0-ffffffff810d1244: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf520)
Location: kernel/sched/core.c:5023
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810bf520-ffffffff810bf5b4: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf270)
Location: kernel/sched/core.c:5023
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810cf270-ffffffff810cf304: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8890)
Location: kernel/sched/core.c:5023
Inline: False
Direct callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810d8890-ffffffff810d8924: _sched_setscheduler (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
